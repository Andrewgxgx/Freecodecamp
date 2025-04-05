
source code
- The Nesting in The html document work, should still render correctly
```html

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="utf-8">

<title>CatPhotoApp</title>

</head>

<body>

<main>

<h1>CatPhotoApp</h1>

<section>

<h2>Cat Photos</h2>

<p>Everyone loves <a href="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg">cute cats</a> online!</p>

<p>See more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>

<a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>

</section>

<section>

<h2>Cat Lists</h2>

<h3>Things cats love:</h3>

<ul>

<li>catnip</li>

<li>laser pointers</li>

<li>lasagna</li>

</ul>

<figure>

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">

<figcaption>Cats <em>love</em> lasagna.</figcaption>

</figure>

<h3>Top 3 things cats hate:</h3>

<ol>

<li>flea treatment</li>

<li>thunder</li>

<li>other cats</li>

</ol>

<figure>

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">

<figcaption>Cats <strong>hate</strong> other cats.</figcaption>

</figure>

</section>

</main>

<footer>

<p>

No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>

</p>

</footer>

</body>

</html>

```


* The `figure` element represents self-contained content and will allow you to associate an image with a caption.
	- A figure caption (`figcaption`) element is used to add a caption to describe the image contained within the `figure` element.
	- Example:
```html
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
```

- To place emphasis on a specific word or phrase, you can use the `em` element.
- The `strong` element is used to indicate that some text is of strong importance or urgent.
	- aka make word bold

- The `footer` element is used to define a footer for a document or section. A footer typically contains information about the author of the document, copyright data, links to terms of use, contact information, and more.
- The `head` element is used to contain metadata about the document, such as its title, links to stylesheets, and scripts. Metadata is information about the page that isn't displayed directly on the page.

- The `title` element determines what browsers show in the title bar or tab for the page.


- specify language of the page by adding lang to `<html>`
```html
<html lang='en'>
```


- All pages should begin with `<!DOCTYPE html>`. This special string is known as a declaration and ensures the browser tries to meet industry-wide specifications.

- You can set browser behavior by adding `meta` elements in the `head`.






