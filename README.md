# CSS Splash Illusion — Perception Over Physics

A visual case study exploring how far CSS can go in creating the feeling of realism — without pretending to simulate physics.

Tagline:
When realism is required, CSS shouldn’t fake it — it should enhance it.

## Project Idea

Water splash visuals are often credited to “CSS tricks”.
In reality, CSS excels at illusion, motion, and depth, not physical simulation.
This project explores that boundary by building a product hero section using:
A CSS-only illusion layer
A hybrid image + CSS enhancement
Clear documentation of where CSS stops being the right tool

## Goals

Create a visually compelling hero section without WebGL or Canvas
Demonstrate technical honesty about CSS limitations
Show how real-world teams combine assets + CSS
Prioritize perception, performance, and accessibility

## What This Project Includes
1. CSS Illusion Layer

Radial gradients to simulate light and water glow
Blur and opacity for depth
Subtle motion to avoid distraction

2. Hybrid Image Approach (Production-Ready)

A real splash image used as a base
CSS used for:
Motion
Scaling
Layering
Responsive behavior

3. Intentional Constraints

No JavaScript
No Canvas
No WebGL
No fake “CSS water physics”

## Technical Highlights

CSS custom properties (design tokens)
Layered composition with z-index
object-fit: cover for full-bleed imagery
Subtle motion using @keyframes
Clean, semantic HTML structure
Performance-friendly animations

 ## Design Decisions
 
Why blue-cyan?
The background palette is intentionally chosen for its psychological effect:
Calm and non-aggressive
Associated with trust and refreshment
Common in healthcare and wellness interfaces
Reduces visual fatigue
This aligns with the project’s goal: calm motion, not visual noise.

## Accessibility Considerations

Motion is subtle and non-essential
Content remains readable without animation
Visual hierarchy is preserved without relying on effects
(Reduced-motion support can be added without redesigning the system.)

## Interview-Ready Explanation

“I didn’t try to recreate water physics in CSS.
I focused on perception — light, depth, and motion — the things CSS does well.
When realism is required, I use a hybrid approach instead of forcing CSS to fake it.”

## Project Structure
css-splash-illusion/
│
├── index.html
├── styles/
│   └── main.css
├── assets/
│   ├── splash-img.avif
│   └── pepsi-can.png
└── README.md
