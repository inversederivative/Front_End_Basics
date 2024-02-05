
HTML attributes provide additional information about HTML elements. Let's explore some commonly used attributes:

#### Name vs Value

In HTML attributes, there is a distinction between the attribute name and its value. For example, in the `<img>` tag, `src` is the attribute name, and `"http://google.com"` is its value.

```html
<img src="http://example.com/image.jpg" alt="Description">
```

#### Source

The `src` attribute specifies the URL of the media resource, such as an image, audio, or video file.

```html
<img src="image.jpg" alt="Description">
<video src="video.mp4" controls></video>
<audio src="audio.mp3" controls></audio>
```

#### Hyperlink Reference

The `href` attribute specifies the URL of the linked resource in anchor elements (`<a>`), creating hyperlinks.

```html
<a href="http://example.com">Visit Example.com</a>
```

### ID and Class

The `id` attribute specifies a unique identifier for an HTML element, while the `class` attribute defines one or more classes for an element, allowing styling and JavaScript targeting.

See [[Classes and IDs]] for more on the subject.

```html
<div id="header">Header</div>
<p class="highlight">Highlighted text</p>
```

#### For

The `for` attribute associates a label with an input element. It specifies which form element a label is bound to.

```html
<label for="username">Username:</label>
<input type="text" id="username" name="username">
```

#### Type

The `type` attribute specifies the type of input element, button, or link.

```html
<input type="text">
<button type="submit">Submit</button>
<a href="#" type="button">Click me</a>
```

#### Value

The `value` attribute specifies the initial value of an input element or the value submitted with the form.

```html
<input type="text" value="Default Text">
<input type="checkbox" value="yes">
<option value="volvo">Volvo</option>
```

#### Video Attributes

Attributes like `muted`, `autoplay`, `loop`, and `controls` are used with the `<video>` tag to specify various video playback options.

```html
 <video src="video.mp4" muted autoplay loop controls></video>
```

---

