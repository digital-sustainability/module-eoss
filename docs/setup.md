# Setup

## technical
 - https://revealjs.com/markdown/ based slides per module `01 - 07` see [content/](docs/content/)
 - uses BFH reveal theme: https://github.com/bfh/reveal.js here
   - https://github.com/digital-sustainability/module-eoss/blob/main/docs/content/index.html#L11
 - for persistent format (PDF & PNG screenshots) generation
   - uses https://github.com/astefanutti/decktape#usage e.g. `mkdir module-eoss-01-screen && decktape http://localhost:8000 --screenshots --screenshots-size 1920x1080 --screenshots-format png --screenshots-directory module-eoss-01-screen/ module-eoss-01.pdf`
   - PNG > PDF: [imagemagick/convert](https://imagemagick.org/script/convert.php) e.g. `convert module-eoss-01/*.png module-eoss-01-screen.pdf`
