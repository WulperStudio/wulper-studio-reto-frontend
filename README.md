# Reto Wulpers FrontEnd

## Requerimiento general

Realizar una vista integrada a un servicio de graphql que desplegara una lista de cards con los datos de los personajes de la serie *Rick and Morty*, también se podra filtrar por el atributo **name**.

Datos en la Card:
- image
- status
- name
- species
- origen
- location

[Figma ~ Brief !!!](https://www.figma.com/file/4WLqhzcovo4xMuMspX2Zsx/Untitled?node-id=4%3A4)

## Requerimientos puntuales:

- Las dimensiones estarán comprendidas para 320 (width) x 640 (height).
- Se debe integrar a un servicio ya existente es indispensable usar GraphQl.

    [doc api](https://rickandmortyapi.com)

    [server graphql ~ GraphQL Playground](https://rickandmortyapi.com/graphql)
- como estado inicial debe mostrar la pagina uno (1) sin filtro alguno, tambien tenga en cuenta de usar un loading general mientras carga la data.
- Para la línea visual es recomendado usar Material-UI, pero queda a su criterio implementar o no un framework visual.

    [material-ui](https://material-ui.com/)
- La integración del servicio en graphql debe hacerse con ApolloJS e implementar sus Hooks **(indispensable)**.

    [ApolloJS](https://www.apollographql.com/docs/react/get-started/)
- Tendra un AppBar y en él un icono principal donde:

    1- si se le hace click hace reset de los filtros y recarga la lista.
- Igualmente en el AppBar habrá un InputText que tendrá como acción:
    
    1- Si se le ingresa la tecla **enter** debe evaluar que tenga por lo menos tres (3) caracteres como valor para accionar la búsqueda con el filtro **name**.
- Con el paso anterior haremos una búsqueda filtrando por el parámetro name (consultar la documentación del **GraphQL Playground** del servicio).

## Tecnologías esperadas

- ReactJS
- Typescript
- ApolloJS
- GraphQl
- material-ui (opcional)
- styled-component (opcional)

## Puntos a evaluar

- Estructura del proyecto.
- Manejo de los estados y componentes.
- Aplicación del paradigma funcional.
- Aplicar Test unitario (donde se pueda).
- Usar JSDoc para documentar las funciones (recomendado).
- clean code.
