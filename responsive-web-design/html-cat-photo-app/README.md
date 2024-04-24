# Responsive Web Design

# **Learn HTML by Building a Cat Photo App**

## [Live Preview](https://raw.githack.com/codem1ner/free-code-camp/main/responsive-web-design/html-cat-photo-app/responsive-web-design.html)

## Main Section

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CatPhotoApp</title>
  </head>
  <body>
    <main>
      <section></section>
      <!-- Section 1: Cat Photos -->
      <section></section>
      <!-- Section 2: Cat Information Lists -->
      <section></section>
      <!-- Section 3: Cat Photo URL Submission Form -->
    </main>
    <footer></footer>
  </body>
</html>
```

## Section 1: Cat Photos

```html
<section>
  <!-- Section 1: Cat Photos -->
  <h2>Cat Photos</h2>

  <p>
    See more  <a target="_blank" href="https://freecatphotoapp.com"
      >cat photos</a
    >
     in our gallery.
  </p>

  <a href="https://freecatphotoapp.com">
    <img
      src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg"
      alt="A cute orange cat lying on its back"
    />
  </a>
</section>
```

- `<section>`: Defines a logical section within an HTML document.

## Section 2: Cat Information Lists

```html
<section>
  <h2>Cat Lists</h2>

  <h3>Things cats love:</h3>
  <ul>
     
    <li>cat nip</li>
     
    <li>laser pointers</li>
     
    <li>lasagna</li>
  </ul>

  <figure>
     <img
      src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg"
      alt="A slice of lasagna on a plate"
    />
     
    <figcaption>Cats <em>love</em> lasagna.</figcaption>
  </figure>

  <h3>Top 3 things cats hate:</h3>
  <ol>
     
    <li>flea treatment</li>
     
    <li>thunder</li>
     
    <li>other cats</li>
  </ol>

  <figure>
     <img
      src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"
      alt="Five cats looking around a field"
    />
     
    <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
  </figure>
</section>
```

## Section 3: Cat Photo URL Submission Form

```html
<section>
  <h2>Cat Form</h2>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
     
    <fieldset>
      <legend>Is your cat an indoor or outdoor cat?</legend>
      <label
        >Indoor  <input
          id="indoor"
          type="radio"
          name="indoor-outdoor"
          value="indoor"
          checked
        />
      </label>
      <label
        >Outdoor  <input
          id="outdoor"
          type="radio"
          name="indoor-outdoor"
          value="outdoor"
        />
      </label>
       
    </fieldset>
  </form>
</section>
```
