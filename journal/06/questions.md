# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > Entry point of our application is through the index.html that then accesses our main.js

02. What is the difference between a vue `component` and `page`?

  > A page is what is first initial component that is loaded when reaching a route on a vue project. A component is a reusable piece of UI that can exist within pages.

03. What is ***Component-Based Architecture***?

  > It's the concept of splitting up many piees of UI into reusuable pieces that each can be edited on their own.

04. What are the three tags that make up a Vue component?

  > Template, script, and style.

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > | ANSWER HERE |

06. Which component in Vue does the vue-router use to mount pages onto?

  > The vue-router uses the router-view component in the App.vue file to mount pages.
07. What is the difference between the `AppState` and the state object within a component?

  > The AppState acts as our single source of truth of the current state within the app, while the state in the component should only refer to any states that are needed by that component.

08. What is the responsibility of `Services` in our Vue projects?

  > Services are used to update our AppState and its data.

09. What are ***props*** and how are they used? Provide an example

  > | ANSWER HERE |

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > reactive()
