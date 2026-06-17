# Core Visuals, DAX, SVG & HTML

This is a collection of Power BI Core Visuals, DAX, SVGs and HTML for use in [Power BI](https://powerbi.microsoft.com/en-us/). All the work is original and where this has been inspired by the work of others, I have pointed this out.

## Chips & Donuts (SVG & HTML)

A simple table that uses an SVG to show a donut as well as demonstrating the use of SVGs nested within HTML nested within SVGs for the display of the chips.

![](https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Chips%20%26%20Donuts/thumbnail.jpg)

## Chips (DAX UDF & SVG)

A UDF to easily create SVG Chips. Syntax is as simple as `Bacci.SVG.Chip("Text","Blue")`

![](<https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Chips%20(DAX%20UDF)/thumbnail.png>)

## Duration (DAX UDF)

A user-defined function that calculates the duration between two dates in the format `n years n months n days.`

Most existing algorithms I found rely on a simplified calendar (assuming 30 days per month and 365 days per year) and use basic `MOD()` and `QUOTIENT()` operations to determine the duration. This often produces inaccurate or unintuitive results.
In contrast, this UDF calculates durations using actual month and year boundaries, resulting in a more natural, human-readable output. The results are displayed side by side for easy comparison with the conventional method.

![](<https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Duration%20(DAX%20UDF)/thumbnail.png>)

## Info Icon (HTML)

A HTML info icon which when hovered over, displays all the key details and context that readers need to understand the numbers they’re seeing.

<p align="center">
<img src="https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Info%20Icon/thumbnail.jpg" width="500">
</p>

## Matrix Gradient (DAX)

Power BI conditional formatting for gradients is quite restrictive and limited to 3 colours. Using some simple DAX, we can easily interpolate between as many colours as required and have much more control over gradient boundaries.

![](https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Matrix%20Gradient/thumbnail.jpg)

## Report Hub (HTML)

HTML Content (Lite) visual used to create a report hub. Use Direct Query to query the last refresh times from each semantic model.

![](https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Report%20Hub/thumbnail.png)

## Slicers (DAX & SVG

Elevate the slicer user experience by showing how many records will be affected with each selection. Useful when using _Sync Slicers_ functionality.

![](https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Slicers/thumbnail.png)

## Tornado Chart (SVG)

SVG bars created using a User Defined Function. The bars can be left or right aligned and are used here to create a 2025 World Population Pyramid. Regular Power BI data bars cannot be used in this scenario as bar lengths cannot be uniformly scaled across multiple columns and would result in a misleading visualisation.

Source data: [https://www.census.gov/](https://www.census.gov/data-tools/demo/idb/#/pop?dashboard_page=country&COUNTRY_YR_ANIM=2025&CCODE=**&popPages=BYAGE&menu=popViz)

![](https://github.com/PBI-David/PBI-Core-Visuals-SVG-HTML/blob/main/Tornado%20Chart/thumbnail.png)
