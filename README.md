# Collectable Colors

![CSS Gradients](https://img.shields.io/badge/CSS-Gradients-663399?style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-Compatible-06B6D4?style=flat-square)
![Themes](https://img.shields.io/badge/Themes-Light%20%2F%20Dark-F59E0B?style=flat-square)

A curated collection of ready-to-use CSS and Tailwind CSS backgrounds.

Explore different visual styles, preview them in context, and copy the exact code you need for your project.

**[Live site →](https://collectable-colors.vercel.app/)** · [Source](https://github.com/itsnazaretdev/collectable-colors)

## ✨ What is Collectable Colors?

Collectable Colors is a visual collection of backgrounds designed to make it easier to find interesting backgrounds for websites, landing pages, portfolios, blogs, dashboards, and other digital projects.

Each background is available in:

- **CSS** — ready to use with the `background` property.
- **Tailwind CSS** — ready to use as an arbitrary `bg-[...]` utility.
- **Light and Dark** variations for every background.

The goal is simple: find a background you like, preview it, and copy it.

## 🔎 Browse

The gallery shows every background in a light and a dark section.

Click a background's **title** to open its own page, where the light and dark versions appear together, side by side.

## 👀 Preview

Click **Preview** on any background to see how it looks when applied to a complete website layout.

The preview includes typical website elements such as:

- Navigation
- Headline
- Supporting text
- Call-to-action
- Footer

This makes it easier to judge the background in context instead of looking at the gradient by itself.

## 📋 Copy CSS

Each background includes its CSS code. Copy the value and add it to any element:

```css
.hero {
  background:
    radial-gradient(
      circle at center,
      rgb(255, 255, 255) 0%,
      rgb(255, 255, 255) 25%,
      transparent 55%
    ),
    #eeeae2;
}
```

## ⚡ Copy Tailwind CSS

If you're using Tailwind CSS, you can copy the provided utility directly:

```html
<section class="bg-[radial-gradient(circle_at_center,rgb(255,255,255)_0%,rgb(255,255,255)_25%,transparent_55%),#eeeae2]">
  ...
</section>
```

The Tailwind version uses an arbitrary value, so no additional configuration is required for the background itself.

## ☀️ Light and 🌙 Dark

Every background is available in both a light and a dark version.

The two versions are designed as visual counterparts rather than simple color inversions. The composition can remain similar while the colors, contrast, and atmosphere change.

Choose the version that fits the overall theme of your website.

## 🛠️ No dependencies required

The backgrounds themselves are standard CSS gradients.

You don't need a background library or JavaScript to use them. The CSS versions can be copied directly into existing projects, while the Tailwind versions work with Tailwind's arbitrary value syntax.

## 📄 License

This project is licensed under the [MIT License](https://github.com/itsnazaretdev/collectable-colors/blob/main/LICENSE).

## ❤️ Made for experimentation

Collectable Colors is intended to make experimenting with visual direction quick and enjoyable.

Find something interesting, try it in your project, change the colors, adjust the gradients, and make it your own.
