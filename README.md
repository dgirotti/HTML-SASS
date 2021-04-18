# React
Curso de Introduccion a React dictado por:
https://www.capacitarte.org/curso/curso-de-react-introduccion

npm init -> creo package.js
npm install -D node-sass nodemon -> crea package-lock.js ; crea la carpeta con los modulos de node

escribir esto en el package.json dentro de: "scripts": {

 "build-css": "node-sass --include-path sass sass/style.scss css/style.css",
"watch-css": "nodemon -e scss -x \"npm run build-css\""
} 
con esto hago que lo que se crea en sass se escriba automaticamente en el css. 


npm run watch-css  ->escribir en consola  para poder sobreescribir el css desde del scss. 

npm install bootstrap@next -> para instalar modulos de bootstrap

sass-lang.com/guide -> pagina para ver sass