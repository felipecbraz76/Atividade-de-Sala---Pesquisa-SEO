# Mini-Auditoria e Plano de Otimização SEO On-Page: SportLife

**Aluno:** Felipe Camelo Braz
**Curso:** Ciências da Computação

## 1. Nicho

A SportLife é uma loja fictícia de artigos esportivos que vende tênis, roupas (bermudas e camisas) e óculos esportivos. O público são pessoas que treinam, correm ou usam roupas esportivas no dia a dia e procuram conforto e bom preço.

## 2. Palavras-chave pesquisadas

| Produto | Palavra-chave estratégica | Intenção de busca |
|---|---|---|
| Óculos | óculos esportivo polarizado | Transacional: o usuário quer comprar um modelo específico |
| Tênis | tênis de corrida masculino | Transacional, com comparação entre modelos |
| Bermuda | bermuda esportiva masculina | Transacional |
| Camisa | camisa esportiva dry fit | Transacional e informacional |

**Como pesquisei:** usei o Google Trends e o autocompletar do Google para comparar os termos.

**O que observei:** *(preencha aqui com o que você viu, por exemplo qual termo teve mais interesse e quais sugestões apareceram no autocompletar)*

## 3. Justificativa

- Usei a palavra do produto junto de um complemento (polarizado, de corrida, dry fit) porque buscas genéricas como "camisa" ou "tênis" são muito amplas e têm muita concorrência.
- Os termos escolhidos têm intenção de compra, que combina com o objetivo de uma loja virtual.
- Cada palavra-chave tem relação direta com o conteúdo de uma seção da página, o que mantém o texto relevante para quem busca.

## 4. Plano de SEO On-Page aplicado

**Estrutura semântica:** troquei o uso genérico de `<div>` por `<header>`, `<nav>`, `<main>`, `<section>` e `<footer>`. Isso ajuda os buscadores e leitores de tela a entenderem as partes da página.

**Metatags no `<head>`:**
- `<title>` com a marca e as palavras principais.
- `<meta name="description">` com um resumo claro de até cerca de 160 caracteres.
- `<meta name="keywords">` com as palavras pesquisadas.
- `<meta name="viewport">` para a página se adaptar ao celular.
- `lang="pt-BR"` e `charset="UTF-8"` para idioma e acentuação corretos.

**Hierarquia de cabeçalhos:** um único `<h1>` com o tema da página e um `<h2>` para cada seção, cada um com uma palavra-chave.

**CSS externo:** o estilo está no arquivo `estilo.css`, ligado pelo `<link>`, o que mantém o HTML limpo e o visual reaproveitável.

| Palavra-chave | Onde foi usada |
|---|---|
| tênis de corrida masculino | `<title>`, `description`, `keywords`, `<h2>` e texto da seção Tênis |
| bermuda esportiva masculina | `description`, `keywords`, `<h2>` e texto da seção Bermudas |
| camisa esportiva dry fit | `description`, `keywords`, `<h2>` e texto da seção Camisas |
| óculos esportivo polarizado | `description`, `keywords`, `<h2>` e texto da seção Óculos |

## 5. Observação

O Google hoje não usa a metatag `keywords` para ranquear. Ela foi incluída porque a atividade pede, mas o peso maior do SEO está no `<title>`, na `description`, nos cabeçalhos e na qualidade do conteúdo.

## 6. Entregáveis

- `index.html`: página principal com semântica e metatags.
- `estilo.css`: folha de estilo externa.
- `relatorio.md`: este relatório.
