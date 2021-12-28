### LEARN BOOTSTRAP 4: UTILITIES AND COMPONENTS
### The Carousel Component
There are times that we want to showcase a group of images but not want to have our users scroll through one picture on top of another. Instead, we could fit our images into a slideshow using <i>Bootstrap’s carousel component</i>.

[Bootstrap has many carousel examples](https://getbootstrap.com/docs/4.2/components/carousel/) but let’s go through a basic example together:
```
<div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="example_slide_1.png" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="example_slide_2.png" alt="Second slide">
    </div>
  </div>
</div>
```
The example above will render a slideshow that loops through two images, displaying one at a time. In the actual code:

The parent ```<div>``` element has an id of ```"carouselExampleSlidesOnly"```, two classes ```"carousel"``` and ```"slide"```, and the attribute ```data-ride="carousel"```.
The id is used later when we want to add controls to click between slides.
The classes provide the styling and formatting.
The data-ride attribute provides the interactivity and slide transitions.
We also have a nested ```<div class="carousel-inner">``` element that contains other <div> elements with images.
Nested inside the 2nd ```<div>``` is yet another ```<div>``` with a class of ```"carousel-item"``` and ```"active"``` (only one image needs the active class, if none have active, no images are shown).
Each ```<div>``` with .carousel-item has a nested ```<img>``` element which have the usual src and alt attributes.
The ```<img>``` elements use two utility classes ```"d-block"``` sets its display as block and the ```"w-100"``` is to take up 100% of the width.
Now, let’s implement a carousel with arrows that control the slideshow.

### Instructions
1.The HTML skeleton of a carousel is already in <strong> index.html</strong> but you need to add the appropriate class values to the ```<div>``` elements. The parent <div> element should also have a ```data-ride``` attribute with the appropriate value.
Look over [Bootstrap’s slides only example](https://getbootstrap.com/docs/4.2/components/carousel/#slides-only) for reference.


2.Now that the carousel is in place, let’s add some controls for users to click through the slides.
You have to use [Bootstrap’s with controls example](https://getbootstrap.com/docs/4.2/components/carousel/#with-controls) to implement this feature. Check out the hint for additional help!