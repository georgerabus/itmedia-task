# Install
`php artisan serve`
`npm install vue@latest vue-loader@latest`
`npm install --save-dev @vitejs/plugin-vue`
in vite.config.js add `import vue from '@vitejs/plugin-vue'` and add `vue()` in `plugins`
edit resources/views/_.blade.php, add `@vite(['resources/css/app.css', 'resources/js/app.js'])` (default)
`npm install && npm run dev`
