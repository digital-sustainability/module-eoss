# Setup

## technical
 - https://revealjs.com/markdown/ based slides per module `01 - 07` see [content/](docs/content/)
 - uses BFH reveal theme: https://github.com/bfh/reveal.js here
   - https://github.com/digital-sustainability/module-eoss/blob/main/docs/content/index.html#L11
 - for persistent format (PDF & PNG screenshots) generation
   - e.g. use https://github.com/astefanutti/decktape#usage
   - PNG > PDF: [imagemagick/convert](https://imagemagick.org/script/convert.php)
   - `mkdir slide-screenshots && decktape http://localhost:8000 --screenshots --screenshots-size 1920x1080 --screenshots-format png --screenshots-directory slide-screenshots/ slides.pdf && convert slide-screenshots/*.png slides-screenshots.pdf`
