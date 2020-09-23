# CV
This is my CV. It's written in [Pug](https://pugjs.org/), which is a simple templating engine that compiles directly to HTML. I've handcrafted the [CSS styles](./style.sass) so that the same document looks good in print and on any screen - try it on your phone!

It also compiles to PDF using [ReLaXed](https://github.com/RelaxedJS/ReLaXed).

After running `npm install`, run `npm start` to start the development server, which will recompile cv.pdf every time cv.pug changes. To compile the PDF as a once-off, use `npm run-script build-pdf`.

This repository also includes a [GitHub Actions workflow](./.github/workflows/build.yml) which compiles the CV in both HTML and PDF formats and [publishes it to GitHub Pages](https://acarapetis.github.io/cv/).
