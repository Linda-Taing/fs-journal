# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```

    One-way binding is binding using the {{}}, this automatically updates the target.
    Two-way binding is when you need data source to the target from another target such as Data-Forms. we use the V-model.

```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single
Page
Application

```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
The application can feel like a multipage experience, it also declutters and keeps the page looking clean and organzed and helps with devs to have reusable components and such from behind the scenes.

```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
This is like our constructor that we previously used in MVCs structure. Making sure we are calling the function.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
V-models are the two-way binding. This helps us get our information off a form to another data target.

```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->

```
This is now used for our on-click: @click.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
The directives are the v-if, v-show, v-for, v-else. 
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key is to know what element we would loop through. as we would use a for-loop. it only renders the items that are called in that key. The keys are like an id they have to be unique.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The slot element is used for a reusability purpose in our case we used slots in our Modals. We had a modal template that we could slot in the body and add ids to use multiple slots.
```