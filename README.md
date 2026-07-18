# 10th Anniversary Interactive Keepsake Card

A beautifully designed, highly responsive interactive digital anniversary card created to celebrate a decade of marriage. This project functions as both a meaningful personal gift and a production-ready component for a frontend developer portfolio, demonstrating clean UI/UX layout design, dynamic DOM manipulation, and smooth asset management.

## 🎨 Visual Identity & Styling
The design pivots away from standard themes to feature a highly custom, modern romance aesthetic:
*   **Base Color:** Deep, rich reddish-purple (`#6b1d3f`) to provide a luxurious, warm backdrop.
*   **Highlights:** Clean, structured silver accents (`#b0b7bd`) combined with active soft-silver box shadows to mimic a realistic metallic sheen/glow.
*   **Typography:** Balanced editorial look utilizing classic serif stylings (`Georgia`) to give the narrative copy an elegant, classic feel.

## ✨ Features
*   **Fixed-Height Viewport Slideshow:** Photos are safely constrained inside a custom `380px` frame. The CSS utilizes `object-fit: cover` to ensure that mixed aspect-ratio or orientation images dynamically adapt without stretching or distorting.
*   **Fluid JavaScript Controls:** Native JS event handling hooks into the UI to allow seamless forward/backward navigation using custom metallic arrow buttons or direct selection via timeline tracking dots.
*   **Zero-Dependency Design:** Built completely using vanilla HTML5, CSS3, and JavaScript—meaning absolute optimization, fast load times, and no external library overhead.
*   **Mobile-First Design Structure:** Responsive elements handle display scaling automatically, providing an authentic app-like card experience on mobile devices while remaining perfectly centered on desktop screens.

## 📁 Project Structure
```text
anniversary-card/
├── images/
│   ├── photo1.jpg       # Anniversary Image 1
│   ├── photo2.jpg       # Anniversary Image 2
│   ├── photo3.jpg       # Anniversary Image 3
│   ├── photo4.jpg       # Anniversary Image 4
│   └── photo5.jpg       # Anniversary Image 5
└── index.html           # Main entry point (HTML, CSS, & JS logic)
