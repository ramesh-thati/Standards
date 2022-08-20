# Coding Guidelines - ReactJS
1. All the folder names should be camelCase.
```
Example: homePage
```
3. React UI component’s names should be PascalCase
```
Example: LoginScreen.js
```
3. All other helper files should be camelCase. (non-component files)
```
Example: commonUtils.js
```
4.CSS files should be named the same as the component PascalCase. Global CSS which applies to all components should be placed in global.css and should be named in camelCase
```
Example: LoginScreen.css(for components), global.css(for global styles)
```
5. Test files should be named the same as the component or non-component file
```
Example: LoginScreen.test.js, commonUtils.test.js
```
6. Maintain a structured import order
```
- Build in imports (like: React)
- Third party Library/External imports Alphabetical order (like: Redux, Formik)
- Internal/project imports Alphabetical order (like: Components, utilsFiles)
```
7. Use index.js for each folder
```
src=>components=>homePage=>index.js
```
