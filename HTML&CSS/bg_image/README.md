background:url('image.jpeg')
background-repeat
background-position
background-size
background-attachment
shorthand syntax
gradient

1. background:url()
   对于小尺寸的图片，会自动铺满
   对于大尺寸的图片，不会

2. background-repeat
   no-repeat，则不会 repeat
   repeat-x, 则仅水平铺满
   space, 则每个重复单元之间有空隙
   round

3. background-size: cover 一定铺满
   background-size:contain

4. background-position
   控制图片出现在哪里
   可以写成 -- background-position:left
   或者写成 -- background-position: 20% 50% 从左上角算起

5. background-attachment
   fixed:可以实现在滚动页面时，指定的 background image 不动

6. 渐变效果
   background: linear-gradient(red,green);
   background: linear-gradient(to top, red, green);
   background: linear-gradient(150deg, red, green);
   background: linear-gradient(to top right, red, green);

7. pro tip :)
   background: url(blablabla.jpeg) center/cover fixed
   no-repeat;
