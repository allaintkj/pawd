# pawd
Pre-processor Assisted WordPress Development.  Now based on Webpack v5.

# functionality
Webpack bundler for WordPress theme development. Supports SCSS/SASS/ES6 transpiling and font/image loading.

# setup
### Place in WordPress theme directory:
```
C:\dev\wordpress\wp-content\themes\twentytwentyone
```

### Install modules:
```
npm install
```

### Configure variables:
Customize webpack.config.js to adjust entry and output filenames/placement to suit your needs.

### To watch files and automatically transpile:
```
npm run dev
```

### Production build:
```
npm run build
```

Output files are located as specified in webpack.config.js.  Enqueue scripts and styles as per WordPress guidelines.
