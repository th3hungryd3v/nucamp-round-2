# 1-HTML-CSS-JavaScript

### Week 1
 - Course Setup & Introduction to HTML
Current Knowledge Level

1. How would you describe your level of expertise in HTML and CSS? (I've never written any HTML or CSS, Beginner, 3+ months into it, etc.)

a. Intermediate, 2 years

2. How would you turn the text below "Welcome to my page!" purple? Please answer based on your current knowledge. Saying "I don't know" or taking a guess is OK!

```html
<!DOCTYPE html>
<html>
<head>
    <link href="styles.css" rel="stylesheet">
</head>
<body>
    <h1>Welcome to My Web Page!</h1>
</body>
</html>
```
a. Quickly:
    Add a ```<style></style>``` at the closing ```</head>``` tag: ```h1 {color: purple}```
    b. Externally:
     Add a ```<link rel="stylesheet" href="stylesheet.css" />
     ```
     
meanwhile in ```stylesheet.css:```
```css
h1 {
    color: purple;
}
```

3. How would you describe your level of expertise in JavaScript? (I've never learned a programming language; I've programmed in other languages but not JavaScript, Beginner, 3+ months into it, etc.)
    
    a. Intermediate

4. What's wrong with the JavaScript code below, and how would you fix it?  Please answer based on your current knowledge. Saying "I don't know" or taking a guess is OK!

```
i = 11;

while (i > 10) {
    text += "The number is " + i;
    i++;
}

```

a. Since text is never defined, the code won't run.

### Week 2
 - More HTML and Introduction to CSS
### Week 3
 - Introduction to JavaScript
### Week 4
 - More JavaScript and the HTML DOM

Todos
 [x] Start Week-1
 [] Write a draft for the first blog entry
 [] 