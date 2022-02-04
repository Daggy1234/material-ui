---
product: material
title: React Breadcrumbs component
components: Breadcrumbs, Link, Typography
githubLabel: 'component: breadcrumbs'
waiAria: 'https://www.w3.org/TR/wai-aria-practices/#breadcrumb'
---

# Navegação estrutural

<p class="description">O Breadcrumbs consiste em uma lista de links que ajuda o usuário a visualizar a localização da página dentro da hierarqui estrutural de um website, e permite a navegação até qualquer um de seus "ancestrais".</p>

{{"component": "modules/components/ComponentLinkHeader.js"}}

## Navegação estrutural simples

{{"demo": "BasicBreadcrumbs.js"}}

## Último caminho ativo

Mantendo o último caminho de navegação interativo.

{{"demo": "ActiveLastBreadcrumb.js"}}

## Separador customizado

Nos exemplos a seguir, nós estamos usando dois separadores de string e um ícone SVG.

{{"demo": "CustomSeparator.js"}}

## Navegação estrutural com ícones

{{"demo": "IconBreadcrumbs.js"}}

## Navegação estrutural retraída

{{"demo": "CollapsedBreadcrumbs.js"}}

## Navegação estrutural customizada

Aqui está um exemplo de customização do componente. Você pode aprender mais sobre isso na [página de documentação de sobrescritas](/customization/how-to-customize/).

{{"demo": "CustomizedBreadcrumbs.js"}}

## Integração com react-router

{{"demo": "RouterBreadcrumbs.js", "bg": true}}

## Acessibilidade

(WAI-ARIA: https://www.w3.org/TR/wai-aria-practices/#breadcrumb)

Certifique-se de adcionar uma descrição `aria-label` no componente `Breadcrumbs`.

A acessibilidade neste componente conta com:

- O conjunto de links são estruturados usando uma lista ordenada (elemento `<ol>`).
- Para prevenir que os leitores de tela pronunciem os separadores visuais entre os links, eles são escondidos com `aria-hidden`.
- Um elemento `nav` rotulado com `aria-label` identifica a estrutura como uma trilha de navegação estrutural e faz uma marcação na navegação para facilitar a localização.
