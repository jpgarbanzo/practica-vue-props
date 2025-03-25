# vue-project

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

# practica-vue-props

## Parte 1

- crear un repositorio personal en github
- instalar vue nuevamente
- subirlo a github

## Parte 2

- crear un componente llamado "Padre.vue"
  - crear dos componentes hijos
    - Vista.vue
    - Editor.vue

## Parte 3

- agregar una variable a data en Padre.vue
  - la variable debe llamarse titulo
- agregar un prop al componente Editor.vue
  - el prop debe llamarse textoAEditar
- pasar titulo como prop desde Padre a Editor
- agregar un input en Editor
- asignar el valor de textoAEditar al input en Editor (usar v-bind:value)

## Parte 4

- agregar un prop al componente Vista.vue
  - el prop debe llamarse textoAVisualizar
  - mostrar textoAVisualizar dentro del componente
- enviar desde Padre a Vista la variable titulo como prop

# Parte 5

- Cuando se actualice el valor en el input de Editor.vue, los cambios deben reflejarse en Vista.vue
