# D3 Term 2 - MDIA-2109

### Welcome to Shana's Repo

Dynamic Content Design - Winter 2026

    This repo is for lab exercises and assignments

```
        \ | /
      '-.;;;.-'
     -==;;;;;==-
      .-';;;'-.
        / | \
          |
      \   |   /
       '. | .'
         \|/
      .-*****-.
   .-' ******* '-.
  / ************* \
 | *************** |
  \ ************* /
   '-. ******* .-'
      '-*****-'
```

<br>

## 🛒 Semester Project: Online Marketplace App

My semester project is an **online marketplace application**. I am working with my teammates **Tommy** and **Jason**.

- **Tommy** will focus on the interactive components and animations, such as hover effects, micro‑interactions, and animated transitions that enhance user engagement.

- **Jason** will focus on the navigation system, including the header, menu behavior, responsive nav patterns, and ensuring smooth movement between pages.

<br>

## 🎯 My Individual Focus: Responsive Product‑Card Grid Layout

My personal focus for this project is to design and **implement the responsive product‑card grid layout** that will serve as the core browsing experience of the marketplace. This adds direct value because the product grid is the first thing every user sees, making it essential for both usability and overall engagement.

I will be building a robust, extensible layout foundation that must handle:

- dynamic product data

- inconsistent image sizes

- variable card heights

- sale badges, ratings, and tags

- wishlist and quick‑view interactions

- hover states and micro‑interactions

- accessibility requirements

<br>

## 🛠️ Action Plan for Implementation

### 📚 What I Need to Study

To implement this properly, I will study:

1. Media queries for clean breakpoints

2. Mobile‑first CSS to establish a strong accessibility baseline

3. Reusable class patterns and naming conventions

4. CSS Grid + Flexbox for complex card arrangements

5. Aspect‑ratio and object‑fit for image consistency

6. Progressive enhancement for larger screens

7. Readable, maintainable CSS architecture

These topics align with my learning plan, which focuses on mastering responsive design, clean code structure, and scalable front‑end development.

### 🧱 Steps for Implementation

> **_Define the mobile baseline_**  
> Build a single‑column layout with consistent spacing, readable text, and accessible tap targets.

> **_Create reusable class structures_**  
> Use utility classes and consistent naming to avoid duplication and keep the CSS maintainable.

> **_Build tablet and desktop breakpoints_**  
> Introduce multi‑column grids, hover states, and richer product information while keeping the core layout identical across devices.

> **_Handle dynamic content early_**  
> Test with long product names, sale badges, ratings, and inconsistent image sizes to ensure the grid remains stable.

> **_Prepare for future features_**  
> Ensure the layout can support filtering, sorting, wishlist icons, and lazy‑loaded images without breaking.

> **_Test across real devices_**  
> Check phones, tablets, laptops, and large monitors to ensure consistent behavior.

> **_Iterate and refine_**  
> Adjust spacing, typography, and card behavior as the team adds new features.

### ⚠️ Fears, Uncertainty, and Doubt (FUD) — and How I’ll Address Them

> **_Fear:_** The layout will break when dynamic content is added
> **_Strategy_**: Use flexible units, CSS Grid’s minmax(), and test with extreme content early.

> **_Uncertainty_**: Managing many reusable classes without confusion  
> **_Strategy_**: Follow a consistent naming convention and document class purposes.

> **_Doubt:_** Ensuring equal experience across all devices  
> **_Strategy_**: Use mobile‑first design and progressive enhancement so all devices share the same core experience.

> **_Fear:_** Media queries becoming messy or duplicated  
> **_Strategy:_** Centralize breakpoints and group related layout logic.

> **_Uncertainty:_** Handling inconsistent product images  
> **_Strategy:_** Use aspect-ratio, object-fit, and container rules to prevent layout shifts.
