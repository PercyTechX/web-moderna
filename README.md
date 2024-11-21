# WEB MODERNA

## Autor👨🏽‍💻

* 🫡Nombre completo: Jesús Percy Nazario Portilla
* 📒Nombre del curso: Code 201 n4
* 📧tu email: jpnazariop@gmail.com
* 🗓️Fecha de creación del proyecto: 19/11/2024

## Sobre el proyecto 💻

> 🌐 "La Web Moderna" es tu puerta de entrada a los conceptos fundamentales que todo Desarrollador de Software necesita dominar 💻 para construir aplicaciones web funcionales, atractivas y eficientes. 🌟 Aquí encontrarás una guía completa que abarca desde los principios básicos hasta las mejores prácticas que están transformando el mundo digital. 🚀

## eslintrc

``` json
{
"env": {
 "browser": true,
 "es2021": true
},
"extends": ["eslint:recommended"],
"parserOptions": {
 "ecmaVersion": "latest",
 "sourceType": "module"
},
"rules": {
 "indent": ["error", 2],
 "linebreak-style": ["error", "unix"],
 "quotes": ["error", "single"],
 "semi": ["error", "always"],
 "no-unused-vars": "warn",
 "no-console": "warn"
}
}
```


### Explicacion del codigo

🌐 Configuración del entorno (env)
```json
Copiar código
"env": {
  "browser": true,
  "es2021": true
}
```

Define en qué entorno se ejecutará el código:

"browser": true 👉 Indica que el código está diseñado para ejecutarse en navegadores web, por lo que entiende variables globales como window o document.
"es2021": true 👉 Permite usar las características de JavaScript de la versión ECMAScript 2021 (como Promise.allSettled o el operador lógico nullish).

📚 Extensiones (extends)
```json
Copiar código
"extends": ["eslint:recommended"]
```

Aquí se extienden las reglas recomendadas por ESLint, una colección de reglas básicas para mantener buenas prácticas de codificación.

🔍 Opciones del analizador (parserOptions)
``` json
Copiar código
"parserOptions": {
  "ecmaVersion": "latest",
  "sourceType": "module"
}
```

"ecmaVersion": "latest" 👉 Permite analizar y entender las últimas características de JavaScript.
"sourceType": "module" 👉 Indica que el código usa módulos de JavaScript (import/export), común en aplicaciones modernas.

🛠️ Reglas específicas (rules)
```json
Copiar código
"rules": {
  "indent": ["error", 2],
  "linebreak-style": ["error", "unix"],
  "quotes": ["error", "single"],
  "semi": ["error", "always"],
  "no-unused-vars": "warn",
  "no-console": "warn"
}
```

Define reglas personalizadas para tu proyecto:

"indent": ["error", 2] 👉 Exige que la indentación sea de 2 espacios. Si no se cumple, marcará un error.
"linebreak-style": ["error", "unix"] 👉 Obliga a usar saltos de línea estilo Unix (\n), típico en Linux/macOS.
"quotes": ["error", "single"] 👉 Indica que se deben usar comillas simples (') para las cadenas.
"semi": ["error", "always"] 👉 Exige que todas las declaraciones terminen con punto y coma (;).
"no-unused-vars": "warn" 👉 Advertencia si hay variables declaradas pero no usadas.
"no-console": "warn" 👉 Advertencia si se deja un console.log() en el código.
🧑‍💻 En resumen:
Este archivo configura ESLint para garantizar un código JavaScript limpio, consistente y libre de errores comunes, con reglas específicas para el entorno del navegador y estándares modernos. Es una herramienta útil para mantener la calidad del código en equipos de desarrollo. 🚀.