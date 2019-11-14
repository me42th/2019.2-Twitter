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

##Matriz

| Id   | Requisito                                                                                                                                    | Artefato                                         | Tipo          | Categoria                        | Elo                                   |
|------|----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|---------------|----------------------------------|---------------------------------------|
| R001 | O usuário deve ser capaz de retweetar, ou seja,  copiar o tweet para o seu próprio perfil.                                                   | UC06, US15                                       | Funcional     | Ambiental,                       | Responsabilidade,  Alocado, Agregação |
| R002 | Liberdade para o usuário postar o que quiser.  - censura parcial                                                                             | UC18, UC07, US13, US15, US17, US18               | Não funcional | Ambiental,                       | Recurso, Satisfação                   |
| R003 | Rapidez na realização de tarefas.                                                                                                            | Diagrama de usabilidade,  Diagrama de desempenho | nao funcional | Desenvolvimento,  Organizacional | Satisfação, Recurso                   |
| R004 | Permitir a interação da aplicação com outros aplicativos.                                                                                    | US13                                             | Funcional     | Desenvolvimento                  | Agregação,  Responsabilidade          |
| R005 | Segurança e proteção de dados.                                                                                                               | Diagrama de Segurança                            | funcional     | Desenvolvimento                  | Agregação,  Responsabilidade          |
| R006 | Permitir a troca de informacoes entre usuários -  numero comentarios, chats, retweet                                                         | UC15, UC17, UC07, UC06,  US10, US12, US17        | Funcional     | Ambiental, D esenvolvimento      | Agregação, Alocado                    |
| R007 | Ter um espaço destinado a anuncios                                                                                                           | Não há artefato relacionado                      | funcional     |  -----------                     | ---------------                       |
| R008 | O usuário deve ser capaz de curtir um tweet,  mostrando que tem interesse naquele conteúdo.                                                  | UC05, US18                                       | Funcional     | Desenvolvimento                  | Satisfação,  Representação            |
| R009 | Permitir que o usuário saia da aplicacao a partir de um anúncio                                                                              |  Não há artefato relacionado                     | Funcional     | ----------------                 | ----------------                      |
| R010 | O sistema deve ser capaz de indentificar e sugerir conteúdo  das pessoas que você mais interage na plataforma, ou seja, amigos mais próximos | UC12, US11                                       | Funcional     | Desenvolvimento                  | Responsabilidade                      |
| R011 | Que o site tenha uma funcionalidade que sugira notícias e conteúdos novos.                                                                   | UC12, US11                                       | Funcional     | Desenvolvimento                  | Satisfação,  Responsabilidade         |
| R012 | Que o site tenha cuidado ao exibir conteúdos violentos  ou que possam ser ofensivos para algumas pessoas.                                    | UC13, US14                                       | Funcional     | Desenvolvimento,  Organizacional | Recurso                               |
| R013 | Que o site seja mais atrativo que os concorrentes.                                                                                           | Diagrama de desempenho                           | Não Funcional | Desenvolvimento,  Organizacional | Responsabilidade                      |
| R014 | Pensar em uma forma inteligente de lucro.                                                                                                    | Não há artefato relacionado                      | Funcional     | 
| R015 | Diminuir ads                                                                                                             | Não Funcional | Não há artefato relacionado | -----------------          | -----------------    |
| R016 | O sistema deve realizar sugestões de conteúdo para o  usuário após um certo período ausente da plataforma                | Funcional     | Não há artefato relacionado | -----------------          | -----------------    |
| R017 | O site deve possuir um sistema de hashtags com agrupamento  de tópicos de acordo com uma marca (#) antecipando a palavra | Funcional     | UC11, US08                  | Ambiental,  Organizacional | Satisfação,  Recurso |---------------------            | ---------------------                 |

---

## Versionamento de edições desta página

| Data       | Autor            | Descrição                | Versão |
| ---------- | ---------------- | ------------------------ | ------ |
| 12/11/2019 | Fernando e Lorrany | Add tabela na página.  | 0.1    |
| 13/11/2019 | Lorrany | Adição descrição modelo Toranzo e Rastros do 01 ao 17 | 0.1|

