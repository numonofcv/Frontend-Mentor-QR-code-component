# Frontend Mentor - QR Code Component Style Guide

This style guide provides general guidelines for the QR code component challenge.

## Colors

### Primary

* White: `#ffffff`
* Light Gray: `#f0f0f0`
* Dark Gray: `#333333`
* Gray Text: `#666666`
* Accent Blue: `#007bff`
* Hover Blue: `#0056b3`

## Typography

* **Font Family:** 'Poppins', sans-serif
* **Font Weights:** 300, 400, 500, 600, 700
* **Headings:**

  * `.title` — 24px (desktop), 20px (mobile)
  * `.card__title` — 18px (desktop), 16px (mobile)
* **Body Text:**

  * `.card__text` — 14px (desktop), 12px (mobile)
  * `.footer` — 14px (desktop), 12px (mobile)

## Layout

* **Container Width:**

  * `.card`: max-width: 300px; width: 100%;
* **Padding:**

  * `.card`: 20px (desktop), 30px (mobile)
* **Border Radius:**

  * `.card` & `.card__image`: 15px
  * `.card__content`: 10px

## Images

* **Aspect Ratio:** 1 / 1
* **Object Fit:** cover

## Effects

* **Box Shadow:**

  * `.card`: `0 0px 15px rgba(0, 0, 0, 0.1)`
  * `.card__image`: `0 2px 4px rgba(0, 0, 0, 0.1)`
* **Hover Effect:**

  * `.card:hover .card__image`: `transform: scale(1.05);`
  * Link Hover: `.footer a:hover` changes color to `#0056b3`

## Layout Techniques

* **Flexbox** is used to center content:

  ```css
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
  }
  ```

## Responsive

* Uses a **mobile-first** approach with a media query at `max-width: 600px` to adjust sizing for smaller screens.

## Accessibility

* Image `alt` attribute: "Frontend Mentor saytiga o‘tish uchun QR kodni skanerlash"
* Semantic headings used (`h1` for page title, `h2` for card title).

## Credits

* **Font:** Google Fonts - Poppins
* **Design:** Based on Frontend Mentor challenge.

---

**Tip:** Always test your component on various screen sizes to ensure the design stays clean and readable.
