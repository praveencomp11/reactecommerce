# reactecommerce
reactecommerce is react based emcoomerce platform using redux-store

1. Download latest (21.7..1 Current) node.js ( https://nodejs.org/en )
2. Install git https://git-scm.com/downloads (Download for windows 2.44.0)
3. npm i -g create-react-app
4. npm install @reduxjs/toolkit
5. npx create-react-app redux-store --template redux
6. cd redux-store
7. npm install -D tailwindcss
8. npx tailwindcss init
9. npm i @material-tailwind/react
10. npm i react-router-dom
11. Modify tailwind.config.js

```
const withMT = require("@material-tailwind/react/utils/withMT");
 
module.exports = withMT({
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {
      fontFamily : {
        inter :  ["inter", "sans-serif"],
      },
    },
  },
  plugins: [],
});

```

12. Modify App.css

@tailwind base;
@tailwind components;
@tailwind utilities;

13. Modify function App() in App.js file 
 
```
   return (
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
  );
 ``` 
14. npm start

15. Keep 
