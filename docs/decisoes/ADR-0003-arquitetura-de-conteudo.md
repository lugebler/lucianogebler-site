# ADR-0003 — Arquitetura de conteúdo e navegação

**Status:** Aceito  
**Data:** 29/08/2026

## Contexto

A ADR-0001 estabeleceu que o site lucianogebler.com.br será um portfólio profissional pessoal e independente, voltado principalmente ao desenvolvimento de software, análise de dados, modelagem, sistemas de apoio à decisão e tecnologias digitais aplicadas.

A trajetória profissional anterior constitui a base de conhecimento e experiência que sustenta essa nova atuação, mas o site não deverá funcionar como currículo acadêmico, repositório de produção institucional ou reprodução de conteúdos já disponíveis em páginas da Embrapa, Currículo Lattes ou outras fontes institucionais.

Dessa forma, a organização do conteúdo deve priorizar aquilo que é desenvolvido, as competências envolvidas e os recursos disponibilizados, utilizando a trajetória profissional como elemento de contextualização e credibilidade.

## Decisão

A arquitetura principal de conteúdo e navegação será organizada nas seguintes áreas:

1. Início
2. Projetos
3. Competências
4. Sobre
5. Contato

Recursos como softwares, downloads, documentação, código-fonte, repositórios e manuais serão tratados inicialmente como conteúdos associados aos respectivos projetos, não constituindo uma seção independente da navegação principal.

Essa organização poderá ser revista futuramente caso o volume e a diversidade de recursos disponibilizados justifiquem a criação de uma área específica.

**o que faço → o que desenvolvo → quais competências utilizo → qual trajetória sustenta essa atuação → como entrar em contato.**

Os recursos disponibilizados constituem resultados ou componentes dos projetos e serão apresentados no contexto em que adquirem significado.

## Início

A página inicial deverá apresentar de forma sintética a identidade profissional e funcionar como porta de entrada para as demais áreas do site.

Deverá priorizar:

- nome e posicionamento profissional;
- apresentação breve da proposta de atuação;
- principais áreas de competência;
- projetos selecionados;
- síntese da relação entre conhecimento de domínio e tecnologia;
- acesso aos principais recursos;
- formas de contato.

A página inicial não deverá funcionar como currículo resumido nem concentrar uma descrição extensa da trajetória profissional.

## Projetos

A área Projetos será um dos elementos centrais do site.

Deverá apresentar trabalhos independentes relacionados, entre outros, a:

- desenvolvimento de software;
- sistemas de apoio à decisão;
- análise e processamento de dados;
- modelagem;
- ferramentas computacionais;
- experimentação tecnológica;
- integração de dados, modelos e conhecimento de domínio.

Projetos relevantes poderão possuir páginas próprias contendo descrição, problema abordado, solução desenvolvida, tecnologias utilizadas, documentação, versões, recursos disponíveis e formas de acesso ou download.

Os projetos poderão utilizar categorias e tags que identifiquem tecnologias, métodos e domínios de aplicação.

## Competências

A área Competências deverá apresentar capacidades profissionais demonstráveis por meio dos projetos e da experiência acumulada.

Inicialmente, poderão ser organizadas em torno de:

- desenvolvimento de software;
- programação;
- análise e processamento de dados;
- modelagem;
- sistemas de apoio à decisão;
- integração de dados e conhecimento;
- tecnologias digitais aplicadas.

As competências deverão ser apresentadas de forma associada à capacidade de resolver problemas, evitando listas extensas de tecnologias ou linguagens sem contexto de aplicação.

## Sobre

A área Sobre apresentará uma síntese da trajetória profissional necessária para compreender a origem e a evolução das competências atuais.

Deverá estabelecer a conexão entre a experiência acumulada em agronomia, pesquisa científica, avaliação ambiental, agricultura de precisão e agricultura digital e a evolução posterior para programação, análise de dados, modelagem e desenvolvimento de sistemas computacionais.

A descrição será deliberadamente resumida.

Informações acadêmicas, científicas e institucionais detalhadas deverão ser acessadas preferencialmente por meio de links externos apropriados, como:

- Currículo Lattes;
- perfil institucional da Embrapa;
- ORCID ou outros perfis profissionais e científicos pertinentes.

