# Alpha.CA.gov-theme

A Bootstrap theme used on <a href="https://alpha.ca.gov">Alpha.CA.gov</a>

## Development

Two versions of the theme are built:
- A standalone version meant to be used in a site where bootstrap is already included ```css/theme.css```
- A version that includes the full CSS from the Bootstrap project ```css/index.css```

### Prerequisites:

- <a href="https://nodejs.org">node.js</a> so you have the latest version of npm installed
- Run ```npm install``` after checking out the files in this repository

### Rebuild

Recompile all the SASS files locally by running:

```
npm run build
```

### Serve locally

You can start a local server if you are making changes to these scss files and want to include them in another project to review how they work with different pages. Start a local server with:

```
npm run start
```

This will choose a random local port, starting with 8000 and make the compiled css files available at: 

- <a href="http://localhost:8000/css/index.css">http://localhost:8000/css/index.css</a>
- <a href="http://localhost:8000/css/theme.css">http://localhost:8000/css/theme.css</a>

```caveat: no watch process added yet, you still have to run the build command to get the css to update```