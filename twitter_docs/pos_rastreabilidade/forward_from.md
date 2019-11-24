<span style="margin-left: 40%;">![Twitter Logo](../images/twitter-logo-100px.png)</span>

---

# Matriz forward-from

### Meta-Modelo de Toranzo

Para classificar as informações a serem rastreadas na nossa matriz forward-from, nós utilizamos o meta-modelo de Toranzo para classicá-las em quatro níveis:

• Ambiental: informações oriundas do contexto no qual a organização
está inserida;</br>
• Organizacional: informações pertencentes à organização (missão,
objetivos e estratégias);</br>
• Gerencial: informações que auxiliam a gerência do projeto. </br>
• Desenvolvimento: informações associadas aos diversos artefatos
gerados ao longo do processo de desenvolvimento (artefatos de
requisitos, diagramas, códigos, casos de teste e outros).</br>

Já os principais elos definidos por Toranzo são: </br>

• Satisfação: classe origem tem dependência de satisfação com a classe
destino.</br>
• Recurso: classe origem tem dependência de recurso com a classe
destino.</br>
• Responsabilidade: registra a participação, responsabilidade e ação de
pessoas sobre artefatos.</br>
• Representação: captura a representação ou modelagem dos requisitos
em outras linguagens.</br>
• Alocado: classe origem está relacionada à classe destino, que
representa um subsistema.</br>
• Agregação: indica “composição” de elementos.</br>

## Matriz

