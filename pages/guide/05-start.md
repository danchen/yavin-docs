---
layout: guide
group: guide
title: User Guide
---

* TOC
{:toc}

Supported Visualizations
------------------------------------------------
Yavin provides much more than static charts. Yavin provides a wide array of interactive visualizations that help you explore your data.

<figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_viz_sample.png" width="800"/><figcaption>Figure - A sample of visualizations supported by Yavin </figcaption> </figure>

When you change the dimensions for a report, Yavin displays the available visualizations for the combination of selected dimensions. You can select the visualization you prefer by clicking among the different visualization icons  ![](assets/images/UG_all_viz.png), which are located at the top of the report.

<figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_general_viz.gif" width="800"/><figcaption>Gif animation - Yavin reports are interactive visualizations  </figcaption> </figure>

###  Measure label
 This is an overview visualization that’s shown when there are no dimensions selected for the report. It presents a numeric summary of the currently selected measures, applying any selected filter criteria.

<figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_metric_sample.png" width="800"/><figcaption>Figure - Sample Yavin measure label visualization </figcaption> </figure>

 The measure label can be edited to change any of these items: Label, Format Type and Format

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_metric_viz.png" width="800"/><figcaption>Figure - Editing Yavin measure label  </figcaption> </figure>

###  Gauge Chart
The Gauge visualization is a chart that displays the major contributors or key influencers for a selected result or value. The Gauge chart displays progress toward a measurable goal.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_gauge_viz.png" width="800"/><figcaption>Figure - Sample Yavin gauge chart visualization </figcaption> </figure>

 The gauge chart can be edited to change any of these: label, baseline and goals

  <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_gauge_viz2.png" width="250"/><img style="border:2px solid black;" src="/assets/images/UG_gauge_viz3.png" width="250"/><img style="border:2px solid black;" src="/assets/images/UG_gauge_viz4.png" width="250"/><figcaption> Figure - Editing Yavin gauge chart visualization and changing the baseline </figcaption> </figure>

###  Table
 **The table visualization is the default view when a dimension is selected**. It presents a tabular view of the data with column ordering and sorting functions.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_table_viz.png" width="800"/><figcaption>Figure - Sample Yavin table visualization </figcaption> </figure>

The table visualization can show multiple dimensions measures and dimensions together:

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_table_viz3.png" width="800"/><figcaption>Figure - Multiple measures in a table visualization </figcaption> </figure>

 The table properties can be edited, including changing the column name, the format type, the format, the layout and the sort order of the columns.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_customize_table.png" width="800"/><figcaption>Figure - Editing Yavin table visualization </figcaption> </figure>

 “**Grand Total**” and “**Subtotals**” of measures by dimension, can be added to the table calculation if desired. The option to add them can be done from the (<img src="/assets/images/UG_edit_table.png" width="100"/>) option.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_add_total.png" width="800"/><figcaption>Figure - Table Visualization with no “Grand Total” and “Subtotal” applied  </figcaption> </figure>

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_add_total2.png" width="800"/><figcaption>Figure - Table Visualization with “Grand Total” and “Subtotal” applied </figcaption> </figure>

###  Line chart
 The line chart can visualize temporal (trend over time) dimensions. <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_line_chart_sample2.png" width="800"/><figcaption>Figure - Line charts are interactive visualizations </figcaption> </figure>

The chart lets you visualize multiple trends together in a single graph. Note the different colored lines in the chart below. They each chart an individual dimension.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_time_series.png" width="800"/><figcaption>Figure - Line charts are interactive visualizations </figcaption> </figure>

The line chart line style can be changed to an area spline. The stacked area chart is similar to the regular line chart, and can be used in similar situations.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_change_line_chart.png" width="800"/><figcaption>Figure - Converting a Yavin line chart to a spline chart </figcaption> </figure>

Or an area step

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_line_chang.png" width="800"/><figcaption>Figure - Converting a Yavin line char to a step chart </figcaption> </figure>

###  Bar chart
 The bar chart can visualize histograms - showing the frequency distribution of occurrences over numeric buckets.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_bar_chart1.png" width="800"/><figcaption>Figure X - Sample Yavin bar chart visualization </figcaption> </figure>

 The bar chart can be edited, allowing you to change the measures and having them stacked:

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_bar_viz.png" width="800"/><figcaption>Figure - Editing a Yavin bar chart visualization </figcaption> </figure>

