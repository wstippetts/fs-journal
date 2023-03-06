# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
```
One-way data binding:
One-way data binding is used to pass data from a component's data object to its template. In one-way data binding, changes made to the data object are reflected in the template, but changes made in the template do not affect the data object. One-way data binding is achieved by using the double curly braces {{ }} or the v-bind directive.
For example, to display the value of a variable "message" in a template, you can use:


<p>{{ message }}</p>
Or, to bind the value of an attribute to a variable, you can use:

<img v-bind:src="imageSrc">

Two-way data binding:
Two-way data binding allows changes made in the template to affect the data object, and changes made to the data object to be reflected in the template. Two-way data binding is achieved using the v-model directive, which binds the value of an input element to a variable.
For example, to create a text input that is bound to a variable "username", you can use:

python
Copy code
<input v-model="username">
```

**2.** The `SPA` acronym stands for what?
```
single page application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
```
does not require full page reload

In a single-page application, the user interacts with different parts of the page through a combination of JavaScript, CSS, and HTML. This approach can provide a faster and more seamless user experience compared to traditional multi-page web applications
```
**4.** What does the `onMounted` method in Vue do?
```
lifecycle hook in Vue 3 that is called when a component is mounted to the DOM
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
```
two-way binding directive that provides a convenient way to create a binding between a form input element and a Vue instance data property
```
**6.** The `v:on` (`@`) directive can be used for what?
```
used as a listener in vue. it can be used with; 
input: This event is fired when the user types into a form input element.
submit: This event is fired when a form is submitted.
keydown: This event is fired when a key is pressed down.
keyup: This event is fired when a key is released.
mousemove: This event is fired when the mouse pointer moves over an element.
mouseenter: This event is fired when the mouse pointer enters an element.
mouseleave: This event is fired when the mouse pointer leaves an element.
focus: This event is fired when an element receives focus.
blur: This event is fired when an element loses focus.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
```
v-if
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
```
 The key attribute serves as a unique identifier for each rendered element and helps Vue.js optimize the rendering process.
```
**9.** What is the `<slot>` element and what is it used for?
```
content distribution and composition. It allows you to create reusable components that can be customized with different content and layouts.
```