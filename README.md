# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
#   f w t _ t e s t  
 #   f w t _ t e s t  
 #   f w t _ t e s t  
 g i t  
 i n i t  
 g i t  
 a d d  
 R E A D M E . m d  
 g i t  
 c o m m i t  
 - m  
 e n d  
 g i t  
 b r a n c h  
 - M  
 m a i n  
 g i t  
 r e m o t e  
 a d d  
 o r i g i n  
 g i t @ g i t h u b . c o m : k i r i l l o i d 1 7 3 / f w t _ t e s t . g i t  
 g i t  
 p u s h  
 - u  
 o r i g i n  
 m a i n  
 #   f w t _ t e s t  
 g i t  
 i n i t  
 g i t  
 a d d  
 R E A D M E . m d  
 g i t  
 c o m m i t  
 - m  
 e n d  
 g i t  
 b r a n c h  
 - M  
 m a i n  
 g i t  
 r e m o t e  
 a d d  
 o r i g i n  
 g i t @ g i t h u b . c o m : k i r i l l o i d 1 7 3 / f w t _ t e s t . g i t  
 g i t  
 p u s h  
 - u  
 o r i g i n  
 m a i n  
 #   f w t _ t e s t  
 #   f w t _ t e s t  
 