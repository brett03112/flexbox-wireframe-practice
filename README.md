# Flexbox Wireframe Practice

## Project Overview

This project demonstrates the implementation of a responsive wireframe layout using CSS Flexbox. It recreates a common application structure with a header, content area, aside section, and footer that adapts from mobile to desktop layouts.

## Technologies Used

- HTML5
- CSS3 (with Flexbox)
- Mobile-first responsive design
- Media queries for responsive breakpoints

## Project Structure

The project consists of the following key files:

- `index.html`: Contains the semantic HTML structure
- `css/style.css`: Contains the custom styling with Flexbox implementation
- `css/reset.css`: Provides a consistent baseline across browsers
- `mobile-wireframe.png`: The reference design that was implemented
- `desktop-wireframe.png`: The reference design for a desktop layout using media queries

## Implementation Details

The layout follows a mobile-first approach with the following components:

1. **Header (Purple)**: Top navigation area
2. **Main Content (Green)**: Container for the three article sections
3. **Articles (Pink)**: Three content blocks stacked vertically
4. **Aside (Blue)**: Secondary content area
5. **Footer (Orange)**: Bottom section of the page

## CSS Features

- Flexbox for layout management
- Consistent spacing with equal margins and padding
- Mobile-optimized viewport settings
- Proper touch target sizes for interactive elements
- Consistent color scheme matching the wireframe
- Rounded corners on all elements

## Mobile Optimization

The layout is specifically designed for mobile devices with:

- Appropriate text sizes for mobile screens
- Prevention of horizontal scrolling
- Optimized spacing for smaller screens
- Non-scalable viewport to prevent unwanted zooming

## Desktop Optimization

The layout adapts to desktop screens (min-width: 768px) with:

- Two-column layout for main content and aside sections
- Reordered elements using Flexbox order property
- Proportional widths (68% for main content, 28% for aside)
- Equal height for main content and aside sections
- Consistent spacing between all elements

## Learning Outcomes

This project demonstrates:

- How to structure a responsive layout using semantic HTML
- Effective use of Flexbox for responsive layouts
- Implementation of a design from wireframe references
- Consistent spacing and styling across components
- Mobile-first design principles
- Using media queries to create responsive breakpoints
- Adapting layouts for different screen sizes
