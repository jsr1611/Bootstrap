LEARN BOOTSTRAP 4: UTILITIES AND COMPONENTS
The Navigation Component
In addition to useful utility classes, Bootstrap offers a collection of components, such as a navbar, buttons, a carousel/slideshow for images, and much more! Each Bootstrap component serves a distinct purpose and we can find examples and code snippets directly from the documentation — then, we can tweak the components to our personal needs.

The first component we’ll investigate is the navigation (nav) component which offers our users a collection of links. The nav component is slightly different from a navbar component. The nav component is often specific to one or a few webpages, whereas a navbar often appears on all the pages of a website.

There are many ways to create a basic nav component. Here’s one example:
```
<ul class="nav">
  <li class="nav-item">
    <a class="nav-link" href="#">First Link</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Second Link</a>
  </li>
</ul>
```
In the above example:

We created a navigation component using an <ul> that has a class of "nav".
The ```<ul>``` has nested ```<li>``` elements which each have a class of "nav-item".
Inside each ```<li>``` is an ```<a>``` which has a class of "nav-link".
Alternatively, for a simpler nav component of only links:
```
<nav class="nav">
  <a class="nav-link" href="#">First Link</a>
  <a class="nav-link" href="#">Second Link</a>
</nav>
```
Notice that we still have the parent element with a class of "nav" and the children elements with a class of "nav-link". Both examples render the same links, but we might choose one example over the other depending on how we want our layout to look.

Read through Bootstrap’s nav documentation for more information.

Instructions
1. We’ll begin the process of piecing together a gardening website using various Bootstrap components.
Let’s utilize the navigation component we learned about and transform the current <nav>.
Assign the ```<nav>``` a class of "nav".

2. Apply a class of "nav-link" to each of the ```<a>``` elements to provide some Bootstrap styling.

3. While we’re at it, let’s also center the links.
Find out what class to add the nav component using [Bootstrap’s Nav documentation](https://getbootstrap.com/docs/4.2/components/navs/).