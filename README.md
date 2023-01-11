# light-dark-mode-switcher

[Demo](https://marionetko.github.io/light-dark-mode-switcher/)

## localStorage API using

For a better user experience, I will use localStorage which will store the user's current theme, that way when the user comes back to the website, their favorite theme will be applied automatically.

```javascript
// storing the theme on the user's machine
localStorage.setItem('theme', 'dark');

//accessed the user's machine theme
localStorage.getItem('theme');
// dark
```