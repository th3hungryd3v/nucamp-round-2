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

- Challenge Questions: More Attributes

1.  ``` <a href="#" target="_blank"> ```

2. Define a primary language with the lang attribute, and then call out the secondary language(s) with *lang* attributes on elements in the document

    .b Define lang in the specific sections of the document as needed:
```html
<div lang="fr-CA" xml:lang="fr-CA">
Canadian French content...
</div>
<div lang="en-CA" xml:lang="en-CA">
Canadian English content...
</div>
<div lang="nl-NL" xml:lang="nl-NL">
Netherlands, Dutch content...
</div>
```

3. The meta description is an HTML tag you can set for a post or page of your website. In it, you can describe what your page is about. If you’re lucky, Google will show it beneath your page’s title in the search results. It brings you an opportunity to convince search engine users that your page will offer what users are looking for.


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