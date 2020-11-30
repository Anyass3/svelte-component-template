## this is my own customized svelte component template builder
1. It is already configured for a low level implementation any webapp
  > dist/lib/*
2. Svelte component
  > src/svelte/*
3. General(In any other js project) component as a module and nomodule fallback
  > dist/component/*
4. Also as a custom element for use in any web-project
  > dist/customElement/*

  > NOTE: change the customElement tag in the rullup config 'my-component-tag-name'

# Installation
```shell
degit Anyass3/svelte-component-template#main
```
if you don't already install degit globally try:
```shell
npm install -g degit
```

ELSE: You may clone this repo or do your way.
