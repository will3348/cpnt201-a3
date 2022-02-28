# CPNT201-a3
## Will Tengyuan Li
#### Repo: https://github.com/will3348/cpnt201-a3
#### Page: https://will3348.github.io/cpnt201-a3/
### Attrubion:
- Jess' git hub repo: https://github.com/Enyorose/tailwind-activity-template
- Install procedure: https://tailwindcss.com/docs/installation
### Note
### What is Tailwind CSS
Tailwind is a utility-first CSS framework. In contrast to other CSS frameworks like Bootstrap or Materialize CSS it doesn’t come with predefined components. Instead Tailwind CSS operates on a lower level and provides you with a set of CSS helper classes. By using this classes you can rapidly create custom design with ease. Tailwind CSS is not opinionated and let’s you create you own unique design.
### Setting up with CLI
1. Open your terminal cd to your folder which you want to set up the tailwind.
2. Install tailwindcss via npm, and create your tailwind.config.js file.
``` npm install -D tailwindcss```
``` npx tailwindcss init```
3. Configure your template paths. This procedure is leting html know this js.file.
```js 
module.exports = {
  content: [we can put just "*.html"in here],
  theme: {
    extend: {},
  },
  plugins: [],
}
 ``` 
 4. Create a CSS file and add the @tailwind directives for each of Tailwind’s layers to your main CSS file. Later on, when executing the Tailwind CSS build process, those directives will be replaced by the corresponding Tailwind CSS code. 
 5. Run the CLI tool to scan your template files for classes and build your CSS.
 ``` npx tailwindcss -i original css file src -o new css file src --watch```
 6. Link the tailwind to html. Just go back to html head part link the new css file.
 7. now we can start using tailwind with classes.

