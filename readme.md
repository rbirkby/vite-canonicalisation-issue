# Vite base canonicalisation issue

Run with 'npm run dev'. This will start vite running with a base path of http://localhost:3000/abc

Use DevTools to see that the index.js module is loaded incorrectly from the parent path. 

This causes issues when running with vite middlewares and the JS api. It also results in different canonicalisation when vite build is run.