## Recursos associados aos projetos

Softwares, downloads, documentação, código-fonte, repositórios, manuais e outros materiais técnicos serão apresentados preferencialmente no contexto dos projetos aos quais pertencem.

Cada projeto poderá disponibilizar, conforme sua natureza e estágio de desenvolvimento:

- software e versões disponíveis;
- downloads;
- documentação técnica;
- manuais;
- código-fonte;
- acesso a repositórios;
- outros recursos relacionados.

Essa abordagem busca evitar duplicação de conteúdo e permitir que o visitante compreenda o recurso juntamente com o problema, a finalidade e o projeto que lhe deram origem.

A distribuição de versões de software deverá utilizar preferencialmente mecanismos apropriados, como GitHub Releases, evitando utilizar o próprio repositório do site como depósito de arquivos executáveis ou pacotes de distribuição.

Caso o volume de recursos cresça a ponto de justificar um catálogo ou mecanismo próprio de navegação, uma seção independente de Recursos poderá ser criada futuramente.

## Contato

A área Contato deverá oferecer formas adequadas de comunicação profissional.

A implementação deverá considerar privacidade, segurança e minimização da exposição desnecessária de dados pessoais.

Formulários ou mecanismos adicionais de contato poderão ser incorporados futuramente caso exista necessidade.

## Produção científica e publicações

Produção científica, livros, capítulos, artigos e outras atividades acadêmicas não constituirão uma seção principal do site.

Quando forem relevantes para demonstrar conhecimento, experiência ou fundamentação de determinado projeto, poderão ser mencionados seletivamente e vinculados às fontes externas apropriadas.

O objetivo é evitar que o site se transforme em duplicação do Currículo Lattes ou de páginas institucionais.

## Domínios de aplicação

Agricultura, agricultura digital, meio ambiente e outras áreas relacionadas à trajetória profissional serão tratadas como domínios de aplicação do conhecimento e das tecnologias desenvolvidas.

Esses domínios não constituirão, isoladamente, a identidade principal ou a estrutura central de navegação do site.

Essa decisão permite que o portfólio permaneça aberto à aplicação das competências tecnológicas em novos setores e problemas no futuro.

## Classificação dos projetos

Sempre que pertinente, projetos poderão ser identificados por tags ou categorias relacionadas a:

- tecnologias utilizadas;
- métodos;
- tipo de solução;
- domínio de aplicação.

Exemplos:

**4DGAP**  
`Python` · `Dados` · `Sistema de apoio à decisão` · `Agricultura`

A classificação deverá auxiliar a navegação e a compreensão dos projetos sem limitar a identidade profissional a um único domínio de aplicação.

## Internacionalização

A arquitetura de conteúdo deverá ser compatível com a decisão estabelecida na ADR-0001 de disponibilizar o site inicialmente em:

- português;
- inglês;
- espanhol;
- italiano.

A estrutura de navegação deverá permanecer conceitualmente equivalente entre os idiomas.

A implementação técnica da internacionalização será definida separadamente, evitando duplicação desnecessária de conteúdo e facilitando a manutenção das diferentes versões linguísticas.

## Evolução

A arquitetura deverá permitir a inclusão futura de novos projetos, competências, recursos e domínios de aplicação sem necessidade de reorganização estrutural significativa.

Novas seções principais somente deverão ser criadas quando representarem uma necessidade real de navegação ou uma mudança relevante na estratégia profissional do site.

## Consequências

Esta decisão estabelece que:

1. o site será organizado prioritariamente como portfólio profissional, e não como currículo;
2. projetos e competências terão maior destaque que a trajetória cronológica;
3. a trajetória profissional será utilizada como contexto e fundamento;
4. produção científica detalhada permanecerá prioritariamente em fontes externas;
5. agricultura digital e outros campos serão tratados como domínios de aplicação, e não como identidade exclusiva;
6. softwares, documentação, código-fonte, downloads e outros recursos serão apresentados preferencialmente no contexto dos projetos aos quais pertencem;
7. uma seção independente de Recursos somente será criada futuramente caso o volume ou a diversidade dos materiais disponibilizados estabeleça uma necessidade real de navegação;
8. a arquitetura deverá permanecer aberta a novos setores, tecnologias e formas de atuação profissional.