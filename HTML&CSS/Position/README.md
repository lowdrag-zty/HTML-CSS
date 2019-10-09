float, clear
positions: static, relative, absolute, fixed
media-queries
z-index
::before and ::after pseudo elements

1. float
   float:left --> the image could float left to the passage. Originally, they should be up and down, for passage is a block element.

2. clear
   clear:left/right/both --> used to avoid a block element being covered by another float-manipulated element.

3. position

   position:static --> default setting...
   position:relative --> followed by left/right/top/bottom & pixels, shifting the box accordingly relative to the original position.

   position: absolute --> first, the box tries to find its NEAREST parent. If successful, shift relative to that. If not, shift relative to the webpage.

   position fixed --> Very commonly used for the navigation bar in a fixed position, so that when you scroll down the web page, it is still there, possibly click it and accordingly bring you to the top.
