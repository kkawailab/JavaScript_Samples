# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a collection of interactive web applications built with vanilla JavaScript, HTML5, and CSS3. Each application is self-contained in a single HTML file with embedded styles and scripts, making them easy to run and understand.

## Key Applications

1. **clock-app.html** - Digital/analog clock with Japanese date display
2. **omikuji-app.html** - Japanese fortune-telling app with animations  
3. **quiz-app.html** - 3-choice quiz app with score tracking

## Development Guidelines

### Code Structure
- Each app is a single HTML file with embedded CSS and JavaScript
- No external dependencies or frameworks - pure vanilla JavaScript only
- All code includes detailed Japanese comments for learning purposes
- Uses modern ES6+ features (const/let, arrow functions, template literals)

### Design Principles
- Responsive design using flexbox and media queries
- Smooth animations and transitions for better UX
- Gradient backgrounds and glassmorphism effects
- Mobile-first approach with breakpoints at 768px and below

### Running Applications
Simply open any HTML file in a modern web browser. No build process or server required.

## Common Patterns

### Animation Classes
Apps use CSS animations with JavaScript class toggling:
- `.show` for fade-in effects
- `.shaking` for shake animations (omikuji)
- Transform-based hover effects

### Event Handling
- Click events for user interactions
- setInterval for real-time updates (clock)
- setTimeout for delayed actions

### Japanese Localization
- Uses `toLocaleDateString('ja-JP')` for date formatting
- Japanese text throughout UI elements
- UTF-8 encoding for proper character display