###  Pie chart
 The pie chart is a visualization that represents the ratios between the values of a dimension.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_pie_viz2.png" width="800"/><figcaption>Figure - Sample Yavin pie chart visualization </figcaption> </figure>

 The pie chart can be edited, allowing you to change the measures:

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_piechart_change.png" width="800"/><figcaption>Figure -Yavin pie chart are interactive visualizations </figcaption> </figure>

When there are multiple dimensions being rendered, the label below the chart shows the dimensions that correspond to each slide of the pie.  Clicking on a slice will highlight the selected label in relation to the other slices.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_pie_highlight.png" width="800"/><figcaption>Figure - Yavin pie chart proportional representation with multiple representations </figcaption> </figure>

###  When can you select each of the visualizations?

|  Visualization                     |  When is it available for selection?  |
|------------------------------------|---------------------------------------|
|  <img src="/assets/images/UG_table_icon2.png" width="100"/> |  When no dimension is added.           |
|  <img src="/assets/images/UG_gauge_icon.png" width="100"/> |  When no dimension is added.          |
|  <img src="/assets/images/UG_table_icon.png" width="100"/> |  Table visualization is available in all cases. It is the default visualization.   |
|  <img src="/assets/images/UG_line_icon.png" width="100"/> |  When at least one time dimension is added.           |
|  <img src="/assets/images/UG_bar_icon.png" width="100"/> |  When at least one dimension is added.      |
|  <img src="/assets/images/UG_pie_icon.png" width="100"/> |  When there is no time dimension added.       |
{:.table}

 Time Series
-----------------------------------
 It is often useful to compare the values for different dimensions over time (time series data).  A time series is a sequence of numerical data points in chronological order.  To visualize time series data, specify a time interval - an inclusive start and exclusive end time/date. In the example below, total clicks is compared acorss gender over a period of 90 days.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_time_series2.png" width="800"/><figcaption>Figure - Time series chart in Yavin </figcaption> </figure>

 The time series can be filtered further to focus on one or more specific dimensions. For example, the time series chart below narrows the focus to only “Male” and “Female” gender, hiding “Unknown” and “All Other”.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_line_chart_sample.png" width="800"/><figcaption> Figure - Yavin time series chart filtered Filters </figcaption> </figure>

 Filters limit the data returned in a report. A filter could limit a period or time, a certain country or a number of countries, or any other dimension value in your data.  Filters are created in the filter bar.  Users can filter by either dimensions, measures, or both at the same time. It is often useful to filter out outlying data and edge cases.

 To add a dimension or measure to a filter criteria, select the filter icon (  ![](assets/images/UG_filter_icon.png)  ) next to the measure or dimension.

<img src="/assets/images/UG_add_filter_tooltip.png" width="300"/>

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_add_dim.gif" width="800"/><figcaption> Gif animation - Filter flow in Yavin </figcaption> </figure>

To remove a dimension or measure from the filter, click the filter icon for the corresponding Dimension or Measure. Or select the (x) ![](assets/images/UG_filters_how.png) icon on the filter section.

<img src="/assets/images/UG_remove_filter.png" width="300"/>

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img src="/assets/images/UG_remove_filters.gif" width="800"/><figcaption> Gif animation - Removing a filter from the filter box </figcaption> </figure>

