# test

{
    "parser": "@tyepscript-eslint/parser",
    "plugins": ["@typescript-eslint", "react-hooks"],
    "extends": ["plugin:react/recommended", "plugin:@typescript-eslint/recommended", "prettier"],
    "parserOptions": {
        "ecmaVersion": 2020,
        "sourceType": "module",
        "ecmaFeatures": {
            "jsx": true
        }
    },
    "rules": {
        "eqeqeq": "off",
        "react/display-name": "off",
        "react/prop-types": "off",
        "@typescript-eslint/no-explicit-any": "off",
        "@typescript-eslint/explicit-function-return-type": "off"
    }
}

{
  "compilerOptions": {
    "target": "ES6",
    "lib": [
      "DOM",
      "DOM.Iterable",
      "ESNext"
    ],
    "allowJs": true,
    "skipLibCheck": true,
    "esModuleInterop": true,
    "allowSyntheticDefaultImports": true,
    "strict": true,
    "module": "ESNext",
    "moduleResolution": "Node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    "jsx": "preserve",
    "forceConsistentCasingInFileNames": true
  },
  "include": [
    "src"
  ]
}
