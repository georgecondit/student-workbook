# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
A dev can bind data from the 'setup' to double curlies in the template. A dev can also bind methods using the '@' symbol to events such as @click, and write the method for what that click does in the script tags as well. Classes can also be bound using a colon or 'v-bind'.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
1. Better user experience.
2. MPA reloads every page change, where a SPA only renders updated information.
3. It's used by major companies and is a more modern approach to rendering info to the DOM.
4. Load times are much faster. 
5. Because rendering is happening on the client side there is a smaller usage load on servers.
6. Client side rendering also allows for better cacheing and offline useability.

```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
On mounted acts like a controller telling the service to do some business logic. An expample of this would be an onMounted that rerequests all the blogs to be retrieved from the server to be rendered to the page. 
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-model is used to tell the controller that there is information coming in from a form. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
it can be used to bind a method to an action like a mouse click or submition of a form input.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
I would use a 'v-if' statement. As in v-if="allow this to be rendered to the page, when this is true"
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key attribute tells the v-for that the data that it should get is the value that is attatched to that key. 
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```A slot element allows the user to use different data in fields within a child component. So if you wanted to use a modal in several spots you could use slots within the modal component to adjust the information in that modal.

```