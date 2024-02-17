# React + Vite (SLINT y PRETTIER)

Ejercicio de configuración de SLint y Prettier para un proyecto de React con Vite.

Instalación de dependencias de desarrollo:

npm i -D eslint eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-simple-import-sort pre-commit prettier

----------------------------------------------------------------

SLINT:

- env: Configuramos el entorno para el navegador, ES2021 y Node.js.
- extends: Utilizamos las configuraciones recomendadas de ESLint para JavaScript y React, y también incluimos la configuración de Prettier.
- parserOptions: Habilitamos las características de ECMAScript 2021 y JSX.
- plugins: Especificamos los plugins necesarios para React, importaciones y accesibilidad.
- rules: Desactivamos algunas reglas de React que podrían no ser necesarias y configuramos las reglas para ordenar las importaciones con simple-import-sort.
- settings: Configuramos la detección automática de la versión de React.

PRETTIER:

- semi: No añadimos punto y coma al final de las sentencias.
- singleQuote: Utilizamos comillas simples en lugar de comillas dobles.
- jsxSingleQuote: No utilizamos comillas simples en JSX.
- trailingComma: Añadimos una coma al final de las listas y objetos, ya que facilita la gestión de control de versiones.
- printWidth: Limitamos la longitud de línea a 80 caracteres.
- tabWidth: Configuramos la indentación con dos espacios.
- endOfLine: Configuramos el estilo de fin de línea para que sea automático.