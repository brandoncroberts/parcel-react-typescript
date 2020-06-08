# Parcel/Typescript/React App

## Steps taken to start a project with Parcel/Typescript/React

1. Create directory with `index.html` , `index.tsx` , `tsconfig.json`

2. Initialize using `yarn init` or `npm init`

3. Install dependencies

```

yarn add react
yarn add react-dom
yarn add --dev parcel@next

```

4. Add Start script to package.json

```
// package.json
"scripts": {
"start": "parcel index.html"
}
```

5. Add compiler options to tsconfig.json

```
// tsconfig.json
{
  "compilerOptions": {
    "jsx": "react"
  }
}
```

6. Add code as shown in this repo to index.html & index.tsx

7. Run `npm run start` or `yarn start` to start dev server!
