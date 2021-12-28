### LEARN BOOTSTRAP 4: UTILITIES AND COMPONENTS
### Adding a Card
Bootstrap also has a card component that serves as a container for smaller customized content. Card components are often grouped together to display a collection of similar content in manageable chunks. We can draw a comparison of the card component to playing cards in deck — in both cases, there are cards grouped together and each one contains something different.

Below is an example modified from [Bootstrap’s card documentation](https://getbootstrap.com/docs/4.2/components/card/#example):
```
<div class="card">
  <img class="card-img-top" src="placeholder.jpg" alt="card example image">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Card description goes here.</p>
    <a href="#" class="card-link">Link to somewhere.</a>
  </div>
</div>
```
Let’s highlight a few key points from the example:

To make a card component we need to assign a class of ```"card"``` to an element.
Inside the card component, there are two children, an ```<img>``` and a ```<div>``` element.
The ```<img>``` has a class of ```"card-img-top"``` which adds styling and formatting to the image.
The ```<div>``` has a class of ```"card-body"``` which adds a section with default padding.
The content inside the card body all have classes with ```"card-{value}"``` which adds styling to these elements specific for Bootstrap cards.
By default, this card will take up the entire width of its parent element.
Let’s add some of our own cards, remember to check [Bootstrap’s card documentation](https://getbootstrap.com/docs/4.2/components/card/#example) for more customizations!

### Instructions
1. Under the jumbotron is a row with 2 nested columns set up for our card components.
Inside the first column, add a <div> and assign it a class of "card". We’ll be making a garden related card for the webpage.


2. Use the [Bootstrap’s card documentation](https://getbootstrap.com/docs/4.2/components/card/) to add a header.
The text in the header should read Planting in the spring. Check the hint if you need help navigating the documentation:


3.Below the header add an image that renders at the top of the card.
Use the image from this link:

```
https://content.codecademy.com/courses/learn-bootstrap-components/flowers.png
```
Also, remember to assign the appropriate class.


4.Time to add more text to this card:
Under the image, add a ```<div>``` with a class of ```"card-body"```.

Inside the ```<div>``` you just made, add ```<p>``` with a class of ```"card-text"```. The text should read It's almost spring time, get your seeds ready for planting!


5.Great job adding a card to the page. Now, add your own customized card to the 2nd column!
If you want to add another image, feel free to use: 
```
https://content.codecademy.com/courses/learn-bootstrap-components/tropical.png.
```