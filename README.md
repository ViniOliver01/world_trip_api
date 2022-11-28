# 🚀 World Trip API

Esta é uma API que ira provir dados para o projeto 
[World Trip](https://github.com/ViniOliver01/World-Trip), fazendo uma utilização simples
com uma biblioteca chamada [Json Server](https://www.npmjs.com/package/json-server)

## Documentação da API

### Retorna todos os continentes

```http
  GET /continents
```

### Retorna as cidades mais visitadas de cada continente

```http
  GET /cities
```

#### Retorna as cidades de acordo com o continente enviado

```http
  GET /cities/?continent='nome_do_continente'
```
*obs: o `nome_do_continente` deve ser enviado de acordo com o `path` provindo do `/continents`*

