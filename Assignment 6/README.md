# my page


Hello! This is my personal space where you'll get to know more about who I am, my hobbies, and what I enjoy doing in my free time.

## How are you feeling regarding the skills you've practiced so far?

I feel confident and excited about the skills I have practiced so far. Building the web page structure and applying styles using HTML and CSS is becoming much more intuitive, and it is rewarding to see the visual results of my code.

## Is there anything you'd like more clarification on and/or to practice? 

I would like to continue practicing and developing my core HTML and CSS skills to build more advanced layouts. Additionally, I am very curious about responsive web design and would love to learn how to make pages adapt perfectly to different screen sizes and devices.

## How did using components and classes affect the way you organized your webpage?

Using components and classes allowed me to organize my HTML and CSS code in a much better and more professional way. Instead of repeating or scattering code, I was able to group related elements inside <div> containers and label them with clear classes (like the hero and cards). This made it much easier to target and style them all at once using CSS, while keeping the files clean and well-structured.

## Is there anything from this week's HTML or CSS that you'd like more clarification on and/or more practice with?

I would like to get more practice with advanced CSS layout properties to control how elements are arranged side-by-side responsively, such as using display: inline-block and fine-tuning margins and spacing between different components so they look consistent across all screens.

# Assignment 4 - Reflection & Design Document

## Visual Appeal
1. **Which icons did you ultimately use and for what purposes?**
   I used six custom-designed icons: Home, Search, Mail, Paintbrush, Star, and Document. The Home and Search icons enhance site navigation, the Mail icon supports the contact form, and the Paintbrush, Star, and Document icons visually represent my creative arts, personal interests, and technical project portfolio.

2. **Which consistent colors, values, lines, and/or shapes did you utilize and why?**
   I utilized clean lines, consistent geometric shapes, and a unified, soft color palette (soft browns, beiges, and muted greens) to maintain a cohesive artistic and professional identity across all components.

3. **Which Google Fonts did you use and for what purposes?**
   I used a clean sans-serif Google Font for body paragraphs to ensure maximum legibility and readability, paired with a distinct heading font to create visual hierarchy and add a polished, professional touch to titles.

## Structure & Organization
4. **What information does your table organize, and why was a table appropriate?**
   The table organizes my technical skills and project metrics, providing a structured, grid-based layout that makes dense information easy to scan and compare.

5. **What specific style choices helped you structure and organize your form?**
   Using `.form-v2` as a container with padding, background color, block-level labels, and styled inputs/select elements helped create clear visual groupings, spacing, and form structure.

## Design Goals
6. **What is the goal of your form, and how did it support your site's goals?**
   The form's goal is to allow visitors or potential collaborators to easily get in touch, providing an interactive channel that directly supports my portfolio's objective of professional networking.

7. **How does the gallery support your website's goals?**
   The CSS Flexbox gallery visually showcases my creative works, digital designs, and multimedia projects, reinforcing my skills in Media Arts and web design.

8. **What pattern did you use: uniform, alternating, or something else, and why?**
   I used a uniform repeating pattern across my card groups and gallery items to create visual predictability and rhythm, making the layout look organized and balanced.

## Checking In
- **Learning about and applying design principles:** I feel confident applying hierarchy, alignment, and consistency to bring order to layouts.
- **Using typography in your designs:** Pairing Google Fonts effectively helped shape the site's tone and readability.
- **Creating components (like navs, cards, galleries, forms, buttons, and tables):** Building modular components made structuring and scaling the website much easier.
- **Exploring display: flex;:** Flexbox provided a predictable and powerful way to arrange responsive layouts like the image gallery.


## Component Plan: Interactive Art & Nature Gallery Grid

### 1. Purpose of the Component
This component is designed to showcase my favorite art pieces and nature drawings in a clean, organized, and responsive multi-column layout. It helps users easily browse different artworks.

### 2. Layout Strategy (CSS Grid)
- **Grid Structure:** I will use CSS Grid (`display: grid;`) to create a 3-column layout (`grid-template-columns: 1fr 1fr 1fr;`) for desktop screens.
- **Spacing:** I'll apply a `gap: 20px;` to maintain a balanced and airy layout between the art cards.
- **Responsiveness:** Using media queries, the columns will adjust to 2 columns on tablets and a single column on mobile screens to ensure perfect readability.

### 3. Visual & Aesthetic Choices
- **Colors:** Utilizing the warm, natural palette (`#F9F7F1` background with `#2A1916` text and `#FFCDA1` accents).
- **Cards:** Each card will include a styled image, title, and artist/description with subtle border-radius and clean padding to match the personal art portfolio vibe.

## Reflection Questions

### 1. What did you create or organize this week that you think will be most useful in future websites? Why?
Creating the centralized `ComponentLibrary` folder and organizing the media assets was the most useful step. Having a dedicated library for reusable components like cards, custom drop caps, and navigation elements means I don't have to rebuild them from scratch for future projects, saving time and ensuring design consistency.

### 2. How did working with reusable components affect the way you approached your design this week?
Working with reusable components made me think more holistically about the website's structure and brand identity. Instead of styling each page in isolation, I focused on creating unified patterns—like consistent color contrast, clean typography, and matching graphical motifs—which made the overall user experience much smoother and more professional.