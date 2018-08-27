# Emoji Color Picker 🎨

## About this Project
Project was done to learn some of the basics of using Vue.js. When you click on one of the grids, the background of the screen changes. I chose Vue because it seems to be an up and coming framework that is used by a lot of companies, some include Netflix, Adobe, Grammarly, GitLab, and Behance.

## About Vue
Vue is a JavaScript front-end framework that was built to organize and simplify web development. It is considered to be a less opinionated framework, which can allow for incremental adopted into existing projects. The core library focuses on declarative rendering and component composition, and there are libraries available for more complex applications. It may have less libraries than something like React, but all of the libraries are officially supported and kept up to date with the core library.

Vue has many similarities to React, both uses a virtual DOM, can seperate concerns throug the use of components, and uses a strong core library that can use many companion libraries. While React will completely re-render a component during a state change, unless explicitly told not to, Vue only re-renders parts of a component that changed during a state change.

Vue was created by Evan You. He summed up his thought process, "I figured, what if I could just extract the part that I really liked about Angular and build something really lightweight." Vue was originally released in February 2014 and is maintained by a dedicated global team. https://vuejs.org/v2/guide/team.html

## Installing Vue
Vue can be used on a small website by calling in the CDN in a script tag, src="https://cdn.jsdelivr.net/npm/vue@2.5.16/dist/vue.js". Or using a CLI command to create your app, similar to create-react-app. To do this, you will need to install vue using node. Run npm install -g @vue/cli - then run vue create project-name. Once your app is built, Vue also creates the run script npm run serve.

## Building with Vue
When building your app, data is passed through from the component into a virtual DOM. This can be displayed in HTML a few ways, you can use a handlebars approach {{message}}, or a v- directive. Some of these are v-text or v-html. v-text will display the message exactly as written, and v-html will take the text, render any html elements, like a break tag, then display the message.

Vue can create HTML elements by referring to what is created as a component. directives can also be used to make if and for loops, using v-if and v-for respectively. Props can be passed by using a : (colon) before what is being passed.

## Conclusion
This is just the start of using Vue. This app is just a single page application, and doesn't touch into the more complex uses. the Vue documentation is helpful and in-depth, due greatly to a dedicated research team. After having spent some time in research and following a tutorial, I really enjoyed working with this. This was built following a tutorial on https://scrimba.com/g/glearnvue
