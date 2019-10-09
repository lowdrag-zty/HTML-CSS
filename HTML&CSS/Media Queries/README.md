Media Queries
Z-index
Responsive Design
Style Elements on different screen sizes
min-width --> starts from
max-width --> up to
Mobile First

1. Media Queries are a feature of CSS that enable webpage content to adapt to different screen sizes and resolutions. They are a fundamental part of responsive web design and are used to customize the appearance of websites for multiple devices.

   @media screen and (min-width: px);
   For this, when we use min-width, we allow changes from small page size to large ones.
   Note that we could actually use multiple @media for different devices' sizes.

   @media screen and (max-width: px);
   Special attention when using max-width. Largers max-width will overwrite smaller max-width, but the smaller max-width's properties will be retained!

2. z-index
   We use z-index to change the stacked order of multiple images.
   z-index:1 will bring the image to the very front.
   z-index: a negative will bring the image to the very end.
   Note that z-index is not applicable when position is static.
