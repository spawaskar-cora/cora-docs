# Dashboards

!!! warning

    This page is work in progress.

# Dashboard Navigation

![](media/dashboard-navigation.png)

![](media/dashboard-navigation.gif)

On the left side bar - you can access the main options for dashboards. 

There are three different dashboards available in CoRA with each view being driven by the user's profile attributes.
1.  The Org Admin Dashboard
2.  The Project Manager Dashboard
3.  The User Dashboard

## Dashboard Widgets

 Dashboards are made of many different widgets.  These widgets provide visualization for the data they represent.  Widgets can display Pie Charts, Line Charts, Bar Charts, Maps, etc...

![](media/dashboard-widget.png)
  
Widgets come with a handful of standard features/functions. 

1.  Last Updated Timestamp :-  It shows the latest date when the data was updated. From the above image the last updated timestamp is shown at bottom left corner

2.  Mouse Over Detail :- On hovering over the graphs present in the widgets provides information on data.
![](media/mouse-over-data.png)

3.  View Details (Drill Into The Data) :- On click of details from the widget gives all the details of the visual data represented.
![](media/view-details.png)

4.  Widget Controls :- The common widget controls present on all the widgets are
* Collapse
* Close
![](media/widget-control.png)
* Help-Cora Docs
  ![](media/widget-control-help.png)

## Pie Chart

The widgets that shows data in pie chart has different options to view data.


1. Semi Circle:- Clicking on the semi-circle option provides a dynamic semicircle view, offering a perspective on data representation.

![](media/semi-circle-widget.png)

![](media/semi-circle-pie-chart.png)

2. Full Circle:- Clicking on the full-circle option provides a dynamic full circle view, offering a perspective on data representation.

![](media/full-circle-widget.png)

![](media/full-circle-pie-chart.png)

3. Show Donut:- Clicking on Donut option provides a dynamic donut view of data representation.

![](media/donut-widget.png)

![](media/donut-pie-chart.png)

4. Show Pie:- Clicking on Pie option provides a dynamic Pie view of data representation.

![](media/pie-widget.png)

![](media/pie-chart-main.png)

## Bar Graph & Stacked Bar Graph

The widgets for bar graph has a toggle switch. 

The toggle switch has 2 options:

1. Show all
2. Show MNI Data

If the toggle switch is deactivated, bar graph/stacked bar graph would show data for all.

![](media/bar-graph-all.png)
![](media/stacked-bar-graph-all.png)

If the toggle switch is activated, bar graph/stacked bar graph would show data related to MNI Only

![](media/bar-graph-mni.png)


## Line Graph

The widgets that shows data in Line graph has different options to view data.

Line graph has below widget controls:

1. Line Step
2. Days
3. Point Style

### Line Step

Line step is a dropdown which shows 4 options to select from

![](media/line-step-options.png)

The view of data in line graph changes depending on the Line step chosen. Below image shows data for line step selected as "before".

![](media/line-step.png)

### Days

Days is a dropdown which shows 4 options to select from

![](media/days-options.png)

The view of data in line graph changes depending on the days selected. If the days selected is 180 or 1 year then the line graph will show a lot of data compared to days selected as 30 or 90. Below image shows data for days selected as "180 days".

![](media/days.png)

### Point Style

Point style is also a dropdown which shows 4 options to select from

![](media/point-style-options.png)

The view of data in line graph changes depending on the point style chosen. Below image shows data when point style selected is "Triangle".

![](media/point-style.png)


## Org Admin Dashboard

### Project Map
![orgAdminDashboard](../../assets/screenshots/dashboard/orgAdminDashboard.png)


### Markers
The markers displayed on the map showcase the latitude and longitude of a particular project. 
On mouse over additional project details as well as a link ![dashboard icon](../../assets/screenshots/dashboard/dashboard-icon.png)
to the corresponding project dashboard can be found in the in popup window.

### DNA Summary
A data table provides a link to a project dashboard and shows high level DNA summary details for each project

