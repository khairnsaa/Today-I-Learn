# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

it's the first day of week 6, today we start learning about node js. this week we have a personal task and team task. for personal task we need to answer a few question that the mentor give us on notion, and for personal task, we need to create a RESTful API using nodejs express and mongoDB. also i've finished watching video lecture, there's a few things i learn from a video lecture.

## What is Web Server?
At the most basic level, whenever a browser needs a file that is hosted on a web server, the browser requests the file via HTTP. When the request reaches the correct (hardware) web server, the (software) HTTP server accepts the request, finds the requested document, and sends it back to the browser, also through HTTP. (If the server doesn't find the requested document, it returns a 404 response instead.)

To publish a website, you need either a static or a dynamic web server.

A static web server, or stack, consists of a computer (hardware) with an HTTP server (software). We call it "static" because the server sends its hosted files as-is to your browser.

A dynamic web server consists of a static web server plus extra software, most commonly an application server and a database. We call it "dynamic" because the application server updates the hosted files before sending content to your browser via the HTTP server.

For example, to produce the final webpages you see in the browser, the application server might fill an HTML template with content from a database. Sites like MDN or Wikipedia have thousands of webpages. Typically, these kinds of sites are composed of only a few HTML templates and a giant database, rather than thousands of static HTML documents. This setup makes it easier to maintain and deliver the content.

## How To Create Schema With Mongoose Library?
first thing to do if we want to write a schema is importing the mongoose library first

`const mongoose = require('mongoose')`

after that let’s create a variable to store the schema and fill that variable with `mongoose.Schema()` function

`const postSchema = new mongoose.Schema()`

note: make sure you write the mongoose schema function with the capital letter S

inside mongoose schema function, let’s create an object for post attribute (title and writerName)

```jsx
const commentsSchema = new mongoose.Schema({
    title: {},
    name: {}
})
```

after that inside the title you need to create an object again to specify type of title attribute (i.e string or number)

```jsx
const commentsSchema = new mongoose.Schema({
    name: {
        type: String,
        required: true
    },
    comment: {
        type: String,
        required: true
    }
})
```

and the last thing is you need to export this module by writing this line of code

`module.exports = mongoose.model("Comment", commentsSchema)`

as you can see inside mongoose.model() we see 2 parameters, the first parameter is what you want a new collection you see on your mongoDB, and the second parameter is the schema you just created.

```jsx
const mongoose = require('mongoose')

const commentsSchema = new mongoose.Schema({
    name: {
        type: String,
        required: true
    },
    comment: {
        type: String,
        required: true
    }
})

module.exports = mongoose.model("Comment", commentsSchema)
```

and code above is the final result of our postSchema
