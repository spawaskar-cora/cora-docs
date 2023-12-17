# Changing the language

!!! warning

    This page is work in progress.

CoRA supports internationalization (i18n) and provides translations for 
template variables and labels in many languages.

## Configuration

### Site language

<!-- md:version 1.0.0 -->
<!-- md:default `en` -->

1.  HTML5 only allows to set a [single language per document], which is why
    CoRA only supports setting a canonical language for the
    entire project.

    The easiest way to build a multi-language documentation is to create one
    project in a subfolder per language, and then use the [language selector]
    to interlink those projects.

The following languages are supported:

<!-- hooks/translations.py -->

!!! tip "Translations missing? Help us out, it takes only 5 minutes"

    CoRA relies on outside contributions for adding and updating translations 
    for the more than 60 languages it supports. If your language shows that some
    translations are missing, click on the link to add them. If your language
    is not in the list, click here to [add a new language].

  [single language per document]: https://www.w3.org/International/questions/qa-html-language-declarations.en#attributes
  [language selector]: #site-language-selector
  [add a new language]: https://github.com/spawaskar-cora/cora-docs/issues/new?template=04-add-a-translation.yml&title=Add+translations+for+...

### Site language selector

<!-- md:version 2.5.0 -->
<!-- md:default none -->

If your documentation is available in multiple languages, a language selector
pointing to those languages can be added to the header. Alternate languages
can be defined via `mkdocs.yml`.

``` yaml
extra:
  alternate:
    - name: English
      link: /en/ # (1)!
      lang: en
    - name: Deutsch
      link: /de/
      lang: de
```

1.  Note that this must be an absolute link. If it includes a domain part, it's
    used as defined. Otherwise the domain part of the [`site_url`][site_url] as
    set in `mkdocs.yml` is prepended to the link.

The following properties are available for each alternate language:

<!-- md:option alternate.name -->

:   <!-- md:default none --> <!-- md:flag required -->
    This value of this property is used inside the language selector as the
    name of the language and must be set to a non-empty string.

<!-- md:option alternate.link -->

:   <!-- md:default none --> <!-- md:flag required -->
    This property must be set to an absolute link, which might also point to
    another domain or subdomain not necessarily generated with MkDocs.

<!-- md:option alternate.lang -->

:   <!-- md:default none --> <!-- md:flag required -->
    This property must contain an [ISO 639-1 language code] and is used for
    the `hreflang` attribute of the link, improving discoverability via search
    engines.

  [site_url]: https://www.mkdocs.org/user-guide/configuration/#site_url
  [ISO 639-1 language code]: https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes

### Directionality

<!-- md:version 2.5.0 -->
<!-- md:default computed -->

While many languages are read `ltr` (left-to-right), CoRA also
supports `rtl` (right-to-left) directionality which is deduced from the
selected language, but can also be set with:

``` yaml
theme:
  direction: ltr
```

Click on a tile to change the directionality:

<div class="mdx-switch">
  <button data-md-dir="ltr"><code>ltr</code></button>
  <button data-md-dir="rtl"><code>rtl</code></button>
</div>

<script>
  var buttons = document.querySelectorAll("button[data-md-dir]")
  buttons.forEach(function(button) {
    button.addEventListener("click", function() {
      var attr = this.getAttribute("data-md-dir")
      document.body.dir = attr
      var name = document.querySelector("#__code_2 code span.l")
      name.textContent = attr
    })
  })
</script>

  [theme extension]: ../getting-started/customization.md#extending-the-theme
  [translations]: https://github.com/spawaskar-cora/cora-docs/blob/master/src/templates/partials/languages/
  [list of available languages]: https://github.com/spawaskar-cora/cora-docs/blob/master/src/templates/partials/languages/