qom-syntax
====================

Qom theme for [Rainbow](http://craig.is/making/rainbows) syntax highlighter.

I am using it in my projects. Such as [Qom](https://github.com/rozzy/Qom), for example.

# Install
To use Rainbow, you shoul download .zip-archive from [repository](https://github.com/ccampbell/rainbow) and upload it on your server.
Then you should insert following scripts after `</body>` tag:
```html
  <script src="js/jquery.min.js"></script>
  <script src="js/rainbow.min.js"></script>
  <script src="js/language/generic.js"></script>
  <script src="js/rainbow.linecount.js"></script>
```

And also insert it into your `<head>`:
```html
   <link href="css/qom.css" media="screen" rel="stylesheet" type="text/css" />
```

# Example
There is a little example of using Rainbow with my theme:
```html 
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Qom</title>
    <script charset="utf-8" src="js/jquery.js" type="text/javascript"></script>
    <link href="css/qom.css" rel="stylesheet" />
  </head>
  <body>
    <pre>
      <code data-language="ruby">
        # Simple Sinatra application:
        require 'sinatra'

        get '/hi' do
          "Hello World!"
        end
      </code>
    </pre>
  </body>
  <script src="js/jquery.min.js"></script>
  <script src="js/rainbow.min.js"></script>
  <script src="js/language/generic.js"></script>
  <script src="js/rainbow.linecount.js"></script>
</html>
  
```
