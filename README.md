# Single-Page CV Project

A simple, semantic HTML project to build a one-page CV (Curriculum Vitae) showcasing your education, skills, and career history.

🔗 **Challenge / Project Page:** [https://roadmap.sh/projects/single-page-cv](https://roadmap.sh/projects/single-page-cv)

## 🎯 Project Goal
Create a **single-page HTML CV** using only HTML. This project focuses on structure and semantics — styling with CSS will come later. The aim is to gain a solid understanding of semantic markup and basic SEO principles.

## ✅ Key Requirements
- Use semantic HTML tags to structure your content (e.g., `<header>`, `<section>`, `<footer>`).  
- Include SEO meta tags in the `<head>` (title, description, keywords).  
- Include Open Graph (OG) meta tags.  
- Add a favicon.  
- Include sections:
  - Education  
  - Skills  
  - Work Experience  
- Keep layout strictly **single-page**.

## 📋 Suggested Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
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

  <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Short professional tagline</p>
  </header>

  <section id="education">
    <h2>Education</h2>
  </section>

  <section id="skills">
    <h2>Skills</h2>
  </section>

  <section id="experience">
    <h2>Work Experience</h2>
  </section>

  <footer>
    <p>Contact Information</p>
  </footer>

</body>
</html>
