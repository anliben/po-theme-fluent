# PO Theme - Fluent Default Theme

Tema padrão da Fluent para aplicações desenvolvidas com [PO UI](http://po-ui.io).

:warning: __Uso exclusivo dos produtos TOTVS e Clientes.__

### Como usar o tema

O **PO UI** possui o seu próprio tema, mas disponibilizamos um tema com os padrões da TOTVS.

Para utilizá-lo, instale o pacote `@anliben/po-theme-fluent` conforme abaixo:

```
npm i @anliben/po-theme-fluent
```

Em seguida, atualize o arquivo `angular.json` para utilizar o tema.

```json
"styles": [
  "node_modules/@anliben/po-theme-fluent/css/po-theme-default-variables.min.css",
  "node_modules/@anliben/po-theme-fluent/css/po-theme-default.min.css",
  "node_modules/@anliben/po-theme-fluent/style/css/po-theme-core.min.css",
]
```

> Leia mais sobre [como criar seu próprio tema customizado do PO UI][create-theme-customization].

[create-theme-customization]: https://po-ui.io/guides/create-theme-customization
