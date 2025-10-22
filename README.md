# Single-Page CV Project

A simple, semantic HTML project to build a one-page CV (Curriculum Vitae) showcasing your education, skills, and career history.

## 🎯 Project Goal  
Create a **single-page HTML CV** using only HTML. This project focuses on structure and semantics — styling with CSS will come later. The aim is to gain a solid understanding of semantic markup and basic SEO principles.

## ✅ Key Requirements  
- Use semantic HTML tags to structure your content (e.g., `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`).  
- Include basic SEO meta tags in the `<head>` (title, description, keywords).  
- Add Open Graph (OG) tags for better social sharing (e.g., `og:title`, `og:description`, `og:image`).  
- Add a favicon in the `<head>`.  
- Layout should be **single-page**, with distinct sections for:  
  - Education  
  - Skills  
  - Career history (work experience)  
- Make sure the HTML structure is clean, readable, and ready for future styling.

## 📋 Suggested Structure  
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name — CV</title>

  <!-- SEO Meta Tags -->
  <meta name="description" content="Curriculum Vitae of Your Name — Skills, Education & Work Experience">
  <meta name="keywords" content="Your Name, CV, Resume, Skills, Education, Work Experience">

  <!-- Open Graph Meta Tags -->
  <meta property="og:title" content="Your Name — CV">
  <meta property="og:description" content="Explore the education, skills and career history of Your Name">
  <meta property="og:image" content="url-to-image.jpg">
  <meta property="og:type" content="website">

  <!-- Favicon -->
  <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Brief tagline or summary</p>
  </header>

  <nav>
    <!-- optional, could link to section IDs -->
  </nav>

  <section id="education">
    <h2>Education</h2>
    <!-- List education items -->
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <!-- List skill categories -->
  </section>

  <section id="experience">
    <h2>Work Experience</h2>
    <!-- List career history items -->
  </section>

  <footer>
    <p>Contact details & perhaps links to portfolio / LinkedIn / GitHub</p>
  </footer>

</body>
</html>
