# Front-End Interview Preparation

- [**Javascript**](#javascript)
  * [**Execution Context**](#execution-context)
    + [Lexical Scope](#lexical-scope)
    + [Closures](#closures)
    + [Hoisting](#hoisting)
    + [Function and block scoping](#function-and-block-scoping)
    + [Function expressions and declarations](#function-expressions-and-declarations)
    + [The *this* keyword](#the-this-keyword)
    + Call, Apply and Bind
  * [**Objects**](#objects)
    + [Object Prototypes](#object-prototypes)
    + [Constructors](#constructors)
    + [Type coercion](#type-coercion)
      - [Typeof](#typeof)
      - [Instanceof](#instanceof)
      - [Object.Prototype.toString](#objectprototypetostring)
      - [Mixins](#mixins)
  * [**Functions**](#functions)
    + [Composition](#composition)
    + [Higher order functions](#higher-order-functions)
  * [**Events**](#events)
    + [Event delegation](#event-delegation)
    + [Bubbling](#bubbling)
  * [**Asynchronous Programming**](#asynchronous-programming)
    + [Callbacks](#callbacks)
    + [Promises](#promises)
    + [Await](#await)
    + [Async](#async)
- [**DOM**](#dom)
  * [**Navigation**](#navigation)
    + [Selecting nodes](#selecting-nodes)
    + [Traversal up and down](#traversal-up-and-down)
    + [Traversal left and right](#traversal-left-and-right)
  * [**Manipulation**](#manipulation)
    + [Add](#add)
    + [Remove](#remove)
    + [Copy](#copy)
    + [Text content](#text-content)
    + [CSS classnames](#css-classnames)
  * [**Performance**](#performance)
    + [Document fragments](#document-fragments)
    + [Node caching](#node-caching)
- [**CSS**](#css)
  * [**Layout**](#layout)
    + [Column layout](#column-layout)
    + [Flexbox](#flexbox)
  * [**Responsive Design**](#responsive-design)
    + [Media queries](#media-queries)
  * [**Specificity**](#specificity)
  * [**Namespacing and naming**](#namespacing-and-naming)
- [**HTML**](#html)
  * [**Semantic Markup**](#semantic-markup)
  * [**Tag attributes**](#tag-attributes)
    + [disabled](#disabled)
    + [async](#async)
    + [defer](#defer)
    + [data-*](#data--)
  * [**Meta Attributes**](#meta-attributes)
  * [**Accessibility**](#accessibility)
- [**System Design**](#system-design)
  * [**Rendering**](#rendering)
    + [Client-side](#client-side)
    + [Server-side](#server-side)
    + [Universal](#universal)
  * [**State management**](#state-management)
    + [Unidirectional data flow](#unidirectional-data-flow)
    + [Two-way data binding](#two-way-data-binding)
    + [Reactive programming model](#reactive-programming-model)
    + [Passive programming model](#passive-programming-model)
  * [Async Flow](#async-flow)
    + [**XHR Calls**](#xhr-calls)
    + [**Bidirectional Calls**](#bidirectional-calls)
    + [**Web Sockets**](#web-sockets)
    + [**Server-sent Events**](#server-sent-events)
  * [**Separation of Concerns**](#separation-of-concerns)
    + [**Model-View-Controller (MVC)**](#model-view-controller--mvc--)
    + [**Model-View-ViewModel (MVVM)**](#model-view-viewmodel--mvvm--)
    + [**Model-View-Presenter (MVP)**](#model-view-presenter--mvp--)
  * [**Asset Delivery**](#asset-delivery)
    + [**Building**](#building)
      - [Code splitting](#code-splitting)
    + [**Testing**](#testing)
      - [Unit testing](#unit-testing)
      - [Integration testing](#integration-testing)
      - [End-to-end testing](#end-to-end-testing)
    + [**Vending through a CDN**](#vending-through-a-cdn)
- [**Web Performance**](#web-performance)
  * [**Critical Rendering Path**](#critical-rendering-path)
  * [**Service Workers**](#service-workers)
  * [**Image Optimisations**](#image-optimisations)
  * [**Lazy Loading & Bundle Splitting**](#lazy-loading---bundle-splitting)
  * [**HTTP/2 and server-push**](#http-2-and-server-push)
  * [**Prefetching and preloading resources**](#prefetching-and-preloading-resources)
  * [**Browser reflows**](#browser-reflows)
  * [**Promoting elements to the GPU**](#promoting-elements-to-the-gpu)
  * [**Browser layout, compositing and painting**](#browser-layout--compositing-and-painting)
- [**Data Structures and Algorithms**](#data-structures-and-algorithms)
- [**General**](#general)
  * [**HTTP Requests**](#http-requests)
    + [**GET**](#get)
    + [**POST**](#post)
    + [**PATCH**](#patch)
    + [**DELETE**](#delete)
    + [**Headers**](#headers)
      - [Cache-Control](#cache-control)
      - [ETag](#etag)
      - [Status Codes](#status-codes)
      - [Transfer-Encoding](#transfer-encoding)
  * [**REST vs. RPC**](#rest-vs-rpc)
  * [**Security**](#security)
    + [**JSONP**](#jsonp)
    + [**CORs**](#cors)
    + [**iFrame**](#iframe)

# **Javascript**

## **Execution Context**

 1. [The execution context in Javascript](http://davidshariff.com/blog/what-is-the-execution-context-in-javascript/)
 2. [The execution context  and the lexical environment](https://medium.com/dailyjs/javascript-basics-the-execution-context-and-the-lexical-environment-3505d4fe1be2)
 3. [Javascript scope chain and closures](http://davidshariff.com/blog/javascript-scope-chain-and-closures/)
 4. [Lexical environments: ECMAScript implementation](http://dmitrysoshnikov.com/ecmascript/es5-chapter-3-2-lexical-environments-ecmascript-implementation/)

### Lexical Scope

[Lexical Scope](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch2.md)

### Closures

[Scope  & Closures](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch5.md)

### Hoisting

[Understanding hoisting in Javascript](https://scotch.io/tutorials/understanding-hoisting-in-javascript)

### Function and block scoping
[Function scopes and block scopes in Javascript](https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7)

### Function expressions and declarations
[Function Declarations vs. Function Expressions](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)

### The *this* keyword
[Understand Javascript's *this*](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)

### Call, Apply & Bind
 1. [How to use Call, Apply and Bind](https://alexperry.io/personal/2016/04/03/How-to-use-apply-bind-and-call.html)
 2. [Javascript's Apply, Call and Bind methods in-depth](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)

## **Objects**

### Object Prototypes

### Constructors

### Type coercion

#### Typeof

#### Instanceof

#### Object.Prototype.toString

#### Mixins

## **Functions**

### Composition

### Higher order functions

## **Events**

### Event delegation

### Bubbling

## **Asynchronous Programming**

### Callbacks

### Promises

### Await

### Async

# **DOM**

## **Navigation**

### Selecting nodes

### Traversal up and down

### Traversal left and right

## **Manipulation**

### Add

### Remove

### Copy

### Text content

### CSS classnames

## **Performance**

### Document fragments

### Node caching

# **CSS** 

## **Layout**

### Column layout

### Flexbox

## **Responsive Design**

### Media queries

## **Specificity**

## **Namespacing and naming**

# **HTML**

## **Semantic Markup**

## **Tag attributes**

### disabled

### async

### defer

### data-*

## **Meta Attributes**

## **Accessibility**

# **System Design**

## **Rendering**

### Client-side

### Server-side

### Universal

## **State management**

### Unidirectional data flow

### Two-way data binding

### Reactive programming model

### Passive programming model

## Async Flow

### **XHR Calls**

### **Bidirectional Calls**

### **Web Sockets**

### **Server-sent Events**

## **Separation of Concerns**

### **Model-View-Controller (MVC)**

### **Model-View-ViewModel (MVVM)**

### **Model-View-Presenter (MVP)**

## **Asset Delivery**

### **Building**

#### Code splitting

### **Testing**

#### Unit testing

#### Integration testing

#### End-to-end testing

### **Vending through a CDN**

# **Web Performance**

## **Critical Rendering Path**

## **Service Workers**

## **Image Optimisations**

## **Lazy Loading & Bundle Splitting**

## **HTTP/2 and server-push**

## **Prefetching and preloading resources**

## **Browser reflows**

## **Promoting elements to the GPU**

## **Browser layout, compositing and painting**

# **Data Structures and Algorithms**

# **General**

## **HTTP Requests**

### **GET**

### **POST**

### **PATCH**

### **DELETE**

### **Headers**

#### Cache-Control

#### ETag

#### Status Codes

#### Transfer-Encoding

## **REST vs. RPC**

## **Security**

### **JSONP**

### **CORs**

### **iFrame**
