# 📘 Class 2 – Links, Images, Lists & More

In this class, we learned **how to connect pages, insert images, and structure content** with HTML.
Let’s go through each new tag one by one.

---

## 1. `<a>` – Anchor Tag (Links)

👉 The `<a>` tag is used to create a **hyperlink**. It connects one page to another page or website.

### Example:

```html
<a href="https://www.google.com/" target="_blank">Google</a>
<a href="/about.html">About Page</a>
```

* `href` → the destination (where the link goes).
* `target="_blank"` → opens the link in a new tab.

🔗 **Analogy**: Think of it like a **door**.

* `href` = where the door leads.
* `target="_blank"` = whether it opens in a **new room** (new tab) or the **same room**.

---

## 2. Internal Links (`#id`)

You can use `id` attributes to jump to a **specific section** on the same page.

### Example:

```html
<a href="#edu">Go to Education</a>
<a href="#exp">Go to Experience</a>
<a href="#">Go to Top</a>

<h2 id="edu">Education Section</h2>
<p>Details about education...</p>

<h2 id="exp">Experience Section</h2>
<p>Details about experience...</p>
```

📖 **Analogy**: Like using a **bookmark inside a book** to jump to a specific chapter.

---

## 3. Navigation Between Pages

You can connect multiple pages together using `<a>`.

### Example:

```html
<!-- index.html -->
<a href="/about.html">About</a>

<!-- about.html -->
<a href="/">Home</a>
```

🏠 **Analogy**: Just like a **menu in a restaurant** helps you move from "Starters" to "Desserts," links help you move from **Home** to **About**.

---

## 4. `<img>` – Image Tag

👉 Displays images on a web page.

### Example:

```html
<img src="doctor.jpg" alt="Doctor Image" width="200" height="200">
```

* `src` → file path of the image.
* `alt` → text shown if the image doesn’t load (also helps accessibility).
* `width` & `height` → size of the image.

🖼️ **Analogy**:

* `src` = the **address of the photo**.
* `alt` = like writing a **caption on the back of a printed photo**.

---

## 5. `<figure>` and `<figcaption>`

👉 Used to group an image with its caption.

### Example:

```html
<figure>
  <img src="doctor.jpg" alt="Doctor Image" width="200">
  <figcaption>Doctor Image</figcaption>
</figure>
```

📷 **Analogy**: Like a **photo in a photo frame** with a **label underneath**.

---

## 6. `<address>`

👉 Used to display contact information such as address, email, or author details.

### Example:

```html
<address>
  Baldia Town, Karachi<br>
  Email: student@example.com
</address>
```

📮 **Analogy**: Like writing your **home address at the end of a letter**.

---

## 7. `<dl>`, `<dt>`, `<dd>` – Description List

👉 Used for terms and their descriptions.

### Example:

```html
<dl>
  <dt>Tea</dt>
  <dd>A hot drink made by infusing dried tea leaves.</dd>

  <dt>Coffee</dt>
  <dd>A drink made from roasted coffee beans.</dd>
</dl>
```

* `<dl>` → description list (container).
* `<dt>` → term (word).
* `<dd>` → description (meaning).

📚 **Analogy**: Like a **dictionary** where:

* Word = `dt`
* Meaning = `dd`

---

## 8. `<ul>` & `<ol>` – Lists

👉 Used to create lists of items.

### Example:

```html
<h3>Unordered List</h3>
<ul>
  <li>Bread</li>
  <li>Butter</li>
  <li>Jam</li>
</ul>

<h3>Ordered List</h3>
<ol>
  <li>Boil water</li>
  <li>Add tea leaves</li>
  <li>Pour into cup</li>
</ol>
```

* `<ul>` → unordered list (bullets).
* `<ol>` → ordered list (numbers).
* `<li>` → list item.

🍔 **Analogy**:

* `<ul>` = a **shopping list** (order doesn’t matter).
* `<ol>` = **recipe steps** (order matters).

---

## 9. `<details>` and `<summary>`

👉 Used to create expandable/collapsible content.

### Example:

```html
<details>
  <summary>Click here for more info</summary>
  <p>This text is hidden until you click above.</p>
</details>
```

* `<summary>` → clickable heading.
* `<details>` → hidden content that shows when clicked.

📂 **Analogy**: Like a **folder** you open to see inside, then close again.

---

## 10. `<progress>`

👉 Displays a progress bar.

### Example:

```html
<label>Downloading:</label>
<progress value="70" max="100"></progress>
```

* `value` = current progress.
* `max` = total.

⏳ **Analogy**: Like a **loading bar** when downloading a file or filling a glass with water until it’s full.

---

# ✅ Summary

In this class, we covered:

1. `<a>` – Anchor links
2. `#id` – Internal links
3. Page navigation
4. `<img>` – Images
5. `<figure>` & `<figcaption>` – Image with caption
6. `<address>` – Contact info
7. `<dl>`, `<dt>`, `<dd>` – Description list
8. `<ul>`, `<ol>`, `<li>` – Lists
9. `<details>` & `<summary>` – Expandable info
10. `<progress>` – Progress bar
