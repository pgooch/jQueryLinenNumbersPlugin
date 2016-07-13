jQueryLineNumbersPlugin
=======================

This jQuery plugin will take any normal text area and give it line numbers. See the example for more infromation

Usage
-----
Simple call the linenumbers function an a text area element like so:
    $('textarea').linenumbers();
Options can be passed via a object.

Plugin Options
--------------
1. col_width (Default: 25px) The width of the numbers column. Default should fit 4 columns on a textarea with no styles applied. This will need to be changed to fix the number of columns you choose and the styles applied to the textarea.
2. start (Default: 1) The starting line number
3. digits (Default: 4) The number of digits the line numbers should max out at, this is used for lead space calculating and does _not_ include the colon.

License
-------
This plugin has been realsed under the GNU General Public License v3.0.

Version History
---------------
+ 1.0.0 • May 27th 2012 - _Initial release._