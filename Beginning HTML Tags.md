markdown

In HTML, you can use various tags to structure your content and add different elements to your webpage. Let's explore some of the basic HTML tags:

#### Paragraph

The `<p>` tag is used to define a paragraph of text.

```html
<p>This is a paragraph of text.</p>
```
#### Line Break

The `<br>` tag is used to insert a single line break.
```html
<p>This is the first line.<br>This is the second line.</p>
```

#### Headers

HTML provides six levels of headings, from `<h1>` to `<h6>`, where `<h1>` is the most important and `<h6>` is the least important.

```html
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
<h3>This is a Heading 3</h3>
<h4>This is a Heading 4</h4>
<h5>This is a Heading 5</h5>
<h6>This is a Heading 6</h6>
```

#### Button

The `<button>` tag creates a clickable button.

```html
<button>Click me</button>
```

#### Anchor

The `<a>` tag is used to create hyperlinks, allowing users to navigate to different pages or sections within the same page.

```html 
<a href="https://www.example.com">Visit Example.com</a>
```

#### Image

The `<img>` tag is used to insert images into a webpage. It is a self-closing tag and requires the `src` attribute to specify the image URL.

```html
<img src="image.jpg" alt="Description of the image">
```



#### Navigation

The `<nav>` tag is used to define a set of navigation links.

```html
<nav>
  <a href="#">Home</a> |
  <a href="#">About</a> |
  <a href="#">Contact</a>
</nav>
```

#### Form

The `<form>` tag is used to create an HTML form for user input.

```html
<form action="/submit-form" method="post">   <!-- Form fields go here --> </form>
```

#### Input

The `<input>` tag is used within a form to accept user input. It has various types like text, radio, checkbox, etc.

```html
<input type="text" placeholder="Enter your name">
<input type="radio" name="gender" value="male"> Male
<input type="checkbox" name="vehicle" value="Bike"> I have a bike
```

#### Label

The `<label>` tag defines a label for an `<input>` element.

```html
<label for="username">Username:</label>
<input type="text" id="username" name="username">
```

#### Select

The `<select>` tag creates a dropdown list.

```html
<select>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```

#### Option

The `<option>` tag defines an option in a `<select>` dropdown list.

```html
<select>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```

#### Video

The `<video>` tag is used to embed video content into a webpage.

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

#### Audio

The `<audio>` tag is used to embed audio content into a webpage.

```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  Your browser does not support the audio element.
</audio>
```

#### Source

The `<source>` tag specifies multiple media resources for `<video>`, `<audio>`, or `<picture>` elements.

```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```


#### Article

The `<article>` tag defines independent, self-contained content.

```html
<article>
  <h2>Article Title</h2>
  <p>Article content goes here.</p>
</article>
```

#### Section

The `<section>` tag defines a section in a document.

```html
<section>
  <h2>Section Title</h2>
  <p>Section content goes here.</p>
</section>
```

#### Aside

The `<aside>` tag defines content aside from the content it is placed in.

```html
<aside>
  <h2>Aside Title</h2>
  <p>Aside content goes here.</p>
</aside>
```

