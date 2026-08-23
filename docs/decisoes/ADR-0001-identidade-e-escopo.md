# ADR-0001 — Identidade e escopo do site profissional

**Status:** Aceito  
**Data:** 23/08/2026

## Contexto

O site lucianogebler.com.br será desenvolvido como uma iniciativa profissional pessoal e independente, destinada à construção de uma identidade profissional voltada principalmente ao desenvolvimento de software, análise de dados, modelagem, sistemas de apoio à decisão e tecnologias digitais aplicadas.

Essa nova atuação possui relação direta com conhecimentos e experiências acumulados ao longo da trajetória profissional anterior, especialmente em agronomia, pesquisa científica, avaliação ambiental, agricultura de precisão e agricultura digital.

Entretanto, o site não deverá funcionar como repositório alternativo de trabalhos institucionais desenvolvidos no âmbito da Embrapa, nem produzir confusão entre a atuação profissional pessoal e a atuação institucional.

## Decisão

O site será estruturado como portfólio profissional pessoal de Luciano Gebler.

Serão priorizados conteúdos relacionados a:

- desenvolvimento independente de software;
- programação;
- análise e processamento de dados;
- modelagem;
- sistemas de apoio à decisão;
- ferramentas computacionais;
- projetos tecnológicos independentes;
- documentação e distribuição de softwares desenvolvidos de forma independente;
- experimentação e desenvolvimento de novas soluções digitais.

A trajetória profissional anterior será apresentada de forma resumida, com a finalidade de contextualizar a formação e a experiência que fundamentam essa nova etapa profissional.

Materiais, produtos e trabalhos desenvolvidos institucionalmente no âmbito da Embrapa não serão reproduzidos ou redistribuídos pelo site pessoal. Quando necessário, serão utilizados links para fontes externas apropriadas, como páginas institucionais, Currículo Lattes e outros repositórios oficiais.

O site deverá deixar clara a natureza pessoal e independente dos projetos apresentados quando isso for pertinente.

## Identidade tecnológica

O domínio principal será:

**lucianogebler.com.br**

O domínio representa a identidade profissional do projeto e deverá permanecer independente da tecnologia ou empresa utilizada para hospedagem.

A hospedagem inicial será realizada por meio do GitHub Pages, sem criar dependência arquitetural permanente desse serviço.

O GitHub será utilizado para controle de versão, documentação, código-fonte e, quando apropriado, distribuição de software por meio do GitHub Releases.

## Internacionalização

O site será projetado desde o início para permitir conteúdo multilíngue.

Os idiomas inicialmente previstos são:

- português;
- inglês;
- espanhol;
- italiano.

O português será o idioma principal utilizado no desenvolvimento, documentação interna e manutenção do projeto.

## Privacidade e métricas

O site poderá utilizar ferramentas de web analytics para obtenção de métricas agregadas de utilização.

Quando houver interesse em conhecer usuários de softwares ou outros recursos disponibilizados pelo site, será priorizada a identificação voluntária.

A coleta de dados pessoais deverá ser minimizada e implementada somente quando houver finalidade definida, considerando os requisitos aplicáveis de privacidade e proteção de dados.

## Evolução futura

A arquitetura deverá permitir integração futura com:

- APIs;
- aplicações web;
- serviços desenvolvidos em Python ou outras linguagens;
- bancos de dados;
- sistemas de autenticação;
- serviços externos;
- infraestrutura de computação em nuvem.

Esses componentes poderão utilizar provedores diferentes do GitHub Pages sem necessidade de alteração do domínio principal ou reconstrução integral do site.

## Consequências

Esta decisão estabelece uma separação entre:

1. a identidade profissional pessoal apresentada pelo site;
2. a trajetória profissional anterior utilizada como fundamento e contexto;
3. os conteúdos e produtos de natureza institucional.

Também estabelece que o domínio próprio constitui a identidade permanente do projeto, enquanto hospedagem, serviços e infraestrutura tecnológica deverão permanecer substituíveis.