![](media/dna-summary.png)

### Specimen Summary
A data table provides a link to a project dashboard and shows high level Skeletal Elements summary details for each project

![](media/specimen-summary.png)

### Isotope Summary
A data table provides a link to a project dashboard and shows high level Isotope summary details for each project

![](media/isotope-summary.png)

### Missing Person Summary
A data table provides a link to a project dashboard and shows high level Missing Person summary details for each project

![](media/missing-person-summary.png)


## Project Manager Dashboard
The Project Manager Dashboard serves as a high level view of both summary and aggregated project data. 
The dashboard is comprised of *widgets*, which are individual visual representations of data.  Examples of those widgets include:
  
  * Skeletal Elements Associated To Individual
  * DNA Sample Information
  * Mito sequence Information
  * Inventory Process
  
Those *widgets* can be added and removed via the *widget selector*.

![](media/project-manager-dashboard.gif)

The data in the dashboard is represented in 4 different formats:
 
  * Pie Chart
  * Bar Graph
  * Stacked Bar Graph
  * Line Graph

On Click of details from widgets project dashboard will be visible. It provides a detailed view of visualization and the data.

![](media/project-dashboard.gif)

### Pie Chart 

Data can be visualized in different ways by *widget selector* for pie chart. 

The data in the widgets will be seen as shown below

Clicking on the show donut option provides a dynamic semicircle view, offering a perspective on data representation.

Clicking on show pie provides a dynamic pie view, offering a perspective on data representation.

![](media/pie-chart.png)

On Click of details present on widgets, provides a detailed view of the visualization along with column details.

![](media/pie-chart-details.gif)

Below are the fields that are visible:

 * Key
 * Bone
 * Side
 * Bone Group
 * Individual Number
 * DNA Sample Number
 * Mito Sequence Number
 * Associations
 * Pathology
 * Methods
 * Measured
 * Complete
 * Isotope Sampled
 * Clavicle Triage
 * CT Scanned
 * Xray Scanned
 * Inventoried
 * Reviewed
 * Inventoried By

### Bar Graph

Bar Graph helps provide comparisons between discrete categories or groups.

![](media/bar-graph.png)

On Click of details present on widgets, provides a detailed view of the visualization along with column details.

![](media/bar-graph.gif)

Below are the fields that are visible:
 
* Mito Sequence Number
* Total

***These fields will vary depending on type of module selected***


### Stacked Bar graph

Stacked bar graph is divided into segments or "stacks" to represent different categories or subgroups within a single category.

![](media/stacked-bar-graph.png)

On Click of details present on widgets, provides a detailed view of the visualization along with column details.

![](media/stacked-bar-graph.gif)

Below are the fields that are visible:

* bone
* side
* Total

***These fields will vary depending on type of module selected***

### Line graph

Line graph helps visualize data trends over time or across different data categories.

![](media/line-graph.png)

Line graph widget contains the following:

* Line step
* Days
* Point Style

 
## User Dashboard
The User Dashboard serves as a high level view of both summary and aggregated user data. 
### User Activity

User activity contains *widgets*, which are individual visual representations of data.  Examples of those widgets include:

* Skeletal Elements Assocciated To Individual
* DNA Sample Information

Those *widgets* can be added and removed via the *widget selector*. User activity widgets are present in the Org admin dashboards

On Click of key from the user activity widget present on dashboard shows the specimen page with details to edit and other actions.

![](media/user-activity-specimen.gif)

On Click of details present on widgets, provides all the data for the selected module.

![](media/user-activity-details.gif)

Below are the fields that are visible:

* Key
* Name
* Side
* Completeness
* Individual Number
* Measured
* Isotope Sampled
* Clavicle Triage
* CT Scanned
* Xray Scanned 
* Inventoried
* Reviewed
* Inventoried At
* Reviewed At
* Created By
* Created At
* Updated By
* Updated At


***These fields will vary depending on type of module selected***








 
 
