# Responsive Laundry Service Landing Page

A simple responsive landing page built using **HTML5** and **CSS3** without Bootstrap.

## Features

- Responsive navigation bar
- Mobile hamburger menu
- User information remains visible on mobile devices
- Responsive hero section
- Smooth button animation
- Clean and modern layout
- No external CSS frameworks used

## Project Structure


project/
│
├── index.html
├── style.css
└── README.md


## Technologies Used

- HTML5
- CSS3
- Flexbox
- Media Queries

## Responsive Design

The layout automatically adapts to different screen sizes:

### Desktop
- Navigation links displayed horizontally
- Hero content and image displayed side by side

### Mobile
- Navigation links hidden inside hamburger menu
- User information remains visible
- Hero section stacks vertically
- Images scale automatically

## Navigation Menu

The mobile menu uses the CSS Checkbox Hack:

```html
<input type="checkbox" id="menu-toggle">
<label for="menu-toggle" class="hamburger">&#9776;</label>
