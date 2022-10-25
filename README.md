# DevSavant's Angular Component Lib Boilerplate

## Usage

### Code scaffolding

To create a new component, run `npm run generate <component-name>` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module <name>`.

After creating a new component, you'll need to add its corresponding exports in the `public-api.ts` file.

The `public-api.ts` file is going to be the entry point to your library. This is where you'll export all the files that you want the user to be able to use. So any files that you export from this file will be accessible to the users who install your library.

## Build

Run `ng build angular-lib-boilerplate` to build the project. The build artifacts will be stored in the `dist/` directory.

Note: You can change the default `angular-lib-boilerplate` name in the `angular.json` file

Once the build process is done, you'll find a `dist` folder in your root directory.

Now that we have this build ready, we can use it in our project just like we would use any other third-party library.

## Publishing to NPM

```bash
cd .\dist\initial-component   //WILL TAKE YOU INSIDE YOUR DIST FOLDER
npm publish
```

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
