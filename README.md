# Sinan Khan — Personal Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. It showcases my journey as a Computer Science and Engineering student, aspiring software developer, photographer, video editor, and content creator.

The website features a dark aesthetic, purple and pink gradients, glassmorphism-inspired elements, smooth animations, and a mobile-friendly layout.

## Live Preview

- **GitHub Repository:** [sinan07khan](https://github.com/sinan07khan/sinan07khan)
- **Live Website:** Add your deployed website URL here.

## Features

- **Modern Dark Theme** — Deep backgrounds with purple, pink, and emerald accents.
- **Responsive Design** — Optimized layouts for desktops, tablets, and mobile devices.
- **Animated Hero Section** — Name reveal animations, profile photo, and floating badges.
- **Interactive Navigation** — Fixed navbar, scroll effects, active section highlighting, and mobile menu.
- **Cursor Glow Effect** — Subtle interactive lighting effect for desktop users.
- **About Me Section** — Personal introduction and key statistics.
- **Skills Showcase** — Programming, web development, problem-solving, and creative skills.
- **Project Gallery** — Highlights selected projects with GitHub links and technology tags.
- **Experience & Leadership** — Displays community involvement and creative roles.
- **Creative Portfolio** — Photography, video editing, and social media profiles.
- **Education Section** — Academic background and relevant coursework.
- **Contact Section** — Email, GitHub, LinkedIn, and Instagram links.
- **Copy Email Button** — Copies the email address with clipboard support.
- **Scroll Reveal Animations** — Sections animate into view while scrolling.
- **SEO & Social Metadata** — Page description, author information, and Open Graph tags.
- **Custom SVG Favicon** — A personalized monogram for the browser tab.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, layouts, gradients, and animations |
| JavaScript | Interactive features and scroll effects |
| Google Fonts | Syne and DM Sans typography |
| Intersection Observer API | Scroll reveal animations |
| Clipboard API | One-click email copying |
| SVG | Custom browser favicon |

## Project Structure

```text
sinan07khan/
├── index.html
├── avatar.jpg
└── README.md
```

- `index.html` — Main website containing the HTML, CSS, and JavaScript.
- `avatar.jpg` — Profile image used in the portfolio.
- `README.md` — Project documentation.

## Getting Started

No package installation or build tools are required.

### 1. Clone the repository

```bash
git clone https://github.com/sinan07khan/sinan07khan.git
```

### 2. Open the project folder

```bash
cd sinan07khan
```

### 3. Run the website

Open `index.html` in your web browser.

For local development, you can also use the **Live Server** extension in Visual Studio Code.

## Customization Guide

The source code includes a detailed customization table of contents. Search for the following tags using `Ctrl + F` in your editor.

| Tag | Section |
|---|---|
| `[CUSTOMIZE 01]` | SEO, page title, and social metadata |
| `[CUSTOMIZE 02]` | Colors and visual theme |
| `[CUSTOMIZE 03]` | Navigation bar and logo |
| `[CUSTOMIZE 04]` | Hero section and profile photo |
| `[CUSTOMIZE 05]` | About section and statistics |
| `[CUSTOMIZE 06]` | Skills and technical toolkit |
| `[CUSTOMIZE 07]` | Projects and repository links |
| `[CUSTOMIZE 08]` | Experience and leadership roles |
| `[CUSTOMIZE 09]` | Creative portfolio and social links |
| `[CUSTOMIZE 10]` | Education history |
| `[CUSTOMIZE 11]` | Contact details and email copying |
| `[CUSTOMIZE 12]` | Footer and copyright |
| `[CUSTOMIZE 13]` | JavaScript interactions |

### Change the Color Theme

Edit the CSS variables inside the `:root` selector.

```css
:root {
    --bg: #07070e;
    --surface: #0f0f1a;
    --surface2: #15151f;
    --accent: #a78bfa;
    --accent2: #f472b6;
    --accent3: #34d399;
    --text: #f1f0fb;
    --muted: #7c7a9e;
}
```

### Change the Profile Photo

Replace `avatar.jpg` with your own image, or update the image paths in the HTML. Keep the image in the same folder as `index.html` when using the default filename.

### Add a New Project

Copy an existing project card inside the `.projects-grid` container. Update its title, description, GitHub URL, date, and technology tags.

### Update Contact Information

Search for `[CUSTOMIZE 11]` and update your email address and social profile links. Also update the email value inside the `copyEmail()` JavaScript function so the copy button uses the correct address.

## Deployment

You can host this static website using any suitable static hosting service.

- **GitHub Pages** — Host the website directly from your GitHub repository.
- **Netlify** — Deploy through GitHub integration or by uploading the website files.
- **Vercel** — Import the repository and deploy it as a static website.

After deployment, add your public website URL to the Live Preview section above.

## Browser Compatibility

Designed for modern browsers such as:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

An internet connection is needed to load the Google Fonts used by the website.

## Future Improvements

- Add a downloadable CV or résumé.
- Include more projects with live demos.
- Add a dedicated photography gallery.
- Improve accessibility and reduced-motion support.
- Add a custom domain and analytics.

## Author

**Sinan Khan**

Computer Science & Engineering Student | Developer | Photographer | Content Creator

- GitHub: [@sinan07khan](https://github.com/sinan07khan)
- LinkedIn: [Sinan Khan](https://www.linkedin.com/in/sinan-khan-24313025a/)
- Instagram: [@sinan07khan](https://www.instagram.com/sinan07khan/)
- Photography: [@sinan.frame](https://www.instagram.com/sinan.frame/)

## License

This project is available for personal learning and portfolio inspiration. If you reuse or modify the source code, please provide appropriate credit to the original author.

---

**Built with code, creativity, and passion.**
