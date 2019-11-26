</br>
</br>
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
| **<a href="../../elicitacao/requisitos/#R002">R002</a>** | Liberdade para o usuário postar o que quiser\. \- censura parcial                                                                           | UC18, UC07, US13, US15, US17, US18              | Não funcional  | Ambiental,                                  | Recurso, Satisfação                        | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R003">R003</a>** | Rapidez na realização de tarefas\.                                                                                                          | Diagrama de usabilidade, Diagrama de desempenho | nao funcional  | Desenvolvimento, Organizacional             | Satisfação, Recurso                        | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R004">R004</a>** | Permitir a interação da aplicação com outros aplicativos\.                                                                                  | US13                                            | Funcional      | Desenvolvimento                             | Agregação, Responsabilidade                | **<a href="../../pos_rastreabilidade/telas/#telaR004">Tela R004</a>** |
| **<a href="../../elicitacao/requisitos/#R005">R005</a>** | Segurança e proteção de dados\.                                                                                                             | Diagrama de Segurança                           | funcional      | Desenvolvimento                             | Agregação, Responsabilidade                | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R006">R006</a>** | Permitir a troca de informacoes entre usuários \- numero comentarios, chats, retweet                                                        | UC15, UC17, UC07, UC06, US10, US12, US17        | Funcional      | Ambiental, desenvolvimento                  | Agregação, Alocado                         | **<a href="../../pos_rastreabilidade/telas/#telaR006">Tela R006</a>** |
| **<a href="../../elicitacao/requisitos/#R007">R007</a>** | Ter um espaço destinado a anuncios                                                                                                          | Não há artefato relacionado                     | funcional      |  \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- | **<a href="../../pos_rastreabilidade/telas/#telaR007">Tela R007</a>** |
| **<a href="../../elicitacao/requisitos/#R008">R008</a>** | O usuário deve ser capaz de curtir um tweet, mostrando que tem interesse naquele conteúdo\.                                                 | UC05, US18                                      | Funcional      | Desenvolvimento                             | Satisfação, Representação                  | **<a href="../../pos_rastreabilidade/telas/#telaR008">Tela R008</a>** |
| **<a href="../../elicitacao/requisitos/#R009">R009</a>** | Permitir que o usuário saia da aplicacao a partir de um anúncio                                                                             |  Não há artefato relacionado                    | Funcional      | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R010">R010</a>** | O sistema deve ser capaz de indentificar e sugerir conteúdo das pessoas que você mais interage na plataforma, ou seja, amigos mais próximos | UC12, US11                                      | Funcional      | Desenvolvimento                             | Responsabilidade                           | **<a href="../../pos_rastreabilidade/telas/#telaR010">Tela R010</a>** |
| **<a href="../../elicitacao/requisitos/#R011">R011</a>** | Que o site tenha uma funcionalidade que sugira notícias e conteúdos novos\.                                                                 | UC12, US11                                      | Funcional      | Desenvolvimento                             | Satisfação, Responsabilidade               | **<a href="../../pos_rastreabilidade/telas/#telaR011">Tela R011</a>** |
| **<a href="../../elicitacao/requisitos/#R012">R012</a>** | Que o site tenha cuidado ao exibir conteúdos violentos ou que possam ser ofensivos para algumas pessoas\.                                   | UC13, US14                                      | Funcional      | Desenvolvimento, Organizacional             | Recurso                                    | **<a href="../../pos_rastreabilidade/telas/#telaR012">Tela R012</a>** |
| **<a href="../../elicitacao/requisitos/#R013">R013</a>** | Que o site seja mais atrativo que os concorrentes\.                                                                                         | Diagrama de desempenho                          | Não Funcional  | Desenvolvimento, Organizacional             | Responsabilidade                           | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R014">R014</a>** | Pensar em uma forma inteligente de lucro\.                                                                                                  | Não há artefato relacionado                     | Funcional      | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R015">R015</a>** | Diminuir ads                                                                                                                                | Não há artefato relacionado                     | Não Funcional  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R016">R016</a>** | O sistema deve realizar sugestões de conteúdo para o usuário após um certo período ausente da plataforma                                    | Não há artefato relacionado                     | Funcional      | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-  | \-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\- | **<a href="../../pos_rastreabilidade/telas/#telaR016">Tela R016</a>** |
| **<a href="../../elicitacao/requisitos/#R017">R017</a>** | O site deve possuir um sistema de hashtags com agrupamento de tópicos de acordo com uma marca \(\#\) antecipando a palavra                  | UC11, US08                                      | Funcional      | Ambiental, Organizacional                   | Satisfação, Recurso                        | **<a href="../../pos_rastreabilidade/telas/#telaR017">Tela R017</a>** |
| **<a href="../../elicitacao/requisitos/#R018">R018</a>** | O sistema deve mostrar para o usuário quais são os assuntos que estão em alta popularidade no momento \- Trending Topics\.                  | UC12, US09                                      | Funcional      | Desenvolvimento                             | Recurso, Agregação                         | **<a href="../../pos_rastreabilidade/telas/#telaR018">Tela R018</a>** |
| **<a href="../../elicitacao/requisitos/#R019">R019</a>** | O sistema deve manter uma velocidade de atualização do feed mais rápida do que o normal da internet                                         | Diagrama de Usabilidade                         | Não Funcional  | Desenvolvimento, Ambiental, Organizacional  | Satisfação                                 | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R020">R020</a>** | O usuário deve ser capaz de silenciar perfis indesejados\.                                                                                  | UC15, US06                                      | Funcional      | Desenvolvimento                             | Representação, Recurso                     | **<a href="../../pos_rastreabilidade/telas/#telaR020">Tela R020</a>** |
| **<a href="../../elicitacao/requisitos/#R021">R021</a>** | Liberdade do usuário em relação aos anúncios promovidos pela plataforma                                                                     | Não há artefato relacionado                                                                                                                 | Não Funcional                                   | Organizacional | Satisfação, Responsabilidade                | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R022">R022</a>** | Filtragem ou Limitação de Conteúdo                                                                                                          | UC13, US14                                      | Funcional      | Desenvolvimento                             | Recurso, Satisfação                        | **<a href="../../pos_rastreabilidade/telas/#telaR022">Tela R022</a>** |
| **<a href="../../elicitacao/requisitos/#R023">R023</a>** | Permitir postagem de conteúdo curto para redirecionamento para outros links                                                                 | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Satisfação                        | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R024">R024</a>** | Permitir Tweets curtos como um diário pessoal sem necessariamente ter imagens                                                               | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Satisfação                        | Não possui tela no app |
| **<a href="../../elicitacao/requisitos/#R025">R025</a>** | O usuário deve ser capaz de buscar informações em um campo de pesquisa\.                                                                    | UC09, UC10, UC11, UC12, US07, US08, US09        | Funcional      | Desenvolvimento                             | Regurso, Agregação, Satisfação             | **<a href="../../pos_rastreabilidade/telas/#telaR025">Tela R025</a>** |
| **<a href="../../elicitacao/requisitos/#R026">R026</a>** | O usuário deve ser capaz de seguir outros usuários\.                                                                                        | UC16                                            | Funcional      | Desenvolvimento                             | Recurso, Responsabilidade                  | **<a href="../../pos_rastreabilidade/telas/#telaR026">Tela R026</a>** |
| **<a href="../../elicitacao/requisitos/#R027">R027</a>** | O usuário deve ser capaz de visualizar todos os tweets postados de outros usuários\.                                                        | UC05, UC15,                                     | Funcional      | Desenvolvimento                             | Recurso, Agregação                         | Feed visivel em todas as outras telas |
| **<a href="../../elicitacao/requisitos/#R028">R028</a>** | O usuário deve ser capaz de criar um tweet com no máximo 280 caracteres\.                                                                   | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Agregação                         | O twitter não exibe mais a quantidadede caractéres | 
| **<a href="../../elicitacao/requisitos/#R029">R029</a>** | O usuário deve ser capaz de enviar mensagens diretas \(Direct Message\) para outros usuários\.                                              | UC17, US16                                      | Funcional      | Desenvolvimento                             | Agregação, Recurso, Satisfação             | **<a href="../../pos_rastreabilidade/telas/#telaR029">Tela R029</a>** |
| **<a href="../../elicitacao/requisitos/#R030">R030</a>** | O usuário deve ser capaz de criar uma conta no Twitter\.                                                                                    | UC02, US01                                      | Funcional      | Desenvolvimento                             | Alocação, Recurso                          | **<a href="../../pos_rastreabilidade/telas/#telaR030">Tela R030</a>** |
| **<a href="../../elicitacao/requisitos/#R031">R031</a>** | O usuário deve possuir um nome de usuário único iniciado pelo caractere “@”\.                                                               | UC01, US04                                      | Funcional      | Organizacional                              | Alocação                                   | **<a href="../../pos_rastreabilidade/telas/#telaR031">Tela R031</a>** |
| **<a href="../../elicitacao/requisitos/#R032">R032</a>** | O usuário deve ser capaz de inserir imagens, gifs e/ou vídeos durante a criação de um tweet\.                                               | UC18, US13                                      | Funcional      | Desenvolvimento                             | Recurso, Agregação                         | **<a href="../../pos_rastreabilidade/telas/#telaR032">Tela R032</a>** |
| **<a href="../../elicitacao/requisitos/#R033">R033</a>** | O usuário deve ser capaz de denunciar posts que contém conteudos imprórios e/ou prejudiciais                                                | UC13, US14                                      | Funcional      | Desenvolvimento, Organizacional             | Recurso, Responsabilidade, Satisfação      | **<a href="../../pos_rastreabilidade/telas/#telaR033">Tela R033</a>** |
| **<a href="../../elicitacao/requisitos/#R034">R034</a>** | O usuário deve ser capaz de criar uma sequência de tweets\.                                                                                 | UC18\. US13, US15                               | Funcional      | Desenvolvimento                             | Recurso, Agregação                         | **<a href="../../pos_rastreabilidade/telas/#telaR034">Tela R034</a>** |

---

## Versionamento de edições desta página

| Data       | Autor            | Descrição                | Versão |
| ---------- | ---------------- | ------------------------ | ------ |
| 12/11/2019 | Fernando e Lorrany | Add tabela na página.  | 0.1    |
| 12/11/2019 | Lorrany | Adição descrição modelo de Toranzo, e rastros do 01 ao 17 | 0.2    |
| 13/11/2019 | Fernando | Adição rastros do 18 ao 34 | 0.3    |
| 21/11/2019 | Lorrany Azevedo | Adição de telas | 0.4 |
| 24/11/2019 | Lorrany Azevedo | Adição de links para os id's dos requisitos | 0.5 |
