<p align="center">
  <a href="https://revealjs.com">
    <img src="https://hakim-static.s3.amazonaws.com/reveal-js/logo/v1/reveal-black-text-sticker.png" alt="reveal.js" width="500">
  </a>
</p>

# Dude brand theme for Reveal.js-presentations

You are browsing the presentation brand theme for Dude, the digital agency from Finland.

## Installation

1. Clone the repository to a desired location
2. Install [reveal.js](https://github.com/hakimel/reveal.js)
3. Cd to the directory you cloned this repository to
4. Copy every file on top of your reveal.js installation with this command:

```bash
cp -r * /var/www/reveal.js/
```

## Creating a new presentation

Just edit index.html with Markdown and reveal.js will do the rest. Considering creating a separate git repository for your index.html and images.

## Development

You should improve the theme by testing it out in reveal.js repository, then copying the files over to this repository.

For styles you'll need the required packages (install on top of reveal.js repository):

```bash
npm i stylelint-config-standard-scss stylelint-order stylelint-declaration-strict-value @ronilaukkarinen/stylelint-value-no-unknown-custom-properties @ronilaukkarinen/stylelint-a11y --save-dev
```

After this just run:

```bash
npm start
```

---

### Getting started with Reveal.js
- 🚀 [Install reveal.js](https://revealjs.com/installation)
- 👀 [View the demo presentation](https://revealjs.com/demo)
- 📖 [Read the documentation](https://revealjs.com/markup/)
- 🖌 [Try the visual editor for reveal.js at Slides.com](https://slides.com/)
- 🎬 [Watch the reveal.js video course (paid)](https://revealjs.com/course)
