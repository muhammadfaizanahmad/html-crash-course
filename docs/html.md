# HTML Crash Course

## 1. Document Type Declaration

The `<!DOCTYPE html>` declaration is used to define the document type and version of HTML being used. In modern web development, this declaration specifies that the document is an HTML5 document.

## 2. HTML Tag and Language Declaration

The `<html lang="en">` tag is the root element of the HTML document. The `lang` attribute specifies the language of the document, which is important for accessibility and search engines.

## 3. Head Tag

The `<head>` element contains meta-information about the HTML document, such as its title, character set, and viewport settings.

### 3.1 Character Set Declaration

The `<meta charset="UTF-8">` tag defines the character encoding for the HTML document. UTF-8 stands for "Unicode Transformation Format - 8-bit."

### 3.2 Viewport Settings for Responsive Design

The `<meta name="viewport" content="width=device-width, initial-scale=1.0">` tag specifies how the page should be displayed on mobile devices, setting the width of the page to the device's screen-width and the initial zoom level.

### 3.3 Other Meta Tags

- **Description**: Provides a brief description of the page, which search engines can use as a snippet in search results.
- **Keywords**: Specifies a list of keywords about the page (largely ignored by modern search engines).
- **Author**: Specifies the author of the document.
- **Refresh**: Sets a time after which the page will be reloaded or redirected to another URL.
- **Robots**: Controls how search engine crawlers should index the page or follow links.

## 4. Title Tag

The `<title>` element sets the title of the HTML document, which appears in the browser's title bar or tab.

## 5. Body Tag

The `<body>` element contains the content of the HTML document, including text, images, links, forms, and other elements that are visible to the user.

### 5.1 Headings and Paragraphs

- **Headings**: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, and `<h6>` tags represent different levels of headings.
- **Paragraphs**: The `<p>` tag defines a paragraph of text.

### 5.2 Ordered and Unordered Lists

- **Ordered List**: The `<ol>` tag creates a numbered list.
- **Unordered List**: The `<ul>` tag creates a bulleted list.

### 5.3 Anchor Tag

The `<a>` tag is used to create hyperlinks, which allow users to navigate from one page to another.

### 5.4 Image Tag

The `<img>` tag is used to embed images in the HTML document. The `src` attribute specifies the image source, and the `alt` attribute provides alternative text for the image.

### 5.5 Div and Span Tags

- **Div Tag**: The `<div>` tag is used as a container for other HTML elements. It is a block-level element.
- **Span Tag**: The `<span>` tag is used to group inline elements in a document.

### 5.6 Form Element

The `<form>` element is used to create an HTML form for user input.

#### 5.6.1 Label Tag

The `<label>` tag defines a label for an input element. The `for` attribute links the label to the corresponding input field.

#### 5.6.2 Form Controls

Form controls are interactive elements within a form that allow users to input data or select options, such as:

- **Text Input**: `<input type="text">` for single-line text input.
- **Password Input**: `<input type="password">` for password input, which hides the entered characters.
- **Text Area**: `<textarea>` for multi-line text input.
- **Radio Buttons**: `<input type="radio">` for selecting one option from a group.
- **Checkboxes**: `<input type="checkbox">` for selecting one or more options from a set.
- **Drop-down Lists**: `<select>` with `<option>` elements for selecting from a list of options.
- **Buttons**: `<button>`, `<input type="submit">`, `<input type="reset">`, etc., for form submission or resetting.
- **File Input**: `<input type="file">` for uploading files.
- **Hidden Input**: `<input type="hidden">` for data that is not visible to the user but is sent with the form submission.
- **Date and Time Input**: `<input type="date">`, `<input type="time">`, etc., for selecting dates and times.

#### 5.6.3 ID, Name, and Value Attributes

- **ID**: A unique identifier for the input field.
- **Name**: Specifies the name of the input field for form submission.
- **Value**: Sets the initial value of the input field.

### 5.7 Semantic HTML Tags (HTML5)

Semantic HTML tags like `<header>`, `<footer>`, `<article>`, `<section>`, `<aside>`, and `<nav>` provide meaning to the structure of the HTML document.

### 5.8 Audio and Video Tags

- **Audio Tag**: The `<audio>` element is used to embed audio content.
- **Video Tag**: The `<video>` element is used to embed video content.

### 5.9 Embed YouTube Video

The `<iframe>` tag is used to embed an external webpage, such as a YouTube video, into the HTML document.
