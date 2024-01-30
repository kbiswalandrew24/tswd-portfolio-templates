| [home page](https://kbiswalandrew24.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title

HEY THERE!!! Let me show you the Govt debt for different countries in different year in different ways.

[Link for the viewing 2019-2022 govt debt](https://data.oecd.org/chart/7km9)

# preview of Govt debt in web tool-OECD data (using iframe)
<iframe src="https://data.oecd.org/chart/7km9" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7km9" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, last 5 years</a></iframe>


## Description -Part1
The dataset presents general government debt data for various countries spanning the years 2019 to 2021. Notably, in the highlights column, I have specifically selected the OECD average, OECD-Total, and USA data points, which are visually distinguished through different colors. This deliberate highlighting aids in making the columns stand out which helps in better visualization for our audience, allowing for easier identification and comparison of these key entities against others in the same color scheme within the dataset.

Moreover, the interactive feature of the visualization further enriches the audience's engagement. When hovering over each bar representing a country's data, additional information is dynamically displayed, including the corresponding year and the percentage of GDP attributed to government debt for that specific country. This interactive feature adds depth to the visualization, enabling a more comprehensive understanding of the data and facilitating nuanced analysis for our audience.


[Link for Tableau public view](https://public.tableau.com/views/Govt_debt_viz/Sheet1?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)

## Tableau view for Govt Debt..

<div class='tableauPlaceholder' id='viz1706570050782' style='position: relative'><noscript><a href='#'><img alt='Govt.Debt_visualisation ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Govt_debt_viz&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Govt_debt_viz&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Govt_debt_viz&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' />
</object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1706570050782');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


## Description- Part 2
The data table utilizes a color gradient scheme, ranging from light orange for lower debt values as low as 6.7 to transitioning into blue for higher debt values up to a maximum of 257. This color coding aids in quickly identifying different ranges of debt within the table. The gradient makes it visually clear which cells represent debts in the middle range, as well as distinguishing cells with lower or higher debt levels. This color scheme is not only visually appealing but also serves a functional purpose, making it easier for the audience to discern and interpret the data.

Furthermore, the exact debt values are displayed within each cell, providing precise numerical information alongside the color gradient. This combination of visual representation and numerical data enhances the audience's understanding and allows for quick comparisons between different countries and years. Overall, this approach simplifies data interpretation and enables the audience to easily identify which countries have the highest or lowest debt levels in each year, thus making the information more convincing and accessible.
### First Graph vs 2nd Graph
In contrast to the first graph, which relies on hover-over functionality for detailed information, the heatmap provides a comprehensive overview of each country's debt values for every year without the need for interaction. Each cell in the heatmap corresponds to a specific country and year, with color intensity indicating the debt value. This approach allows for immediate identification of high or low debt values without the need for additional actions. Specifically, countries with higher debt values are highlighted with more intense colors, making them stand out visually. This feature enhances the accessibility and usability of the graph, enabling users to quickly grasp debt trends across countries and years at a glance.

## Part 3-Another way in Tableau to view the Govt Debt
<div class='tableauPlaceholder' id='viz1706578656989' style='position: relative'><noscript><a href='#'><img alt='Govt.Debt_visualisation ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Govt_debt_viz_v2&#47;Sheet12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Govt_debt_viz_v2&#47;Sheet12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;Govt_debt_viz_v2&#47;Sheet12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' />
</object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1706578656989');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

# Description -Part 3
What stands out to me about this graph is its effective representation of data. With a quick glance, one can easily discern the highest debt value, along with the corresponding country and year. The aggregation of countries for each year simplifies the complexity of the data, providing a clearer overview. The use of blue indicates years with lower debt levels, while the standout red color highlights countries that exceed the debt range. Additionally, the inclusion of country names on the bars serves as reference points, enhancing clarity. Overall, the strategic use of color and added elements like country names makes the graph more convincing and accessible to the audience, aiding in better comprehension and analysis of the data.

### Why choose this format in Part 3
When comparing the 2nd and 3rd graphs, distinct differences emerge. The 2nd graph offers a granular view, providing extensive details for each country and year. In contrast, the 3rd graph presents data in a more condensed, pivot-like format, focusing solely on identifying countries and years with debt in higher or highest ranges. The simplicity of this presentation is accentuated by the strategic use of color: blue denotes the lowest range, red signifies the highest, and transitional colors indicate intermediate values. Given the scale of the dataset, I find this approach preferable as it streamlines information, eliminating extraneous details while highlighting key data points. Notably, the inclusion of country names on bars with high debt levels further enhances the graph's clarity and impact, making it a superior choice compared to alternative representations.