###  Editing filters
Users can edit filters in the filter section of the report. Some dimension filters support “Type Ahead” search.  Type ahead search is a feature of the search bar where user search terms are matched to suggestions as the user types.  Type ahead search is only supported for dimensions with text values and must be [specifically enabled in the semantic layer](/pages/guide/03-start.html#type-ahead-search).  

The example below demonstrates editing different types of dimension filters:

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_filter_change.gif" width="800"/><figcaption>Gif animation - Exploring the filter operations </figcaption> </figure>

###  Supported filter operation for Dimensions (String filters)

|  Operation    | Availability   |
|---------------|----------------|
|  Equals       |  Now           |
|  Not equals   |  Now           |
|  Is Empty     |  Now           |
|  Is not empty |  Now           |
|  Contains     |  Now           |
{:.table}

###  Supported filter operation for Measures (Number or range filters)

|  Operation                     |  Availability  |
|--------------------------------|----------------|
|  &gt;                          |  Now           |
|  &lt;                          |  Now           |
|  =                             |  Now           |
|  !=                            |  Now           |
|  &lt; = &gt; (in between)      |  Q1 2020       |
|  !&lt; = &gt; (not in between) |  Q1 2020       |
|  &gt;=                         |  Now           |
|  &lt;=                         |  Now           |
{:.table}

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_filters.gif" width="800"/><figcaption>Gif animation - Filter operation for measures </figcaption> </figure>

###  Supported filter operation for Dates (Time filters)
Time and date dimensions support their own filter operations.  Some operations are relative to the user's wallclock time.  The supported filter operations for time filters are:

|  Operation                                                                                       |  Availability  |
|--------------------------------------------------------------------------------------------------|----------------|
|  Current                                                                                         |  Now           |
|  In the past                                                                                     |  Now           |
|  Since                                                                                           |  Now           |
|  Between                                                                                         |  Now           |
|  Advanced ( Advanced time ranges allows for between dates and selecting  a specific time range)  |  Q1 2020       |
{:.table}

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_line_filter_change.gif" width="800"/><figcaption>Gif animation - Filter operation for dates </figcaption> </figure>

###  Dashboard filter
You can add a filter to a dashboard by clicking on the <img src="/assets/images/UG_settings_icon.png" width="100"/> icon, followed by <img src="/assets/images/UG_add_filter.png" width="100"/> to select the dimension, the operation and the value.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_dashboard_filter.gif" width="800"/><figcaption> Gif animation -  Dashboard filters </figcaption> </figure>

 Operations on Reports
---------------------------------------------
### Change column name
 As dimensions ![](assets/images/GS_dim_symbol.png) and measures ![](assets/images/GS_metric_symbol.png) get added to the report, their column names can be updated in the column tab section ![](assets/images/GS_column_expand.png). The column tab section can be retracted and expanded.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/GS_report_change_column_name.gif" width="800"/><figcaption> Gif animation -  Changing column name of a report </figcaption> </figure>

###  Add to Favorites
Add your Report to the favorite bucket.

###  Add To Dashboard
Adds the Report to a new or existing Dashboard.

###  Clone
Creates an exact copy of a Report with the name “Copy of ….”.

###  Copy API Query
Allows you to copy the API query of your Report, or run it in a new Tab.

 <figure style="font-size:0.6vw; color:DodgerBlue;"> <img style="border:2px solid black;" src="/assets/images/UG_api.png" width="300"/>
 <figcaption>Figure - Copy API query dialog </figcaption></figure>

### Export <img src="/assets/images/UG_coming_soon.png" width="100"/>
Allows you export your Report as CSV, PDF or PNG.
<img src="/assets/images/UG_export_report.png" width="150"/>

###  Share
Allows you to share the link of your Report.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_share.png" width="400"/><figcaption>Figure - Share dialog </figcaption> </figure>

### Schedule <img src="/assets/images/UG_coming_soon.png" width="100"/>
Allows you to schedule your Report by specifying the rules of scheduling including format (CSV, PDF or PNG), the email recipients and the frequency:

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_schedule_report.png" width="400"/><figcaption> Figure - Report schedule dialog </figcaption> </figure>

### Delete
 Allows you to delete your Report.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_delete_widget.png" width="400"/><figcaption> Figure - Delete dialog </figcaption> </figure>

 Operations on Dashboards
------------------------------------------------
###  Add to Favorites
Allows you to add your dashboard to the favorite bucket.

###  + Add Widget
Allows you to add a widget to the dashboard.

###  Clone
Creates an exact copy of a dashboard with the name “Copy of ….”.

### Export <img src="/assets/images/UG_coming_soon.png" width="100"/>
Allows you export your Dashboard as PDF or PNG.
<img src="/assets/images/UG_export.png" width="150"/>

###  Share
Allows you to share the link for your Dashboard.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_share_dashboard.png" width="400"/><figcaption> Figure - Dashboard share dialog </figcaption> </figure>

### Schedule <img src="/assets/images/UG_coming_soon.png" width="100"/>
Allows you to schedule your Dashboard by specifying the rules of scheduling including format (PDF or PNG), the email recipients and the frequency:

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_schedule_dashboard.png" width="400"/><figcaption> Figure - Dashboard schedule dialog </figcaption> </figure>

### Delete
Allows you to delete your Dashboard.

 <figure style="font-size:0.6vw; color:DodgerBlue;"><img style="border:2px solid black;" src="/assets/images/UG_delete_widget.png" width="400"/><figcaption>Figure - Dashboard delete dialog </figcaption> </figure>
