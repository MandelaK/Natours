Natours is a portfolio project built as part of the [Advanced CSS and SASS](https://www.udemy.com/course/advanced-css-and-sass/) course by Jonas Schmedtmann.

This specific project uses float layouts to build a responsive website with no JavaScript.

### Project Setup

- Clone the repository and make sure you are on the branch `ft-develop`
- Run `npm install`
- You will need to install `live-server` if you want to use the npm scripts for live reloading
  - `npm install -g live-server`
- Run `npm run start:dev` to run both `live-server` and `node-sass` in parallel so that the browser reloads on changes.
- Run `npm build` to build a production-ready version of the CSS files

### Improvement Areas

Some aspects of the project can still be improved upon.

- [ ] The navigation menu doesn't work. It will probably need JavaScript to work properly
- [ ] Not all images are responsive. Some images don't have low resolution alternatives, but that can be solved by using something ImageKit or Cloudinary
- [ ] The website is not responsive when you zoom in above 200%.
- [ ] The minified stylesheet is not bundled separately. This means running `npm buld` will minify the `styles.css` stylesheet and `node-sass` will also overwrite this in development.

### Feedback

This is a portfolio project, and is not meant to offer any functionality in real world use cases. However, feel free to raise any issues you find with the project. I don't intend to use JavaScript on the main branch, but might do so in the future in a different branch.
