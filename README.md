> [!CAUTION]
> # This repository has been moved to GitLab with the latest commits not available in this repository. <sup>[?](https://gitlab.com/LIGMATV)</sup>
> https://gitlab.com/LIGMATV/docsify-dark-switcher

# Docsify Dark Switcher [Preview](https://docsify-dark-switcher.vercel.app/)
Easily switch toggle to light and dark theme for your Docsify, customizable and works in any CSS themes.
*(With a bit enhancement from you)*.

| Default | Dark |
|:--:|:--:|
| ![Screenshot Capture - 2024-05-19 - 13-06-35](https://github.com/LIGMATV/docsify-dark-switcher/assets/143163098/90db43ce-a63e-4cb7-8edd-b137f11ff95e) | ![Screenshot Capture - 2024-05-19 - 13-07-12](https://github.com/LIGMATV/docsify-dark-switcher/assets/143163098/979526dd-0981-4f29-9eee-0b708ab8e150) |
| Example, try it [here](https://docsify-dark-switcher.vercel.app/) |

# Install
 
```js
<script src="//cdn.jsdelivr.net/gh/LIGMATV/docsify-dark-switcher@latest/docsify-dark-switcher.js"></script>
```

> [!NOTE]
> Just to be safe, please use your downloaded version.
> You can download the docsify-dark-switcher.js <a href="https://cdn.jsdelivr.net/gh/LIGMATV/docsify-dark-switcher@latest/docsify-dark-switcher.js" download>here</a>.

# Configuration

**Default configuration**  
*This configuration not automically exist in the js, add this to ``<style>`` in your ``index.html``. (Except the ``dark-moon-icon`` and ``dark-sun-icon``).*
```css
:root {
    --dark-base-background: #222;
    --dark-base-color: #bbc0c4;
    --dark-theme-color: var(--theme-color, #42b983);
    --dark-code-color: var(--dark-color);
    --dark-heading-color: var(--dark-theme-color);
    --dark-cover-background: #000000a8;
    --dark-code-background: #303030;
    --dark-tip-background: #2c0000;
    --dark-warn-background: #005842;
    --dark-icon-size: 25px;
    --dark-icon-transition: .1s ease-in-out .1s;
    --dark-moon-color: #000000;
    --dark-sun-color: #ffffff;
    --dark-moon-icon: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='32' height='32' viewBox='0 0 16 16'%3E%3Cpath fill='currentColor' d='M9.598 1.591a.749.749 0 0 1 .785-.175 7.001 7.001 0 1 1-8.967 8.967.75.75 0 0 1 .961-.96 5.5 5.5 0 0 0 7.046-7.046.75.75 0 0 1 .175-.786m1.616 1.945a7 7 0 0 1-7.678 7.678 5.499 5.499 0 1 0 7.678-7.678'/%3E%3C/svg%3E");
    --dark-sun-icon: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='32' height='32' viewBox='0 0 16 16'%3E%3Cpath fill='currentColor' d='M8 12a4 4 0 1 1 0-8a4 4 0 0 1 0 8m0-1.5a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m5.657-8.157a.75.75 0 0 1 0 1.061l-1.061 1.06a.749.749 0 0 1-1.275-.326a.749.749 0 0 1 .215-.734l1.06-1.06a.75.75 0 0 1 1.06 0Zm-9.193 9.193a.75.75 0 0 1 0 1.06l-1.06 1.061a.75.75 0 1 1-1.061-1.06l1.06-1.061a.75.75 0 0 1 1.061 0M8 0a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0V.75A.75.75 0 0 1 8 0M3 8a.75.75 0 0 1-.75.75H.75a.75.75 0 0 1 0-1.5h1.5A.75.75 0 0 1 3 8m13 0a.75.75 0 0 1-.75.75h-1.5a.75.75 0 0 1 0-1.5h1.5A.75.75 0 0 1 16 8m-8 5a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0v-1.5A.75.75 0 0 1 8 13m3.536-1.464a.75.75 0 0 1 1.06 0l1.061 1.06a.75.75 0 0 1-1.06 1.061l-1.061-1.06a.75.75 0 0 1 0-1.061M2.343 2.343a.75.75 0 0 1 1.061 0l1.06 1.061a.751.751 0 0 1-.018 1.042a.751.751 0 0 1-1.042.018l-1.06-1.06a.75.75 0 0 1 0-1.06Z'/%3E%3C/svg%3E");
}
```

If you want add the dark mode version from some element, add ``.docsify-dark-mode`` part on your CSS.  
Example : ``.docsify-dark-mode element {``

# Showcase

- [LIGMATV](https://ligmatv.is-a.dev/Docs-Docsify/) - Home of my open blogs 📖.

---

Every ⭐ star is expensive. If you can star this repository, you absolutely rich!  
✨ *If you using this plugin, consider to add the project in the showcase. So i can see that! :)*

usually, you done!
