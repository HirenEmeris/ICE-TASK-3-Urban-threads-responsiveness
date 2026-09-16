# WEDE5020 — ICE Task 3
## Urban Threads: Responsive Web Design

### 📱 Learning Unit 5 — Responsive Web Design


## 🎯 Overview

In this ICE task, you will work with the **Urban Threads** clothing store website.

The website has been designed to work well on larger screens, but it contains layout problems when the browser window becomes smaller.

Your task is to use the **responsive web design techniques covered in LU5** to identify and fix these problems using CSS.

> **Important:** You are not creating the website from scratch. Start with the provided Urban Threads project and focus on understanding and improving the CSS.


## 📝 What You Need to Do

Follow these steps:

1. Open the **Urban Threads** starter project in VS Code.
2. Open `index.html` in your browser.
3. Resize the browser window to a smaller size.
4. Identify at least **three problems** with the layout.
5. Add a media query to your `styles.css`.
6. Use responsive CSS to fix the layout for smaller screens.
7. Test your website again by resizing the browser.
8. Write a short explanation of the changes you made and why they work.


## 🔎 Step 1: Investigate the Problems

Before changing your CSS, carefully investigate what happens when the browser becomes smaller.

Look for problems such as:

- The header or navigation becoming crowded.
- Content becoming wider than the screen.
- The hero section becoming difficult to use.
- Product cards remaining in one long row.
- Horizontal scrolling being required.
- The CTA section or footer not fitting comfortably on a small screen.

### 💡 Think First!

**Identify the problem before changing the CSS.**

Ask yourself:

> What is causing this problem, and what CSS change could solve it?



## 📱 Step 2: Add Responsive CSS

Add your responsive CSS to the **bottom of `styles.css`** using a media query.


@media screen and (max-width: 768px) {
    /* Your responsive rules go here */
}
