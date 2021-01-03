6 steps to integrate Prettier + ESLint + Airbnb Style in VSCode

1. npx create-react-app app-name 

2. Download Eslint and Prettier extensions for VScode: 
https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

3. Install airbnb config: 
npx install-peerdeps --dev eslint-config-airbnb (only available with npm+5) 

4. eslint-config-prettier and eslint-plugin-prettier: 
npm install -D eslint-config-prettier eslint-plugin-prettier

5. create and copy the file .eslintrc.json from this repository

6. create and copy the file .prettierrc from this repository

--IF YOU HAVE A ERROR WITH NPM START--
Copy and paste the .env file