| Id   | Requisito                                                                                                                                   | Artefato                                        | Tipo           | Categoria meta modelo                       | Elo                                        |  Telas  |
|------|---------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------|----------------|---------------------------------------------|--------------------------------------------|-------|
| **<a href="../../elicitacao/requisitos/#R001">R001</a>** | O usuário deve ser capaz de retweetar, ou seja, copiar o tweet para o seu próprio perfil\.                                                  | UC06, US15                                      | Funcional      | Ambiental,                                  | Responsabilidade, Alocado, Agregação       | **<a href="../../pos_rastreabilidade/telas/#telaR001">Tela R001</a>** |
| R002 | Liberdade para o usuário postar o que quiser\. \- censura parcial                                                                           | UC18, UC07, US13, US15, US17, US18              | Não funcional  | Ambiental,                                  | Recurso, Satisfação                        | Não possui tela no app |
| R003 | Rapidez na realização de tarefas\.                                                                                                          | Diagrama de usabilidade, Diagrama de desempenho | nao funcional  | Desenvolvimento, Organizacional             | Satisfação, Recurso                        | Não possui tela no app |
| R004 | Permitir a interação da aplicação com outros aplicativos\.                                                                                  | US13                                            | Funcional      | Desenvolvimento                             | Agregação, Responsabilidade                | **<a href="../../pos_rastreabilidade/telas/#telaR004">Tela R004</a>** |
| R005 | Segurança e proteção de dados\.                                                                                                             | Diagrama de Segurança                           | funcional      | Desenvolvimento                             | Agregação, Responsabilidade                | Não possui tela no app |
| R006 | Permitir a troca de informacoes entre usuários \- numero comentarios, chats, retweet                                                        | UC15, UC17, UC07, UC06, US10, US12, US17        | Funcional      | Ambiental, desenvolvimento                  | Agregação, Alocado                         | **<a href="../../pos_rastreabilidade/telas/#telaR006">Tela R006</a>** |
| R007 | Ter um espaço destinado a anuncios                                                                                                          | Não há artefato relacionado                     | funcional      |  \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- |
| R008 | O usuário deve ser capaz de curtir um tweet, mostrando que tem interesse naquele conteúdo\.                                                 | UC05, US18                                      | Funcional      | Desenvolvimento                             | Satisfação, Representação                  |
| R009 | Permitir que o usuário saia da aplicacao a partir de um anúncio                                                                             |  Não há artefato relacionado                    | Funcional      | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- |
| R010 | O sistema deve ser capaz de indentificar e sugerir conteúdo das pessoas que você mais interage na plataforma, ou seja, amigos mais próximos | UC12, US11                                      | Funcional      | Desenvolvimento                             | Responsabilidade                           |
| R011 | Que o site tenha uma funcionalidade que sugira notícias e conteúdos novos\.                                                                 | UC12, US11                                      | Funcional      | Desenvolvimento                             | Satisfação, Responsabilidade               |
| R012 | Que o site tenha cuidado ao exibir conteúdos violentos ou que possam ser ofensivos para algumas pessoas\.                                   | UC13, US14                                      | Funcional      | Desenvolvimento, Organizacional             | Recurso                                    |
| R013 | Que o site seja mais atrativo que os concorrentes\.                                                                                         | Diagrama de desempenho                          | Não Funcional  | Desenvolvimento, Organizacional             | Responsabilidade                           |
| R014 | Pensar em uma forma inteligente de lucro\.                                                                                                  | Não há artefato relacionado                     | Funcional      | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- |
| R015 | Diminuir ads                                                                                                                                | Não há artefato relacionado                     | Não Funcional  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- |
| R016 | O sistema deve realizar sugestões de conteúdo para o usuário após um certo período ausente da plataforma                                    | Não há artefato relacionado                     | Funcional      | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- |
| R017 | O site deve possuir um sistema de hashtags com agrupamento de tópicos de acordo com uma marca \(\#\) antecipando a palavra                  | UC11, US08                                      | Funcional      | Ambiental, Organizacional                   | Satisfação, Recurso                        |
| R018 | O sistema deve mostrar para o usuário quais são os assuntos que estão em alta popularidade no momento \- Trending Topics\.                  | UC12, US09                                      | Funcional      | Desenvolvimento                             | Recurso, Agregação                         |
| R019 | O sistema deve manter uma velocidade de atualização do feed mais rápida do que o normal da internet                                         | Diagrama de Usabilidade                         | Não Funcional  | Desenvolvimento, Ambiental, Organizacional  | Satisfação                                 |
| R020 | O usuário deve ser capaz de silenciar perfis indesejados\.                                                                                  | UC15, US06                                      | Funcional      | Desenvolvimento                             | Representação, Recurso                     |
| R021 | Liberdade do usuário em relação aos anúncios promovidos pela plataforma                                                                     | Não há artefato relacionado                                                                                                                 | Não Funcional                                   | Organizacional | Satisfação, Responsabilidade                |
| R022 | Filtragem ou Limitação de Conteúdo                                                                                                          | UC13, US14                                      | Funcional      | Desenvolvimento                             | Recurso, Satisfação                        |
| R023 | Permitir postagem de conteúdo curto para redirecionamento para outros links                                                                 | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Satisfação                        |
| R024 | Permitir Tweets curtos como um diário pessoal sem necessariamente ter imagens                                                               | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Satisfação                        |
| R025 | O usuário deve ser capaz de buscar informações em um campo de pesquisa\.                                                                    | UC09, UC10, UC11, UC12, US07, US08, US09        | Funcional      | Desenvolvimento                             | Regurso, Agregação, Satisfação             |
| R026 | O usuário deve ser capaz de seguir outros usuários\.                                                                                        | UC16                                            | Funcional      | Desenvolvimento                             | Recurso, Responsabilidade                  |
| R027 | O usuário deve ser capaz de visualizar todos os tweets postados de outros usuários\.                                                        | UC05, UC15,                                     | Funcional      | Desenvolvimento                             | Recurso, Agregação                         |
| R028 | O usuário deve ser capaz de criar um tweet com no máximo 280 caracteres\.                                                                   | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Agregação                         |
| R029 | O usuário deve ser capaz de enviar mensagens diretas \(Direct Message\) para outros usuários\.                                              | UC17, US16                                      | Funcional      | Desenvolvimento                             | Agregação, Recurso, Satisfação             |
| R030 | O usuário deve ser capaz de criar uma conta no Twitter\.                                                                                    | UC02, US01                                      | Funcional      | Desenvolvimento                             | Alocação, Recurso                          |
| R031 | O usuário deve possuir um nome de usuário único iniciado pelo caractere “@”\.                                                               | UC01, US04                                      | Funcional      | Organizacional                              | Alocação                                   |
| R032 | O usuário deve ser capaz de inserir imagens, gifs e/ou vídeos durante a criação de um tweet\.                                               | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Agregação                         |
| R033 | O usuário deve ser capaz de denunciar posts que contém conteudos imprórios e/ou prejudiciais                                                | UC13, US14                                      | Funcional      | Desenvolvimento, Organizacional             | Recurso, Responsabilidade, Satisfação      |
| R034 | O usuário deve ser capaz de criar uma sequência de tweets\.                                                                                 | UC18\. US13, US15                               | Funcional      | Desenvolvimento                             | Recurso, Agregação                         |

---

## Versionamento de edições desta página

| Data       | Autor            | Descrição                | Versão |
| ---------- | ---------------- | ------------------------ | ------ |
| 12/11/2019 | Fernando e Lorrany | Add tabela na página.  | 0.1    |
| 12/11/2019 | Lorrany | Adição descrição modelo de Toranzo, e rastros do 01 ao 17 | 0.2    |
| 13/11/2019 | Fernando | Adição rastros do 18 ao 34 | 0.3    |
| 21/11/2019 | Lorrany Azevedo | Adição de telas | 0.4 |
