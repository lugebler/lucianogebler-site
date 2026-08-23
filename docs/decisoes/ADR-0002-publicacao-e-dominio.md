# ADR-0002 — Publicação e domínio

**Status:** Aceito  
**Data:** 23/08/2026

## Contexto

O site profissional pessoal será publicado inicialmente por meio do GitHub Pages, utilizando o repositório `lucianogebler-site` como fonte de publicação.

O domínio próprio registrado para o projeto é:

**lucianogebler.com.br**

Foi decidido adotar uma forma principal de acesso com `www`, mantendo também o domínio raiz funcional.

## Decisão

O endereço principal e canônico do site será:

**https://www.lucianogebler.com.br**

O domínio raiz:

**https://lucianogebler.com.br**

deverá permanecer funcional e redirecionar para o endereço principal com `www`.

A hospedagem inicial será realizada pelo GitHub Pages.

A publicação será feita a partir da branch `main`, utilizando a raiz do repositório como origem do site.

## Portabilidade

O domínio próprio representa a identidade permanente do projeto.

A hospedagem é considerada substituível.

Caso o GitHub Pages deixe de atender às necessidades futuras, o site poderá ser migrado para outro serviço de hospedagem sem alteração do domínio principal e, sempre que possível, sem alteração das URLs públicas utilizadas pelos visitantes.

Aplicações, APIs, bancos de dados e outros serviços futuros poderão ser hospedados em infraestrutura separada e integrados ao domínio por meio de subdomínios ou outras formas apropriadas.

## Situação atual

O GitHub Pages já está ativo e publicando corretamente o conteúdo da branch `main`.

O endereço provisório de publicação é:

**https://lugebler.github.io/lucianogebler-site/**

A configuração DNS do domínio próprio foi iniciada no Registro.br.

O domínio utiliza os servidores DNS do Registro.br e encontra-se temporariamente em transição para o modo avançado de gerenciamento da zona DNS.

A configuração definitiva de `www.lucianogebler.com.br` e `lucianogebler.com.br` será concluída após o término dessa transição.

## Consequências

Esta decisão estabelece:

1. `www.lucianogebler.com.br` como endereço oficial do site;
2. `lucianogebler.com.br` como endereço alternativo com redirecionamento;
3. GitHub Pages como solução inicial de hospedagem;
4. independência entre domínio e provedor de hospedagem;
5. possibilidade de evolução futura para infraestrutura mais avançada sem ruptura da identidade pública do projeto.