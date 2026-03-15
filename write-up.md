# CSS Module Assignment: Personal Resume Redesign

**GitHub Repository:** [https://github.com/aryanpruthi07/Aryan-Resume](https://github.com/aryanpruthi07/Aryan-Resume)

## Summary of CSS Improvements

For this assignment, I completely overhauled my basic HTML resume into a modern, responsive styled portfolio by applying various advanced CSS layout concepts. Here are the specific techniques and enhancements:

### 1. Custom Google Fonts
- Integrated the **"Inter"** Google font (`@import url(...)`) across the site to replace the default browser typography. Used multiple font weights (300 to 800) to create a visual hierarchy between headings and paragraph text, greatly enhancing readability and establishing a modern aesthetic.

### 2. Variables & Consistent Color Palette
- Declared a centralized theme using the CSS `:root` selector for custom properties (e.g., `var(--primary-color)`). I developed a cohesive palette containing a "Sky Blue Accent" (`#0ea5e9`), varied slate text colors, and subtle border colors, which kept styling highly consistent.

### 3. Effecient CSS Selectors
- Moved from relying solely on broad element tags to specific **Class and ID Selectors**. Structured the CSS logically—grouping `.card` classes, `.nav-links`, and pseudo-classes like `:hover` securely without unexpected cascading issues. 

### 4. Advanced Layout Configuration (Flexbox & Grid)
- **Flexbox Navigation Bar:** Designed a sticky (`position: sticky`) responsive navigation bar aligning the logo and link items perfectly via `display: flex; justify-content: space-between; align-items: center;`.
- **CSS Grid Portfolios:** I wrapped "Work Experience" and "Education" into `<article>` and `<section>` tags and deployed **CSS Grid** (`display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));`). This creates automatic dynamic columns for wide screens that perfectly collapse into a single column on mobile.

### 5. Alignment, Spacing, & Hover Effects
- Controlled structural flow universally leveraging padding and fluid margins (`margin: 0 auto;`). 
- Incorporated CSS transitions (`transition: transform 0.2s, box-shadow 0.2s`) so that hovering over experience cards, navigation links, and tags generates an interactive, premium "lift" effect horizontally across the page. 
