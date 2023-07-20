# Figma-Design
figma design using html css responsive
# Figma Design to HTML/CSS Conversion

![Preview](/Figma-Design/ss.png)

## Introduction
This project is a personal challenge where I converted a Figma design into a responsive website using HTML and CSS. I coded this project alone to practice my frontend development skills and learn more about web design.

## Project Description
The Figma design is a one-page website for a fictional creative agency. It features a modern and clean layout with a hero section, services offered, portfolio section, team members, and a contact form.

### Technologies Used
- HTML
- CSS
- Flexbox
- Media queries for responsiveness

## Preview
![Website Preview](/Figma-Design/ss.png)

## Implementation Details
To create this website, I followed the design closely and made sure to recreate all the elements with precision. I used HTML to structure the content and CSS to style each component. Flexbox was utilized to achieve responsive layouts, ensuring the site looks great on various devices.

### Code Example
Here is a snippet of the CSS code responsible for styling the hero section:

```css
/* Hero Section */
.hero {
  background-image: url('hero-background.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  text-align: center;
  padding: 2rem;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.5rem;
}
