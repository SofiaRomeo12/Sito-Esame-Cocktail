# Carousel JS Library

## Description
A lightweight JavaScript carousel library for smooth animations, touch interactions, and easy slide management. Fast, customizable, and simple to integrate into any web project.

## Features
- Easy to use
- Lightweight and fast
- No dependencies (vanilla JS)
- Compatible with all browsers
- Responsive

## Installation

### IMPORT JAVASCRIPT LIB (required)
```html
<script src="https://cdn.jsdelivr.net/npm/carousel-javascript-library-stable-v/core.min.js"></script>
```

### IMPORT CSS (required)
```html
<link href="https://cdn.jsdelivr.net/npm/carousel-javascript-library-stable-v/core.min.css" rel="stylesheet">
```

### CSS (optional)
You can customize the component using its CSS classes, such as:
`.carousel-card`, `.set`, `.scroll-track`, `.carousel-wrap`, etc.

## Usage

### HTML
The following HTML structure defines an infinite horizontal carousel with duplicated content sets for seamless looping.
```html
<div class="carousel-wrap">
    <div class="scroll-track" id="track-1">
        <div class="set">
            <a href="#" class="carousel-card">
                <img src="#" alt="" />
                <!-- your content -->
            </a>

            <a href="#" class="carousel-card">
                <img src="#" alt="" />
                <!-- your content -->
            </a>
        
            <a href="#" class="carousel-card">
                <img src="#" alt="" />
                <!-- your content -->
            </a>
        </div>

        <div class="set">
            <a href="#" class="carousel-card">
                <img src="#" alt="" />
                <!-- your content -->
            </a>

            <a href="#" class="carousel-card">
                <img src="#" alt="" />
                <!-- your content -->
            </a>

            <a href="#" class="carousel-card">
                <img src="#" alt="" />
                <!-- your content -->
            </a>
        </div>
    </div>
</div>

NOTE: 
You can add more sets by reusing the same structure.
You can add more carousels by reusing the same structure and incrementing the ID values.
```

This HTML structure defines a custom horizontal scrollbar designed to visually track and enhance carousel navigation.
```html
<div class="custom-scrollbar-container">
    <div class="custom-scrollbar-thumb" id="thumb-1"></div>
</div>
```

## Requirements
- Modern browsers (Chrome, Firefox, Safari, Edge)
- No external dependencies

## Support
For issues or questions, open an issue on GitHub.

## Contributing
Contributions are welcome! Feel free to open pull requests.

## License
MIT License - see LICENSE file for details.

## Author
Tyler Dawson