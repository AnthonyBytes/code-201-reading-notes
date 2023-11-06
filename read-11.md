Read: Class 11

# Readings: Audio, Video, Images

## Why is this topic important?

- This is important because videos and audio enhance the overall experience of a webpage. It's a lot easier to implement these features on sites today than it was in the early 2000s, so you should take advantage if needed. 

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

The first online videos were made possible by Flash and Silverlight, but they had major security and accessibility issues. These technologies are now obsolete, in favor of HTML solutions for video and audio elements available in JavaScript APIs. 

2. Describe the use of the src and controls attributes in the <video> element.

The src attribute contains a path to the video you want to embed. It works exactly the same way as if your providing a src to an image.

The controls allows you to add a video and audio playback interface to the video, so you can pause, play and change volume.

3. Why is it important to have fallback content inside the <video> element?

It's important to have a paragraph inside the video tag in case the browser is older or doesn't support.  This will be displayed if the browser accessing the page.

4. Write a very short story where <audio> and <video> are characters.

In the bustling city of Technoville, Audio and Video were renowned as the dynamic duo of creativity. Audio, with its soulful melodies, could stir emotions like no other, while Video's vivid imagery painted worlds beyond imagination. Together, they embarked on artistic escapades, weaving tales that left audiences breathless. One day, a curious inventor named User arrived, seeking their collaboration to craft a masterpiece. With synchronized precision, Audio and Video transformed User's vision into a mesmerizing narrative, leaving an indelible mark on the city's artistic legacy. From then on, their legend echoed through Technoville, a testament to the boundless magic that unfolds when talents unite.

(some assitance from ChatGPT)

## A Complete Guide To Grid

1. How does Grid layout differ from Flex?

Grid layout is designed for creating two-dimensional layouts, where you can define both rows and columns. It's best for creating complex, grid-based designs.

Flexbox is primarily designed for one-dimensional layouts, focusing on arranging items along a single row or column. It's best for creating flexible and dynamic layouts.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

A Grid container is an element that has been set to use CSS Grid layout. It is the parent element that contains a set of grid items. 

A Grid item is an element that is a direct child of a grid container. Grid items are the individual elements that are placed within the grid's cells.

Grid lines are the horizontal and vertical lines that form the grid's structure. They define the boundaries between rows and columns within the grid container.

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- Improved user experience
- Faster loading times
- Better image quality/resolution

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.

Srcset defines the set of images we will allow the browser to choose between, and what size each image is. Sizes defines a set of media conditions and indicates what image size would be best to choose, when certain media conditions are true. By using srcset and sizes together, developers can provide the browser with information so it can make a decisions about which image to download.

3. How is srcset more helpful for responsive images than CSS or JavaScript?

srcset allows the browser to choose the most appropriate image based on the device's screen resolution and viewport size. It also helps reduce bandwith usage and improve the page load speed.

## Things I want to know more about

- I just think it's going to be interesting to implement videos into our pages. 