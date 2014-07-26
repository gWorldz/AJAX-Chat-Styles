AJAX Chat Styles
================

This repository is a simple collection of styles created and/or modified by the AJAX Chat community. 

The layout of AJAX Chat (https://github.com/Frug/AJAX-Chat) developed by Frug (https://github.com/Frug) is fully customizable by using CSS (Cascading Style Sheets).

Included Styles
---------------

| *Minimal*              | *Lost In Space*                | 
| ---------------------- | ---------------------------- |
| ![Minimal Preview](https://github.com/gWorldz/AJAX-Chat-Styles/raw/master/Minimal/preview.jpg) | ![Lost In Space Preview](https://github.com/gWorldz/AJAX-Chat-Styles/raw/master/Lost-In-Space/preview.jpg)


Installing Styles
-----------------

To install one of these styles in AJAX Chat, do the following:

- Download the style folder from GitHub
- Upload the folders contents to your css/ directory
- Add the name of the style without file extension to the available styles in lib/config.php:

<pre>// Available styles:
$config['styleAvailable'] = array('mystyle','beige','black','grey');
// Default style:
$config['styleDefault'] = 'mystyle';</pre>

Designing Styles
----------------

To add your own style, do the following:

- Add a new CSS file (e.g. mystyle.css) by copying one of the existing styles from the CSS directory.
- Edit your file (css/mystyle.css) and adjust the CSS settings to your liking.
- Add the name of your style without file extension to the available styles in lib/config.php:

<pre>// Available styles:
$config['styleAvailable'] = array('mystyle','beige','black','grey');
// Default style:
$config['styleDefault'] = 'mystyle';</pre>

Changelog
---------

Initialising
0.0.1
- Added MInimal by [Bomdia](https://github.com/bomdia)

0.0.2
- Added Lost In Space by [gWorldz](https://github.com/gWorldz)
