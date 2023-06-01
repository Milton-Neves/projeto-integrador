# Automação de uma plataforma de trabalho freelance online 

### Cronograma de atividades - gantt

* Projeto integrador

```mermaid
    gantt
    title Projeto PotyWork
    dateFormat  YYYY-MM-DD

    section Planejamento
    Tema           :a1, 2023-05-05, 5d
    Documentação Inicial     :after a1  , 30d

    section Requisitos
    Levantamento de Requisitos      :2023-05-11  , 8d

    section Desenvolvimento Inicial
    Preparação do ambiente      :2023-05-19  , 1d

    section Implementação e Testes
    Implementação      :2023-05-19  , 14d
    Testes     : 7d

    section Documentação e Defesa
    Documentação Final      :2023-06-09  , 3d
    Defesa      : 1d

```

## Cronograma de atividades


## Planejamento


### Tema


O tema escolhido foi tomado por base em outro sistema já existente, com implementações de melhor usabilidade

### Documentação Inicial

Aqui, dou início a pesquisa, definição e documentação inicial das etapas do processo, que segue até a fase de implementação e testes

### Documentação Telas
I - PÁGINAS
Tela 1 - Na tela de início (HOME), além do NavBar, existe um pouco sobre a proposta no título "Mostre o seu Talento".
Nesta mesma página, é possível encontrar as regras e diretrizes do site (PDF, disponível para download em "VER REGRAS").
Também, é possível contratar, oferecer e visualizar cursos relacionados à área.

Tela 2 - Aqui, é possível visualizar profissionais em diversas formações da área de desenvolvimento, tais como: Web Developer, Front-end, Back-end e outros.

Tela 3 - É apresentada a equipe responsável pela plataforma, que vai tanto dos profisisonais envolvidos no desenvolvimentos como os que atuam na área de gestão e contabilidade da empresa.

Tela 4 - Tem a história da empresa, como ela foi idealizada, como surgiu, quando, quem são os responsáveis, enfim.

Tela 5 - Há um painel com todos os serviços prestados que envolvam o contrato tanto da solicitação de uma prestação de serviço, quanto que da própria prestação de serviço.

Tela 6 - A última tela é a "Fale Conosco", cuja qual o usuário terá a possibilidade de contato mais direto com os idealizadores do projeto.

II - GERENCIADOR

Tela 1 - É a tela de login, na qual, o usuário vai entrar em seu ambiente virtual. Caso este usuário não possua cadastro, é possível realizá-lo na tela 2.1 (cadastro) e ou, caso ja possua cadastro, o perfil em si.

Tela 2 - No navbar, é possivel publicar um projeto clicando no botão "publique um projeto". Nesta mesma tela tem as sinalizações de notificação (contatos, mensagens de outros usuários, contratos e outros). Também, a área de perfil, na qual consta as configurações e acessibildiade.
Ainda nesta tela, encontram-se cards com páginas para Freelancers, que é uma espécie de rede de contatos com outros profissionais, clientes e ou empresas.
Há, também, o card "contratos", onde consta todos os contratos e status destes, no dono do perfil.
O Card "portfólio" apresenta todos os trabalhos realizados por este usuário.
O Card de "finanças", direciona para a página de finanças, acordos tratados e outros por este usuário e ou empresa.

## Levantamento de Requisitos


Definição dos requisitos, com uma visão dos possíveis problemas e suas respectivas soluções.


## Preparação do ambiente e Implantação

Escolha das tecnologias que serão usadas no desenvolvimento do software e construção de um protótipo.

## Implementação e Testes


Execução dos testes com a aplicação para a verificação de possíveis erros.


## Documentação e Defesa


Apresentação do projeto com slides e telas


### Integração com as disciplinas

A plataforma PotiWork usará as tecnologias Next (frontend), Node (backend) e Postgress (banco).

Para o Front-End, optei pelo Next por causa da minha familiaridade com o trabalho, bem como NodeJs para Back-end e Postgress para o Banco.

## Diagrama de Componentes - PotiWork

![diagrama-componentes-potiwork](imagens/Classe%20UML%20-%20P%C3%A1gina%202.png)