### **Awesome Image Resources** ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)


A collection of awesome things regarding image optimisations and utility

- Articles
	- [Essential Image Optimization](https://images.guide/)
	- [Image optimization](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
	- [Responsive Images](https://developers.google.com/web/ilt/pwa/responsive-images-slides)
	- [Automating Image Optimization](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/automating-image-optimization/)
	- [Replace animated GIFs with Video](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/replace-animated-gifs-with-video/)
	- [Lazy loading Images and Video](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
	- [Clowncar technique](http://coding.smashingmagazine.com/2013/06/02/clown-car-technique-solving-for-adaptive-images-in-responsive-web-design/)
	- [Generate multi-resolution images for srcset with Grunt](https://addyosmani.com/blog/generate-multi-resolution-images-for-srcset-with-grunt/)

- Libraries
	- Gallery
		- [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) JavaScript image gallery for mobile and desktop, modular, framework independent
	- Lazy Loading
		- [LazySizes](https://github.com/aFarkas/lazysizes) High performance and SEO friendly lazy loader for images (responsive and normal), iframes and more, that detects any visibility changes triggered through user interaction, CSS or JavaScript without configuration
		- [Lozad.js](https://github.com/ApoorvSaxena/lozad.js) Highly performant, light and configurable lazy loader in pure JS with no dependencies for responsive images, iframes and more
	- Resizing or Cropping
		- [Sharp](https://github.com/lovell/sharp) High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images. Uses the libvips library
		- [SmartCrop.js](https://github.com/jwagner/smartcrop.js) Content aware image cropping	
	- Utility
		- [Color Thief](https://github.com/lokesh/color-thief) Grabs the dominant color or a representative color palette from an image. Uses javascript and canvas
		- [Jimp](https://github.com/oliver-moran/jimp) An image processing library written entirely in JavaScript for Node, with zero external or native dependencies
		- [DropZone](https://github.com/enyo/dropzone) Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
		- [Intense Images](https://github.com/tholman/intense-images) A simple library to view large images up close using simple mouse interaction, and the full screen
		
- Automation Tasks
	- Grunt
		- Compression
			- [OptiPNG/jpegtran/gifsicle](https://github.com/gruntjs/grunt-contrib-imagemin)
			- [grunt-svgmin](https://github.com/sindresorhus/grunt-svgmin)
			- [ImageOptim-CLI companion](https://github.com/JamieMason/grunt-imageoptim)
			- [Convert to WebP](https://github.com/somerandomdude/grunt-webp)
		- Spriting
			- [grunt-spritefiles](https://npmjs.org/package/grunt-spritefiles)
			- [grunt-montage](https://github.com/globaldev/grunt-montage)
		- Prescaling (normalization) to avoid excessive image resize/decode work:
			- [grunt-imageNormalize](https://github.com/dancingplatypus/grunt-imageNormalize)
			- [grunt-image-resize](https://npmjs.org/package/grunt-image-resize)
		- Responsive image generation/handling:
			- [Generate multi-resolution images](https://github.com/andismith/grunt-responsive-images)
			- [grunt-clowncar](https://npmjs.org/package/grunt-clowncar)
		- Inline images as data URIs:
			- [grunt-image-embed](https://github.com/ehynds/grunt-image-embed)

- Individual tools
	- PNG:
		- [pngcrush](http://pmt.sourceforge.net/pngcrush/)
		- [optipng](http://optipng.sourceforge.net/)
		- [advpng](http://advancemame.sourceforge.net/comp-download.html)
		- For Windows, see [pngout](http://advsys.net/ken/utils.htm) and [pngwolf](http://bjoern.hoehrmann.de/pngwolf)
		- [zopfli-png](https://github.com/subzey/zopfli-png) and [Pngnq S9](http://sourceforge.net/projects/pngnqs9/) by Kornel
	- PNG Quantizer
		- [pngquant](http://pngquant.org/)
		- [pngnq](http://pngnq.sourceforge.net/)
	- JPG:
		- [jpegmini](http://www.jpegmini.com/)
		- [jpegcrush](http://akuvian.org/src/jpgcrush.tar.gz)
		- [jpegoptim](https://github.com/glennr/jpegoptim)
		- [jpgtran](http://jpegclub.org/jpegtran/)
	- GIF:
		- [gifsicle](http://www.lcdf.org/gifsicle/)
	- SVG
		- [SVGO](https://github.com/svg/svgo)
		- [SVGCleaner](https://github.com/RazrFalcon/SVGCleaner)