# Managing the Fullstack Application

1. Describe the two ways to bind Data in Vue?

  > We can use either double curly braces wrapping a variable, and using v-model to 2 way bind a variables data.

2. The `SPA` acronym stands for what?

  > Single Page Application

3. What are some of the advantages/uses of a `SPA` over a traditional one?

  > Faster load times and less files, since you are simple just removing and injecting HTML rather than returning a brand new HTML file to the user.

4. What does the `onMounted` method in Vue do?

  > The moment a component is mounted onto the page, anything inside the onMounted method is ran.

5. What is the `v-model` attribute in Vue for, and when might you use it?

  > v-model is used for binding data of an HTML element to a variable in javascript. Typically we use it to bind it to inputs, that way any change to the variable is reflected in the input and any input change is reflected in the variable.

6. What is the package.json file used for?

  > We use it for installing dependencies, dev dependencies and running particular scripts like serving or building.

7. Which Vue attributes(directives) could you use to conditionally render elements on a page?

  > v-if and v-show

8. What is the purpose of the `key` attribute when using `v-for` on an element?

  > the key attribiute is used to id a particular div or element in order for Vue to remember and be able to maniuplate the correct element/div. 

9. What is the `<slot>` element and what is it used for?

  > The slot element is used to inject HTML into the where the slot is defined. Like injecting different forms within a Modal component, the form we choose to inject goes where the slot element is defined.
