# IMAGES

Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.

GIF images support transparency by declaring a single colour in the colour palette as transparent (index transparency). Because of absence of partial transparency, the edges (specially rounded or too-detailed edges) get a poor jagged effect. Though this can be solved to some extent using dithering, with improved PNG support, GIF is unsuitable for images with transparent backgrounds.

PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). Partial transparency makes the edges blend smoothly into the background. PNG8 images (discussed in the “Colours” section below) can support only index transparency whereas PNG24 images can support alpha channel transparency.
// pulled from <https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d>

## CSS COLOR AND TEXT

The color property specifies the color of text.

color Specifies the text color. Look at CSS Color Values for a complete list of possible color values. initial Sets this property to its default value.
inherit Inherits this property from its parent element

The color property is used to set the color of the text. The color is specified by: name, rgb, or hex. The default text color for a page is defined in the body selector.

Important: High contrast is very important for people with vision problems. So, always ensure that the contrast between the text color and the background color (or background image) is good!

  Courtesy of <https://www.w3schools.com/csS/css_text.asp>
