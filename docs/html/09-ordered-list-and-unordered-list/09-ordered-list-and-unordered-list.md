---
title: Ordered List and Unordered List, In Page Navigation
description: "Ordered List and Unordered List, In Page Navigation"
hide_table_of_contents: true
---

## Unordered List

An unordered list is used to create a list of related items that have **no specific order or sequence**. It is represented by the `<ul>` tag in HTML.

**Syntax :**

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Unorder List</title>
  </head>
  <body>
    <h1>Features of RTC</h1>

    <ul>
      <li>Live + Recorded Classes</li>
      <li>Teaching Assistance for Doubt Solving</li>
      <li>Notes for Quick Revision</li>
      <li>Low Fees</li>
    </ul>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-1.png" alt="output-1" width="600px"/>

### Types of Unordered Lists

There are three types of unordered lists that you can use by specifying the type attribute within the `<ul>` tag.

- `type="disc"` (default): The list items are marked with small black circles.

**Syntax :**

```html
<ul type="disc">
  <li>list1</li>
  <li>list2</li>
  <li>list3</li>
</ul>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>List</title>
  </head>
  <body>
    <h1>Features of RTC</h1>

    <ul type="disc">
      <li>Live + Recorded Classes</li>
      <li>Teaching Assistance for Doubt Solving</li>
      <li>Notes for Quick Revision</li>
      <li>Low Fees</li>
    </ul>
  </body>
</html>
```

**Output "**

<img src="/html/09/output-7.png" alt="output-1" width="600px"/>

- `type="circle"`: The list items are marked with circles.

**Syntax :**

```html
<ul type="circle">
  <li>list1</li>
  <li>list2</li>
  <li>list3</li>
</ul>
```

**Example :**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Unorder List</title>
  </head>
  <body>
    <h1>Features of RTC</h1>

    <ul type="circle">
      <li>Live + Recorded Classes</li>
      <li>Teaching Assistance for Doubt Solving</li>
      <li>Notes for Quick Revision</li>
      <li>Low Fees</li>
    </ul>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-2.png" alt="output-2" width="600px"/>

- `type="square"`: The list items are marked with squares.

**Syntax :**

```html
<ul type="square">
  <li>list1</li>
  <li>list2</li>
  <li>list3</li>
</ul>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Unorder List</title>
  </head>
  <body>
    <h1>Features of RTC</h1>

    <ul type="square">
      <li>Live + Recorded Classes</li>
      <li>Teaching Assistance for Doubt Solving</li>
      <li>Notes for Quick Revision</li>
      <li>Low Fees</li>
    </ul>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-3.png" alt="output-3" width="600px"/>

### Ordered List

An ordered list is used to create a list of related items that have a **specific order or sequence**. It is represented by the `<ol>` tag in HTML.

Example :

1. 1, 2, 3, 4,....,
2. a, b, c, d,....,
3. A, B, C, D,....,
4. I, II, III, IV,....,
5. i, ii, iii, iv,.....

**Syntax :**

```html
<ol>
  <li>list Item 1</li>
  <li>list Item 2</li>
  <li>list Item 3</li>
</ol>
```

**Example :**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Syllabus of RTC</h1>

    <ol>
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Git & Github</li>
    </ol>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-4.png" alt="output-4" width="600px"/>

### Types of Ordered Lists

There are different types of ordered lists that you can specify using the type attribute within the `<ol>` tag.

- `type="1"` (default): The list items are numbered with Arabic numerals (1, 2, 3, etc.).

**Syntax :**

```html
<ol type="1">
  <li>list Item 1</li>
  <li>list Item 2</li>
  <li>list Item 3</li>
</ol>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Syllabus of RTC</h1>

    <ol type="1">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Git & Github</li>
    </ol>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-4.png" alt="output-4" width="600px"/>

- `type="A"`: The list items are numbered with uppercase letters (A, B, C, etc.).

**Syntax :**

