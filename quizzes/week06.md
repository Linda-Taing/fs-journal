# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
The main.js is the entry point of the application.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A component is designed to be a reusable source. Where as the page contains the components for the user level and user experience.

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
V-for allows us to loop through arrays and templates when called upon. 
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
The three tags in our Vue Component are <template> <script> <style>.

```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle this means that we should set type of function that can cover several subclasses to not break the code.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
The component used is <router-view>
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState is used as a global variable, where as the state within the component is local.

```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
The Services is there to keep the business logic of application and keeping the separation between the UI. We talked in lecture about making the service functions for any services and not having any dependencies to that part if we can keep it in the controller or to their pages.

```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The index.html because that's where we mount the main.js to that runs first most on the application.

```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
<style> and <scoped>
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
Vue.Observable(). this method is created for the reactive object and it is automatically triggered  when any change or modifications.
```