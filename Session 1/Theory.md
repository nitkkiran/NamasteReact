# Chapter 1 Inception

## What is Emmet?
Emmet allows users to type shortcuts for code which are then expanded to full code. e.g. typing html:5 will create a HTML 5 element as below.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## Difference between library and framework
Main difference between library and framework is that our code will call the library whereas in the case of framework, our code will be called by the framework.  
Library is used to reuse an existing functionality into our application whereas framework provides tools and templates to create an application.

## What is CDN? Why do we use it?
CDN is Content Delivery Network, it is used to cache static files so that they can be loaded faster when required onto the client systems.

## Why is React known as React?
Because it reacts to data changes and efficiently updates the UI.

## What is Cross Origin in Script tag?
Cross origin in Script tag indicates that the resource needs to be fetched from a different domain.

## What is the difference between React and React DOM?
React helps in creating the User Interfaces whereas React DOM helps in interacting with the DOM.

## What is the difference between react.development.js and react.production.js files via CDN?
react.production.js file is minified version of the react.development.js

## What is async and defer?
In async, HTML parsing continues while the script files are downloaded from network and begins the script execution when download is complete.  
In defer, HTML parsing continues while the script files are downloaded from network, but the script execution starts only when the HTML parsing is complete.