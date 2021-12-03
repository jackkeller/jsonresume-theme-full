# jsonresume-theme-full

This theme is based off of [npmjs.com/package/jsonresume-theme-short](https://www.npmjs.com/package/jsonresume-theme-short) with some additional fixes and workflows.

## Getting Started/Prerequisites

Follow the directions from the [boilerplate](https://github.com/jsonresume/jsonresume-theme-boilerplate) to get everything installed like `node`, `npm`, and the `resume-cli` then follow the workflow below in Developing

## Developing

If you have NVM installed you should be switched into a flavor of nodejs 15, otherwise make sure you're using a version around `15.14.0` before the next step.

1. `npm install`
2. In your terminal run `npm run style`
3. In another terminal run `npm run dev`
4. open `http://localhost:35729/` and start hacking away on styles

You can edit the `dev/index.html` file if you're looking to reorder things, but anything you do will not persist until you make changes in the `resume.hbs` or it's partials located in `partials/`

The resume.json used for the static dev file is located at [jsonresume.org/schema/](https://jsonresume.org/schema/) and it is the baseline that you should use in order to build your resume, leaving out sections will remove them from the output.

Enjoy!

## Using

If you want to change the accent color add this to the top of your `resume.json` above the `basics` information, and change the hex color to suit your needs!

```json
  "meta": {
    "accent": "#b4d455"
  },
```

## License

Available under [the MIT license](http://mths.be/mit).
