#   Login and Signup Page(Front-end only)

 To create a simple login and signup form with validation using HTML, CSS & JavaScript.

## Form structure





```bash
  <input type="text" name="name" id="logName" placeholder="Username">

```

## Styling

```bash
  <link rel="stylesheet" type="text/css" href="style.css">

```
## Animation

```bash
  <script src="index.js"></script>

```

In order to display Login form and Signup form on one web page, we have to add an animation part using JavaScript and jquery. Therefore, include the jquery CDN within the <script> tag.
```bash
  <script src="https://code.jquery.com/jquery-3.3.1.min.js"
integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>

```

## Form Validation
```bash
  <form class="login"name="loginForm"
onsubmit="returnvalidateLoginForm()" method="POST">

```