```html
<ol type="A">
  <li>list Item 1</li>
  <li>list Item 2</li>
  <li>list Item 3</li>
</ol>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Syllabus of RTC</h1>

    <ol type="A">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Git & Github</li>
    </ol>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-5.png" alt="output-5" width="600px"/>

- `type="a"`: The list items are numbered with lowercase letters (a, b, c, etc.).

**Syntax :**

```html
<ol type="a">
  <li>list Item 1</li>
  <li>list Item 2</li>
  <li>list Item 3</li>
</ol>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Syllabus of RTC</h1>

    <ol type="a">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Git & Github</li>
    </ol>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-8.png" alt="output-8" width="600px"/>

- `type="I"`: The list items are numbered with uppercase Roman numerals (I, II, III, etc.).

**Syntax :**

```html
<ol type="I">
  <li>list Item 1</li>
  <li>list Item 2</li>
  <li>list Item 3</li>
</ol>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Syllabus of RTC</h1>

    <ol type="I">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Git & Github</li>
    </ol>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-9.png" alt="output-9" width="600px"/>

- `type="i"`: The list items are numbered with lowercase Roman numerals (i, ii, iii, etc.).

**Syntax :**

```html
<ol type="i">
  <li>list Item 1</li>
  <li>list Item 2</li>
  <li>list Item 3</li>
</ol>
```

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Syllabus of RTC</h1>

    <ol type="i">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>Git & Github</li>
    </ol>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-10.png" alt="output-10" width="600px"/>

## Starting the List at a Specific Point

You can start the ordered list at a specific point using the `start` attribute within the `<ol>` tag. The start attribute specifies the starting number for the first item in the list.

**Example :**

```html
<ol start="2">
  <li>Item 2</li>
  <li>Item 3</li>
  <li>Item 4</li>
</ol>
```

In the example above, the ordered list `<ol>` starts at the number 2. The first item in the list will be labeled as "Item 1" the second item will be "Item 2," and so on.

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html>
  <head>
    <title>Ordered List</title>
  </head>
  <body>
    <h1>Pending Syllabus</h1>

    <ol type="A" start="2">
      <li>CSS3</li>
      <li>Git & Github</li>
      <li>Bootstrap</li>
    </ol>
  </body>
</html>
```

**Output :**

<img src="/html/09/output-6.png" alt="output-6" width="600px"/>

## In Page Navigation

In-page navigation, it allows users to jump to different sections of the same web page using links. This is particularly useful for long pages with a lot of content, like articles, documentation, or FAQs 😊

**Example :**

```html showLineNumbers=true
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>In-Page Navigation Example</title>
</head>
<body>
<h1> Road To Code</h1>
    <nav>
        <ul>
            <li><a href="#section1">Features</a></li>
            <li><a href="#section2">Achievements</a></li>
            <li><a href="#section3">Courses Details</a></li>
        </ul>
    </nav>

    <h2 id="section1">Features</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo corporis ab veritatis sunt illum ducimus animi natus officia! Hic, ratione? Voluptate nihil repellendus perspiciatis quis ex vitae quo veritatis est.</p>
    <hr/>
    
    <h2 id="section2">Achievements</h2>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea asperiores optio fuga ad harum nobis quaerat vero minus eveniet. Inventore nam voluptatum illum expedita laboriosam, veniam totam atque in laudantium.</p>
    <hr/>
    
    <h2 id="section3">Courses Details</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate at, provident ab officia perspiciatis delectus voluptatum, suscipit ullam qui numquam totam iste labore debitis, optio tenetur esse quas. Delectus, possimus!</p>
    <hr/>
</body>
</html>
```
**Output :**

<img src="inpagenav_op1.png" alt="inpagenav_main" width="600px"/>


After clicking on `Achievement` you will go to section 2

<img src="inpagenav_op3.png" alt="inpagenav_main" width="600px"/>

**Explanation :**

The main body of the example features a main heading "Road To Code" followed by a navigation menu `within a <nav> tag containing links to different sections of the page: "Features," "Achievements," and "Courses Details."` Each link uses an `anchor (href) pointing to corresponding sections identified by unique id attributes (#section1, #section2, #section3)`. The content sections each have a subheading `(<h2>)` with these id attributes, followed by paragraphs of placeholder text, and are visually separated by horizontal rules `(<hr/>).` This setup `allows users to click on the navigation links to quickly jump to the specific content` sections within the same page.