Documentation
There are three main parts of my midterm project, the home page, individual character pages, and individual category pages. Due to the limitation of time, for the character and category pages, I each made one of them for demonstration, since the construction would be mostly the same.

1.	The home page
My design of the home page is a gallery like web page as I mentioned in my proposal. The home page is separated into two main parts: the header of the page on the top, and the gallery.
For the header on the top, there are three subunits, the logo on the left, the title of the page in the middle, and the navigation bar on the right. I used three separated divs that aligned together, floating left. And for the navbar, I added hover effects that changes the curser and the background color of the buttons. 
For the gallery, I used 996 grid for the main structure. I used grid-4 that arranges 3 images a row for two rows to fit in the 6 characters I chose. Hover effects are also added to the image, including appearing a cover and shows information of the hovered image, as well as a button that leads to another for more information. Scaling up the image transition is also added to make it more interactivce.

2.	The character page
The header of the character is the same with the home page to keep the consistency, while the content is different. 
For this page, I arranged for images in a row that show how the character is represented in the for medias. To make it interactive, I decided to add a hover effect to the image: the picture scales up, a white semi-transparent show and a paragraph of introduction appears. At first, I continued to use 996 grid as the basic structure of my web page. But while I was trying to add the scale up transition effect, I had a trouble manipulating the div of the image. Since it’s preset in its own structures, I have to break it to make it flexible. Therefore, I have to abandon all of it as well as the 996 structure, and build up my own structure. This time it was more successful, I was able to realize all the effects I planned to make by using the hover effect and the transition function.

3.	Same as the two previous pages, the header of the category page is also the same design.
For the content of this page, I decided to make a slide show by clicking buttons to see different pictures. This can be realized by JavaScript mouse click functions to change the image. But I want to use CSS to realize it. After learning more about the transition function and referred to some sample codes, I found that there is a smart way to make it look like changing images, by letting the image to appear outside the div and then move into the div to show it out. Using a href as a “button” to call different images, and transition function to move it inside, the slide show is then realized successfully.

After the lecture in photoshop, I edited all my images. I cut my images into the correct size as my divs are designed. After that I decreased the file size of the image so that they can load faster on the website. A miner issue is that the quality of the images are not so good, I have to sacrifise the quailty of the images to make them smaller. I think one thing I need to practice is to balance between the size of the images and the quality of the images.

Many further improvements could be added. Improve the background and navbar design. Make different slideshow effects with JavaScript. Polish the overall design of the gallery. There are some remaining div locating problems that need to solved. Complete the content of the webpage.  

The url of my website is http://192.168.50.184/~ww1025/Midterm/index.html

(The abondoned html and css files are included in the folder /testing)
