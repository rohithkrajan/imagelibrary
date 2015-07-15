
---


# IMPORTANT! #
**WE'VE MOVED OVER TO [GITHUB](https://github.com/fschultz/NetImageLibrary) WHERE YOU WILL FIND THE LATEST VERSION. THIS REPOSITORY WILL REMAIN BUT ALL NEW DEVELOPMENT WILL BE DONE OVER AT [GITHUB](https://github.com/fschultz/NetImageLibrary).**


---


You'll find information on how to get started at http://kaliko.com/image-library/get-started/ and full API documentation at http://kaliko.com/image-library/api/

[Download latest version, 2.0.0](https://docs.google.com/uc?export=download&id=0ByDd6qehepdVNXFJZm9MYW13dDQ)

.NET library for easy image handling like:
  * Filters
  * Cropping
  * Thumbnail creation
  * Saving as JPG/GIF/PNG files or streams
  * Opening images from streams or URLs

Using only safe code making this library possible to use on web hosts with medium trust.

Current build contains the following filters:
  * Gaussian blur filter
  * Unsharpen mask filter
  * Chroma key filter
  * Contrast filter
  * Brightness filter
  * Invert filter
  * Desaturnation filter

If you plan using this library with WPF or simular, read this post on [how to convert an KalikoImage object to System.Windows.Media.Imaging.BitmapImage and System.Windows.Controls.Image](http://labs.kaliko.com/2011/03/convert-to-bitmapimage.html).

## History ##
2.0.0
  * Replaced Gaussian blur filter with better implementation (affects unsharpen masks)
  * Added chroma key filter
  * Rewritten API for Scaling
  * Added color space handling

1.2.4
  * Updated to Visual Studio 2010.
  * Code clean-up.<br>
<ul><li>Unwanted-border-artifact-problem fixed (thanks Richard!)<br>
</li><li>IDisponable has been implemented.<br></li></ul>

1.2.3<br>
<ul><li>Minor changes.<br>
</li><li>First API documentation uploaded. Still missing a whole lot, but it's a start :)</li></ul>

1.2.2<br>
<ul><li>Minor changes</li></ul>

1.2.1<br>
<ul><li>Bug in thumbnail function fixed.<br>
</li><li>Code cleaned up.