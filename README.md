AJAX Chat Styles
================

This repository is a simple collection of styles created and/or modified by the AJAX Chat community. 

The layout of AJAX Chat (https://github.com/Frug/AJAX-Chat) developed by Frug (https://github.com/Frug) is fully customizable by using CSS (Cascading Style Sheets).

Included Styles
---------------

| *Minimal* | *Lost In Space* | *example* |
| --------- | --------------- | --------- |
| ![Minimal Preview](https://github.com/gWorldz/AJAX-Chat-Styles/raw/master/Minimal/preview.jpg) | ![example Preview](https://github.com/gWorldz/AJAX-Chat-Styles/raw/master/example/preview.jpg) | ![Lost In Space Preview](https://github.com/gWorldz/AJAX-Chat-Styles/raw/master/Lost-In-Space/preview.jpg) |

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

- Add a new CSS file (e.g. mystyle.css) by copying one of the existing styles from the AJAX Chat CSS directory or other AJAX Chat Styles.
- Edit your file (css/mystyle.css) and adjust the CSS settings to your liking.
- Add the name of your style without file extension to the available styles in lib/config.php:

<pre>// Available styles:
$config['styleAvailable'] = array('mystyle','beige','black','grey');
// Default style:
$config['styleDefault'] = 'mystyle';</pre>

The example style is a blank canvas with some commonly used CSS and is a great start for custom styles.

Contributing Styles
-------------------

If you are interested in contributing your style to this [AJAX Chat Styles](https://github.com/gWorldz/AJAX-Chat-Styles) repository:

1. Fork the repository.
2. Add your style - make sure you maintain the example style structure.
3. Commit changes.
4. Push your commit.
5. Create a Pull Request.

Example Style Structure
-----------------------

| FILES          | REQ. | DESCRIPTION |
| -------------- | ---- | ----------- |
| example.css    | Yes  | This is where we import required AJAX Chat styles and add our custom CSS styles. |
| example.jpg    | No   | This 800x640 screenshot uses the name of our style and serves as a large preview. |
| license.txt    | No   | The license for the style, if omitted the Modified MIT license included with [AJAX Chat Styles](https://github.com/gWorldz/AJAX-Chat-Styles) will be used. |
| preview.jpg    | No   | This 200x160 preview is used for the [AJAX Chat Styles](https://github.com/gWorldz/AJAX-Chat-Styles) README.md |
| example_images | No   | This folder uses the name of our style followed by "_images" and is for images/files required by the theme |

Changelog
---------

0.0.1 Initialising
- Added MInimal by [Bomdia](https://github.com/bomdia)

0.0.2
- Added example by [gWorldz](https://github.com/gWorldz)
- Added Lost In Space by [gWorldz](https://github.com/gWorldz)
