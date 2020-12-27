# Error handling and debugging 

1. order of execution: 

it helps finding the source of an error. 

2. execution contexts: 

3. the stack:

when javascript interpreter process one line of code at a time when a statement needs data from another function it stascks. 

4. execution contexts & hoisting: 

which is divided to 
* prepare 
* excute

5. understanding scope: 

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 

6. understanding errors: 

if javascript had an error then it will throws an exception. 

7. error objects: 

it helps finding mistakes and browsers have tools to help. 

# content panels 

content panels allow you to showcase extra information within a limited space. 
accordion, tabbed panels, responsive slider, creating a jquery plugin, modal window and photo viewer are several examples in panels. 

### separation of concerns 

its a best practice to separate your content HTMI,JS,CSS 

### accessibility and no javascript 

thinking about those who are using your website in diffferent statuses when writing any script. 

### creating  panels 

each panel had its own way to be created 
those steps vary depending on the type of panels you want to creat. 


#### all in all: 

* Content panels offer ways to show more content
  within a limited area.
* Popular types of content panels include accordions,
  tabs, photo viewers, modal windows, and sliders.
* As with all website code, it is advisable to separate
  content (HTML), presentation (CSS), and behavior
  (JavaScript) into different files.
* You can create objects to represent the functionality
  you want (as with the modal window).
* You can turn functions into jQuery plugins that allow
* you to re-use code and share it with others.
* Immediately invoked function expressions (llFEs) are
  used to contain scope and prevent naming collisions. 


