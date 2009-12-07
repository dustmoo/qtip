This is a fork of Craig Thomson's jQuery plugin qTip. Original version available at:

http://craigsworks.com/projects/qtip/

Craig is also working on a new version featuring jQuery UI styling integration and other enhancements. This is NOT that version, but a fork of the
original qtip 1.0.0-rc3

Here are the changes I have made:

12-7-2009

* Integrated Craig's image preload function into this version of the script. Note: Script now requires the jquery.preload.js plugin.
* Added minified version of the script which includes the preload plugin.

12-4-2009

* Added Craig's opacity fix for to the afterShow function to prevent the tip opacity being set wrong when tip drawing is interrupted.
* Raised the base z-index to a higher number to prevent z-index conflicts.
* Added functionality so that unfocus can be used with other hide actions, i.e.

		hide: {when: {event:'mouseout unfocus'}, fixed: true, delay: 500 }

