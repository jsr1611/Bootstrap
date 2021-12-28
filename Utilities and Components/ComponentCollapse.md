### LEARN BOOTSTRAP 4: UTILITIES AND COMPONENTS
### Collapsing a Component
Bootstrap also allows us to quickly add interactivity to a webpage. One way to include interactivity is to toggle the visibility of an element.

To add such a feature, we need two elements and a few attributes — one element with content and another element that switches the visibility of the previous element. For example:

```
<button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
  This button controls the following div's visibility. 
</button>

<div class="collapse" id="collapseExample">
  <p>This content's visibility gets toggled</p>
</div>
```
In the example above, we have a ```<button>``` element that toggles the visibility of the ```<div>``` element below it.

The button has an attribute ```data-toggle="collapse"``` which enables button’s toggle ability. Another attribute, ```data-target="#collapseExample"```, means that this button toggles the visibility of the element with the id of ```"collapseExample"```. The aria-expanded and aria-controls attributes are information for screen readers and other accessibility means.

Focusing our attention on the ```<div>``` below the button, notice that it has a class of ```"collapse"```, which hides the content when the webpage initially renders. Our <div> also has an id of ```"collapseExample"``` which corresponds to the value of the button’s data-target.

With both elements set up, we’ve made our page interactive! Look up [Bootstrap’s collapse documentation](https://getbootstrap.com/docs/4.2/components/collapse/) for additional ways of incorporating collapse.

### Instructions
1. Some of Gloria’s Gardening users might be interested in seed specials. Let’s make this content collapsible so it’s only relevant to users who want to click and learn more.
Locate the row with collapsible content to find the elements you’ll need to manipulate.
Change the value of the ```<button>‘```s data-target to ```"#seedSpecial"```. Then, add a data-toggle attribute and assign it a value of ```"collapse"```.


2. Now let’s make the content inside the ```<p>``` element, below the ```<button>``` element, collapsible. Add a class of ```"collapse"```. Also, assign an id of ```"seedSpecial"```.
After you’ve run your code and passed this checkpoint, play around with the button in the browser and watch the text appear and disappear!
