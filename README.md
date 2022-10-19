<h1 align="center">JS Documentation</h1>
<p align="center">
  Coded with <code>HTML</code>, <code>CSS</code>
</p>

## ℹ️ About
  
This is a solution to the [Build a Technical Documentation Page](https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-technical-documentation-page-project/build-a-technical-documentation-page).

**Build an app that is functionally similar to** https://technical-documentation-page.freecodecamp.rocks

## ⚙️ Tools

* **HTML5**
  * Semantic HTML
* **CSS**
  * Responsive design
* **Github Pages**
  * Hosting

## 💡 Features

* **Navigation menu**. Works like a swiss watch
* **Customized `<code>` blocks**. Plus animation on hover over code elements
* **Bouncy animation on headers**. Click on navigation links to see the effect
* **Nav transforms on small screens**
* **Custom scrollbar**
* **Custom selection**

## 📍 Additional information

### Bouncy animation on headers

```css
.main-section:target h1 {
  animation: highlight 1s ease;
  animation-delay: .3s;
}

@keyframes highlight {
  50% { 
    background-color: var(--gray-3); 
    transform: scale(1.05, 1.05) translateX(1rem);
  }
}
```

### Hover animation for code blocks

```css
code:hover {
  transform: translate(.25rem, -.25rem);
  box-shadow: 
    rgba(0, 0, 0, 0.07) 0px .0625rem 2px, 
    rgba(0, 0, 0, 0.07) 0px 2px 4px, 
    rgba(0, 0, 0, 0.07) 0px 4px 8px, 
    rgba(0, 0, 0, 0.07) 0px 8px 16px, 
    rgba(0, 0, 0, 0.07) 0px 16px 32px, 
    rgba(0, 0, 0, 0.07) 0px 32px 64px;
}
```

### Custom scrollbar

```css
::-webkit-scrollbar {
  width: .4rem;
}

::-webkit-scrollbar-track {
  background: var(--bg-color);
  
}

::-webkit-scrollbar-thumb {
  background: var(--gray-2);
  border-radius: .5rem;
}

::-webkit-scrollbar-thumb:hover {
  background: var(--gray-1);
}
```

### Custom selection

```css
::selection {
  background-color: var(--gray-3);
}
```

## 👤 Author

* FreeCodeCamp - [@Arlagonix](https://www.freecodecamp.org/Arlagonix)
* Telegram - [@Arlagonix](https://t.me/Arlagonix)
* Github - [@arlagonix](https://github.com/arlagonix)
