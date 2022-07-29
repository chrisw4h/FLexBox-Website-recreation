# FLexBox-Website-recreation
The files labeled Snow ball are meant to recreate the website depicted here: https://css-tricks.com/designing-a-product-page-layout-with-flexbox/. My first intention was to recreate the header labeled SNOWBALL. I started using the header tag but later I decided to use the div tag so I can make it flush with the top and sides. With the div tag i could simply make the width of the div 100% of the body width and set the top margin to 0. However, setting the top margin of the div proved ineffective. After some toiling around I found out the margin for my h1 tag was taking up space. So I set h1 margin-top to 0.

My next mission was to create links at the bottom of the header bellow SNOWBALL. I tried adjusting the margin on the top and on the bottom to no avail. I wanted to increase the padding to visually move the letter closer to the bottom but I later used a div. Most of my solutions involved using a div up to this point so that's what I did for the links as well. I increased margin-top and eyeballed it until it looked flush with the bottom of the header (there must be a better way to do this).

The next step was to use flex. I simply opened up css tricks and looked up the properties and vlaues to adjust content in flex mode. I wanted too evenly space out the links.
