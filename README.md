# slowblow

1 - Introductory Course: HTML & CSS - Layouting
Recreation of an old Slowblow poster, in plain/static HTML.

LIVE DEMO HERE: 

When asked to recreate an advertising poster, the choice was simple. Since 2004, a poster for Slowblow's s/t album and release concert has been hanging on my wall. There were actually two types of posters advertising the same concert, the other one dedicated to múm's album "Summer Make Good", which was released around the same time. The poster can be seen in the repo under /slowblow-original-poster.jpg.

I started by scanning the poster and then proceeded to cutting out some graphics. The biggest challenge was "extracting" the waterdrop-looking illustration at the bottom, since it was partly covered by text. You can have a look at ./graphics/bottom.psd to see how I worked my way around it by hiding the "overlay"-layer. One last thing I did in Photoshop was using the blur > avarge filter to find the background color.

The page is built on screen-size 1440px width. Since the poster is square, I built it 1440px height as well. I exported the images as 790px height because they make up ~55% of the poster.