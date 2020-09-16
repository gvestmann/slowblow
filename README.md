# slowblow

1 - Introductory Course: HTML & CSS - Layouting
Recreation of an old Slowblow poster, in plain/static HTML.

LIVE DEMO HERE: https://gvestmann.github.io/slowblow/

When asked to recreate an advertising poster, the choice was simple. Since 2004, a poster for Slowblow's s/t album and release concert has been hanging on my wall. There were actually two types of posters advertising the same concert, the other one dedicated to múm's new album "Summer Make Good", which was released around the same time. The poster can be seen in the repo under /slowblow-original-poster.jpg.

I started by scanning the poster and then proceeded to cutting out some graphics. The biggest challenge was "extracting" the waterdrop-looking illustration at the bottom, since it was partly covered by text. You can have a look at ./graphics/bottom.psd to see how I worked my way around it by hiding stuff with the "overlay"-layer. One last thing I did in Photoshop was using the blur > average filter to find the right background color.

The page is built on screen-size 1440px width - and I kept that in mind for an ideal outcome. Since the poster is square, I built it 1440px height as well. I exported the wings as 790px height because they make up ~55% of the poster. I used flexbox for the the top 3/4 part (wings and first two lines of text), as well as the footer section. The rest is a more simple HTML aligned centered with some css-styling for text and space. I added some animation to the poster, and did some adjustments to make it look better on mobile (including using "vw" for font-size.) I know the responsive part can be improved. Might just do that later on. I used Google Fonts, trying to match the look of the poster. I ended up using: Special Elite for the typewriter text, Parisienne for Smekkleysa's logo and Solway for the rest. The only text seen on the site which is an image are the bands logos. It would have been easy to use fonts, but it would never have looked the same. When reading index.html you can see some more detailed comments about how I approched building this. All in all I'm pretty content with what I achieved and I learned a bunch of new stuff - and it's kind of surreal seeing this old poster of mine as an HTML-file! 

I had an idea to add some stuff to the poster, for example Facebook-links, or samples from the album. But ended up deciding I just wanted pay my respect by keeping it as is. But be sure to check out their album here: https://open.spotify.com/album/0wYmsPO8BY3KSjxbFQvyYE?si=Pl5EhEzIR5KXhY3_S5XXew 