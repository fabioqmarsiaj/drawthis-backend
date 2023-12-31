# Aplicação Draw This
**Por Anadara Belmont e Fabio Marsiaj**

Nesse projeto a intenção é criar uma aplicação web para clientes que queiram ilustrações/desenhos digitais
e os ilustradores/desenhistas que queiram atender as demandas e buscar clientes.

Este README se dedica apenas ao backend do projeto.


## Summary

- [Tecnologias](#tecnologias)
- [Autores](#autores)

## Tecnologias

Para este projeto decidimos usar as tecnologias: Java17, SpringBoot 2.7.13, MongoDB, Heroku e SonarCloud.
Bem como as github actions para criação das pipelines de deploy.

Heroku será usado para rodar em produção as API's.

SonarCloud utilizaremos em todo PR, de DEVELOPMENT para MAIN, para rodar testes automatizados onde apontará sugestões de código bem como cobertura de testes.

Exemplo da análise da branch main no SonarCloud:

![main-branch](src/main/resources/images/sonar-main-branch.png)

Exemplo da análise de um PR para main no SonarCloud:

![pr-analysis](src/main/resources/images/sonar-pr-to-main-analysis.png)

Antes mesmo do PR ser mergeado configuramos o github actions para integrar com o SonarCloud checar o PR, como na imagem abaixo:

![pr-github](src/main/resources/images/pr-github.png)

Por hora a arquitetura do backend vai ser básica, uma API RESTful onde o frontend fará as chamadas.

Faremos a análise dos domínios ricos e segregações baseado no DDD - Domain Driven Design, apesar de
não ser uma aplicação grande e que se faça necessário do DDD será aplicado para fins de estudo.


## Autores

**Anadara Belmont** -  [GitHub](https://github.com/anadarabelmont)

   <a href="https://github.com/anadarabelmont">
        <img 
        alt="Imagem da Autorora Anadara Belmont" src="https://avatars.githubusercontent.com/u/112440301?v=4" width="100">
  </a>

**Fabio Quinto Marsiaj** -  [GitHub](https://github.com/fabioqmarsiaj)

   <a href="https://github.com/fabioqmarsiaj">
        <img 
        alt="Imagem do Autor Fabio Marsiaj" src="https://avatars0.githubusercontent.com/u/34289167?s=460&v=4" width="100">
  </a>
  