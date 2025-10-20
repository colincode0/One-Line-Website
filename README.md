# Base64 Obfuscated Website

A single-page website that demonstrates code obfuscation through Base64 encoding. The entire website content is hidden within a single Base64 string, creating a digital sleight of hand.

## How It Works

The `index.html` file contains only a few lines of code and a massive Base64 string. When opened in a browser, JavaScript decodes this string to render a complete website about obfuscation techniques.

```html
<script>
  document.write(atob("...massive base64 string..."));
</script>
```

## What You'll See

- **Source Code**: A minimal HTML file with what appears to be random characters
- **Rendered Website**: A complete, interactive website with:
  - Black and white Apple-inspired design
  - Subtle 3D breathing animations
  - Terminal-style code blocks
  - Educational content about obfuscation techniques

## The Art of Digital Camouflage

This project explores the boundary between readable and unreadable code, demonstrating how:

- **Steganography**: Messages can be concealed within seemingly innocent content
- **Art**: Programming can become a form of digital art
- **Curiosity**: The most interesting discoveries come from looking beyond what's immediately visible
- **Creativity**: Code obfuscation transforms programming into digital craftsmanship

## Technical Details

- Pure HTML/CSS/JavaScript (no external dependencies)
- Base64 encoding for content obfuscation
- CSS animations for subtle 3D effects
- Responsive design
- Terminal-inspired aesthetics

## View the Site

Simply open `index.html` in any modern web browser to see the obfuscation in action.

---

_Sometimes the most interesting things are hidden in plain sight._
