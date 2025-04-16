---
name: Srikar Manikonda vega homework 5
tools: [Python, HTML, vega-lite]
description: This is Srikar Manikonda's homework using vega/altair!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Charts and reference data/analysis

Plot 1: This interactive scatter plot visualizes each license’s duration over time by mapping the original issue date on the x‑axis against the calculated duration (in days) on the y‑axis. Each point represents an individual license, colored by its type, which allows for easy differentiation among license categories. This plot is  relevant to the dataset as it offers insights into how long licenses are valid across various periods and may reveal underlying patterns related to regulatory practices or changes in licensing policies over time.

<vegachart schema-url="{{ site.baseurl }}/assets/json/saved_license_plot.json" style="width: 100%"></vegachart>



Plot 2: This bar chart aggregates and displays the frequency of licenses for each category, with the x‑axis showing the license types and the y‑axis indicating the count of licenses within each category. By summarizing the distribution of license types, the chart shows which categories are most prevalent, highlighting potential areas where licensing is concentrated or more actively enforced. The visual simplicity makes it  effective and clearly show the display of each license category.



<vegachart schema-url="{{ site.baseurl }}/assets/json/saved_license_plot_2.json" style="width: 100%"></vegachart>









<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/srikarmanikonda/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>