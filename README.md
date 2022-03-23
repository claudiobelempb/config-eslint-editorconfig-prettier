# Getting Started with Create React App

npx create-react-app . --template typescript

# EditorConfig is awesome: https://EditorConfig.org

# top-most EditorConfig file

root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

# Eslint

yarn add eslint -D
npx eslint --init
yarn add eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest

yarn add eslint-plugin-react -D
yarn add eslint-plugin-react-hooks -D

"rules": {
"react/prop-type": "off",
"react-in-jsx-scope":"off",
"@typescript-eslint/explicit-module-boundary-types": "off"
}

# Prettier

yarn add prettier -D
yarn add eslint-plugin-prettier eslint-config-prettier -D

{
"semi": true,
"trailingComma": "all",
"singleQuote": true,
"printWidth": 80,
"arrowParens": "avoid"
}
