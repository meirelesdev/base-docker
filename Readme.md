# Configs para Desenvolvimento.
# Em containers Docker | PHP | Nginx | MySql
---

Este repositorio é definido como base para o desenvolvimento em containers.
O objetivo é ter uma base pronta para rodar um projeto PHP com banco MySQL utilizando Containers Docker.

<p align="center">	
   <a href="https://www.linkedin.com/in/developer-danielmn/">
      <img alt="Daniel Meireles" src="https://img.shields.io/badge/-Daniel Meireles-0080000?style=flat&logo=Linkedin&logoColor=white" />
   </a>
  <img alt="Repository size" src="https://img.shields.io/github/languages/code-size/meirelesdev/base-docker?color=0080000label=repo%20size">


  <a href="https://github.com/meirelesdev/base-docker/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/meirelesdev/base-docker?color=0080000">
</p>

# :pushpin: Índice

- [Sobre](#sobre)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Usar](#como-usar)
- [Como Contribuir](#como-contribuir)

<a id="sobre"></a>

## :bookmark: Sobre

O <strong>Base PHP | Nginx | MySQL</strong> é uma configuração base para desenvolvimento de aplicações utilizando o PHP, Nginx e MySQL.


<a id="tecnologias-utilizadas"></a>

## :rocket: Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [Docker](https://docker.com)
- [PHP](https://www.php.net/)
- [MySQL](https://reactjs.org/)
 
<a id="como-usar"></a>

# :construction_worker: Como Usar

### **Pré-requisitos**

  - É **necessário** possuir o **[Docker](https://docker.com)** instalado na máquina.
  - Também, é **essencial** ter o **[Docker Composer](https://docs.docker.com/compose/install/)** instalado de forma global na máquina.

```bash
# Clone o Repositório
$ git clone https://github.com/meirelesdev/base-docker.git
```
### :whale: Executando os containers

```bash
# Entre na pasta projeto
$ cd base-docker

# Levantando os Containers
$ docker-compose up -d

```
### Informações Adicionais

Você também pode fazer ajustes no container PHP, como por exemplo instalar extenções como pdo_mysql é instalado basta usar o exemplo alterando o Arquivo DOckerfile dentro da pasta docker-php.
Se tiver duvida em como instalar uma extenção php, basta pesquisar no [Google](https://google.com).

<a id="como-contribuir"></a>

## :recycle: Como contribuir

- Faça um Fork desse repositório,
- Crie uma branch com a sua feature: `git checkout -b my-feature`
- Commit suas mudanças: `git commit -m 'feat: My new feature'`
- Push a sua branch: `git push origin my-feature`

---

<h4 align="center">
    Feito com ❤️ by <a href="https://www.linkedin.com/in/developer-danielmn/" target="_blank">Daniel Meireles</a>
</h4>