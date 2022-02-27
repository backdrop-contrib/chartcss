# ChartCSS

Simple module to add the Charts.css framework for data visualisation to
inline content and turn data into beautiful charts and graphs using
simple CSS classes.

### ***Please note that this CSS framework can not do calculations so will not format charts generated from Views.***

You will need to add the calculation to the ***<td style=... >*** tag in order to
tell the framework how to display the data. To minimize logarithmic errors,
the best practice is to calculation using CSS calc() function.

For example...
```<tbody>
  .  <tr>
  .    <td style="--size: calc( 40 / 100 )"> $40K </td>
  .  </tr>
  .  <tr>
  .    <td style="--size: calc( 60 / 100 )"> $60K </td>
  .  </tr>
  ```

### See the menu ***/admin/config/content/chartcss/help*** for links to the Framework and an example.

This module uses the chartsCSS framework on github https://github.com/ChartsCSS/charts.css

## Requirements:
No dependencies.

## Installation:
Install this module using the official Backdrop CMS instructions at https://docs.backdropcms.org/documentation/extend-with-modules

Visit the configuration page under Administration > ChartCSS (/admin/chartcss).

## Documentation:
Additional documentation is located in the Wiki: https://github.com/backdrop-contrib/chartcss/wiki

## Issues:
Bugs and Feature requests should be reported in the Issue Queue: https://github.com/backdrop-contrib/chartcss/issues

## Current Maintainer(s):
- [Steve Moorhouse (albanycomputers)] (https://github.com/albanycomputers)
- Seeking additional maintainers.

## Credits:
- Backdrop CMS Module created by Stephen Moorhouse.

- Chart.CSS creator Rammiy (https://github.com/ramiy)
- Chart.CSS Github respoitory (https://github.com/ChartsCSS/charts.css)

## Sponsorship:
 - [Albany Computer Services] (https://www.albany-computers.co.uk)

License
This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
