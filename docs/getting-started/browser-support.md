# Browser support

!!! warning

    This page is work in progress.

CoRA goes at great lengths to support the largest possible range
of browsers while retaining the simplest possibilities for customization via
modern CSS features like [custom properties] and [mask images].

  [custom properties]: https://caniuse.com/css-variables
  [mask images]: https://caniuse.com/mdn-css_properties_mask-image

## Recommended browsers

CoRA is optimized for the Google Chrome browser and we have extensively tested
its functionaility on the Chrome browser. The product will work on other browsers
such as Apple Safari, Mozilla Firefox and Microsoft Edge. 

!!! tip

    Always make sure that you keep your OS and Browser updated and current, using 
    older verions may compromise functionality

## Supported browsers

The following table lists all browsers for which CoRA offers full
support, so it can be assumed that all features work without degradation. If you
find that something doesn't look right in a browser which is in the supported
version range, please [open an issue]:

<figure markdown>

| Browser                              | Version | Release date |         |        |      Usage |
| ------------------------------------ | ------: | -----------: | ------: | -----: | ---------: |
|                                      |         |              | desktop | mobile |    overall |
| :fontawesome-brands-chrome: Chrome   |     49+ |      03/2016 | 25.65%  | 38.33% |     63.98% |
| :fontawesome-brands-safari: Safari   |     10+ |      09/2016 |  4.63%  | 14.96% |     19.59% |
| :fontawesome-brands-edge: Edge       |     79+ |      01/2020 |  3.95%  |    n/a |      3.95% |
| :fontawesome-brands-firefox: Firefox |     53+ |      04/2017 |  3.40%  |   .30% |      3.70% |
| :fontawesome-brands-opera: Opera     |     36+ |      03/2016 |  1.44%  |   .01% |      1.45% |
|                                      |         |              |         |        | __92.67%__ |

  <figcaption markdown>

Browser support matrix sourced from [caniuse.com].[^1]

  </figcaption>
</figure>

  [^1]:
    The data was collected from [caniuse.com] in December 2023, and is primarily
    based on browser support for [custom properties], [mask images] and the
    [:is pseudo selector] which are not entirely polyfillable. Browsers with a
    cumulated market share of less than 1% were not considered, but might still
    be fully or partially supported.

Note that the usage data is based on global browser market share, so it could
in fact be entirely different for your target demographic. It's a good idea to
check the distribution of browser types and versions among your users.

  [open an issue]: https://github.com/spawaskar-cora/cora-docs/issues/new/choose
  [caniuse.com]: https://caniuse.com/
  [:is pseudo selector]: https://caniuse.com/css-matches-pseudo
  [browser support]: #supported-browsers
  [built-in privacy plugin]: plugins/privacy.md


!!! danger

    CoRA will not work on the Microsoft Internet Explorer 11 browser. Microsoft Support 
    for Internet Explorer ended on June 15, 2022

## Other browsers

Albeit your site might not look as perfect as when viewed with a modern browser,
the following older browser versions might work with some additional effort:

- :fontawesome-brands-firefox: __Firefox 31-52__ – icons will render as little
  boxes due to missing support for [mask images]. While this cannot be
  polyfilled, it might be mitigated by hiding the icons altogether.
- :fontawesome-brands-edge: __Edge 16-18__ – the spacing of some elements might
  be a little off due to missing support for the [:is pseudo selector], which
  can be mitigated with some additional effort.
- :fontawesome-brands-internet-explorer: __Internet Explorer__ - no support,
  mainly due to missing support for [custom properties]. Microsoft Support for 
  Internet Explorer ended on June 15, 2022
  <!-- md:version 4.6.3 -->.