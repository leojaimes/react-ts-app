# install eslint

```
 yarn add -eslint
```

```
npx eslint --init
```

# select

To check syntax and find problems

# what type of modules does your project use?

- Javascript modules (import/export)

React

# Where does your code run?

Browser

# What format do you want your config file to be in ?

Javascript

# Which package manager do you want to use?

use yarn

# install eslint-config-airbnb

```
    npx install-peerdeps --dev eslint-config-airbnb
```

```
yarn add -D eslint-config-airbnb-typescript  @typescript-eslint/eslint-plugin@^5.13.0 @typescript-eslint/parser@^5.0.0
```

{
extends: ['airbnb', 'airbnb-typescript'],

- parserOptions: {
- project: './tsconfig.json' <----agregar esta linea
- }
  }

ctrl + shift + p
Seleccionar Developer Reload Window

yarn add -D prettier eslint-config-prettier eslint-plugin-prettier

# Testing adding

yarn add --dev @testing-library/react
yarn add --dev @testing-library/jest-dom

basada en https://www.youtube.com/watch?v=cchqeWY0Nak
