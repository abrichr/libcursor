libcursor
=========

libcursor is a JavaScript library for manipulating cursor inside 
textareas and contenteditable html elements.

### Using libcursor
##### Include the library:
```HTML
<script 
   type='text/javascript' 
   src='//sujeet.github.io/libcursor/libcursor.js'>
</script>
```

##### Here is a sample piece of code:
```javascript
/* *
 * Write "Hello world!" with cursor 
 * ending up just after the 'o' in 'Hello' 
 */
cursor = Cursor.new ();
cursor.insert ("world!")
      .moveBackward (6)
      .insert ("Hello")
      .insertAfter (" ");
```
For API documentation, visit [github pages for libcursor]
(http://sujeet.github.io/libcursor/symbols/Cursor.html "API documentation").
