#### **padding** : {<%= type %>}

<% if(defaultValue !== "[object Object]") { %>*default: <%= defaultValue %>* <% }%>

The whitespace, in pixels, between the outer edge of any visualizations in this Contour instance (for example, the labels or axis titles) and the inner plot area (for example, the axes).

The `padding` configuration property needs to include at least one of [`top`](#config_config.chart.padding.top), [`bottom`](#config_config.chart.padding.bottom), [`right`](#config_config.chart.padding.right), and [`left`](#config_config.chart.padding.left).

It is an error if the `padding` is greater than the total space available for the chart. 

**Notes:**

This `padding` is distinct from the [`margin`](#config_config.chart.margin). The [`margin`](#config_config.chart.margin) is the whitespace, in pixels, between the container of this Contour instance and the outer edge of any visualizations in this Contour instance (for example, the labels or axis titles). (The container, in turn, has its dimensions determined by [`defaultWidth`](#config_config.chart.defaultWidth), [`width`](#config_config.chart.width), [`defaultAspect`](#config_config.chart.defaultAspect), and [`height`](#config_config.chart.height).)

<% if(notes) { %><%= notes %><% } %>

