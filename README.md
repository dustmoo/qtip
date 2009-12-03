This is a fork of Craig Thomson's jQuery plugin qTip. Original version available at:

http://craigsworks.com/projects/qtip/

Craig is also working on a new version featuring jQuery UI styling integration and other enhancements. This is NOT that version, but a fork of the
original qtip 1.0.0-rc3

Here are the changes I have made:

* Added Craigs opacity fix for to the afterShow function to prevent the tip opacity being set wrong when tip drawing is interrupted.
* Raised the base z-index to a higher number to prevent z-index conflicts
* Added functionality so that unfocus can be used with other hide actions, i.e.

	hide: {when: {event:'mouseout unfocus'}, fixed: true, delay: 500 }

