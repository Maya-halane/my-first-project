## Pre-launch checklist
- [x] W3C validator — no errors
- [x] Lighthouse Accessibility ≥ 95
- [ ] Keyboard-only pass
- [ ] Console clean on all pages
- [ ] Live URL in README

```html
<article class="card">
    <h3>Maasai Mara</h3>
</article>
```

```javascript
const render = items => {
    container.replaceChildren();
    items.forEach(item => container.append(renderCard(item)));
};
```

```bash
git clone https://github.com/your-username/tembea.git
```

> [!NOTE]
> The REST Countries API returns all data in one call — no pagination needed.

> [!WARNING]
> Never commit `.env` files. Once in git history, they are permanent even after deletion.

> [!TIP]
> Use `git stash` when you need to switch branches before you're ready to commit.

The site scores 98 on Lighthouse[^1].

[^1]: Tested on the deployed Netlify URL in incognito mode, mobile preset.

<details>
<summary>Local setup instructions</summary>

1. Clone the repo
2. Open the folder in VS Code
3. Right-click `index.html` → Open with Live Server

</details>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Deployed_on-Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)

<!-- From a URL -->
![Tembea homepage](https://tembea.netlify.app/og-image.jpg)

<!-- From the repo — use a relative path -->
![Tembea homepage](https://raw.githubusercontent.com/nexa-courses/course-web-foundations/prod-main/content/1.4-developer-workflow/docs/screenshots/homepage.png)
