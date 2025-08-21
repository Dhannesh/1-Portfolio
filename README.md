# 🌐 HTML5 Portfolio Assignment

## 🎯 Objective

Build a **personal portfolio webpage** using **HTML5 tags**.  
This will help you practice semantic HTML and create a simple one-page portfolio.

---

## 📝 Requirements

Your `index.html` must include:

### 1. Document Structure

- Correct usage of `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`.

### 2. Semantic Sections

- `<header>` → Your **name** and a tagline.
- `<nav>` → Navigation with at least **3 links**.
- `<main>` → Main content area.
- `<footer>` → Your name + copyright.

### 3. Content

- At least one heading (`<h1>` or `<h2>`).
- At least **two paragraphs** (`<p>`) about yourself.
- At least **one list** (`<ul>` or `<ol>`) with **3 skills**.
- At least one **image** (`<img>`).
- A **table** (`<table>`) for projects, education, or work experience.
- A **contact form** with:
  - One text input (`name`).
  - One email input.
  - One submit button.

---

## 📂 Starter Code

Use this as a base:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
  </head>
  <body>
    <header>
      <h1>Student Name</h1>
      <p>Aspiring Web Developer</p>
    </header>

    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <main>
      <section id="about">
        <h2>About Me</h2>
        <p>Write a short bio here.</p>
        <p>Highlight your interests, goals, and experience.</p>
      </section>

      <section id="skills">
        <h2>My Skills</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
        </ul>
      </section>

      <section id="projects">
        <h2>Projects</h2>
        <table border="1">
          <tr>
            <th>Project</th>
            <th>Description</th>
          </tr>
          <tr>
            <td>Portfolio</td>
            <td>A personal portfolio website.</td>
          </tr>
        </table>
      </section>

      <section id="contact">
        <h2>Contact Me</h2>
        <form>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" /><br /><br />

          <label for="email">Email:</label>
          <input type="email" id="email" name="email" /><br /><br />

          <button type="submit">Send</button>
        </form>
      </section>
    </main>

    <footer>
      <p>Created by Student Name &copy; 2025</p>
    </footer>
  </body>
</html>
```
