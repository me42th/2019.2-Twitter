<span style="margin-left: 40%;">![Twitter Logo](../images/twitter-logo-100px.png)</span>

***
# Requisitos & Priorização MoSCoW
<p>A partir do desenvolvimento de artefatos utilizando técnicas de elicitação, levantamos requisitos funcionais e não-funcionais para o Twitter.</p>
<p>Já a priorização MoSCoW foi aplicada nos requisitos levantados para, de acordo com a sua prioridade no sistema virtual Twitter, classificar os requisitos levantados com os termos: Must (tem que ter), Should (deveria ter), Could (pode ter) e Would (interessante ter).</p>
***
## Tabela de requisitos
**Autor(es):** Todos os integrantes do grupo. </br>
**Legenda para a coluna "Tipo":**

+ F = Requisito Funcional;
+ NF = Requisito Não-funcional.

|Código| Requisito | Rastro | MoSCoW | Tipo | A quem se refere |
|------|-----------|--------|--------|------|------------------|
| <span id="R001"></span> **<a href="#R001">R001</a>** |	O usuário deve ser capaz de retweetar, ou seja, copiar o tweet para o seu próprio perfil. |	Entrevista 02 do Fernando, Entrevista da Aline |	MUST |	F | Usuário |
| <span id="R002"></span> **<a href="#R002">R002</a>** |	O usuário deve dotar de liberdade para expressar sua opinião sobre quaisquer temas sem qualquer tipo de censura imposta pelo sistema  |	Entrevista do Erick, Entrevista da Aline, Entrevista do Erick |	SHOULD |	NF | Usuário |
| <span id="R003"></span> **<a href="#R003">R003</a>**|	O sistema deve responder de forma rápida às ações do usuário |	Entrevista do Erick, Entrevista 01 do Fernando, Entrevista da Aline | SHOULD |	NF | Sistema |
| <span id="R004"></span> **<a href="#R004">R004</a>**|	Permitir a interação da aplicação com outros aplicativos |	Entrevista do Erick |	WOULD |	F | Sistema |
| <span id="R005"></span> **<a href="#R005">R005</a>**|	O sistema deve prover segurança e proteção dos dados submetidos |	Entrevista do Erick, Entrevista da Lorrany |	MUST |	F | Sistema |
| <span id="R006"></span> **<a href="#R006">R006</a>**|	Permitir a troca de informações entre usuários - numero comentarios, chats, retweet. |	Entrevista do Erick |	MUST |	F | Sistema |
| <span id="R007"></span> **<a href="#R007">R007</a>**|	Ter um espaço destinado a anúncios. |	Entrevista do Erick |	COULD |	F | Sistema |
| <span id="R008"></span> **<a href="#R008">R008</a>** |	O usuário deve ser capaz de curtir um tweet, mostrando que tem interesse naquele conteúdo. |	Entrevista 02 do Fernando, Entrevista da Aline | MUST |	F | Usuário | 
| <span id="R009"></span> **<a href="#R009">R009</a>**|	Permitir que o usuário saia da aplicação a partir de um anúncio. |	Entrevista do Erick |	WOULD |	F | Usuário |
| <span id="R010"></span> **<a href="#R010">R010</a>**|	O sistema deve ser capaz de indentificar e sugerir conteúdo das pessoas que você mais interage na plataforma, ou seja, amigos mais próximos. |	Entrevista 02 do Fernando |	SHOULD | F | Sistema |
| <span id="R011"></span> **<a href="#R001">R011</a>**|	Que o app tenha uma funcionalidade que sugira notícias e conteúdos novos. | 	Entrevista 01 Lorrany |	SHOULD | F | Sistema |
| <span id="R012"></span> **<a href="#R012">R012</a>**|	Que o app tenha cuidado ao exibir conteúdos violentos ou que possam ser ofensivos para algumas pessoas. |	Entrevista 01 Lorrany |	MUST |	F | Sistema |
| <span id="R013"></span> **<a href="#R013">R013</a>**|	Que o app seja mais atrativo que os concorrentes. |	Entrevista 01 Lorrany |	COULD |	NF | Sistema |
| <span id="R014"></span> **<a href="#R014">R014</a>**|	O sistema deve possuir uma forma de monetização que não prejudique a experiência do usuário |	Entrevista 01 Lorrany |	COULD |	F | Sistema |
| <span id="R015"></span> **<a href="#R015">R015</a>**|	O sistema deve atenuar a quantidade de mídia paga veiculada aos usuários |	Entrevista 01 Lorrany |	SHOULD | NF | Sistema | 
| <span id="R016"></span> **<a href="#R016">R016</a>**|	O sistema deve realizar sugestões de conteúdo para o usuário após um certo período ausente da plataforma. |	Entrevista 03 do Fernando |	COULD |	F | Sistema |
| <span id="R017"></span> **<a href="#R017">R017</a>**|	O app deve possuir um sistema de hashtags com agrupamento de tópicos de acordo com uma marca (#) antecipando a palavra. |	Entrevista 03 do Fernando |	MUST | F | Sistema |
| <span id="R018"></span> **<a href="#R018">R018</a>**|	O sistema deve mostrar para o usuário quais são os assuntos que estão em alta popularidade no momento - Trending Topics. |	Entrevista 03 do Fernando, Entrevista 01 Eugênio |	COULD | F | Sistema |
| <span id="R019"></span> **<a href="#R019">R019</a>**|	O sistema deve manter uma velocidade de atualização do feed mais rápida do que o normal da internet. |	Entrevista 03 do Fernando |	SHOULD | NF | Sistema |
| <span id="R020"></span> **<a href="#R020">R020</a>**|	O usuário deve ser capaz de silenciar perfis indesejados. |	Entrevista 01 Bruno |	MUST |	F | Sistema |
| <span id="R021"></span> **<a href="#R021">R021</a>**|	O usuário deve ter a opção de retirar/personalizar os anúncios gerados na sua timeline |	Entrevista 01 Bruno |	SHOULD | NF | Usuário |
| <span id="R022"></span> **<a href="#R022">R022</a>**|	Filtragem ou limitação de conteúdo. |	Entrevista 01 Bruno |	SHOULD | F | Usuário | 
| <span id="R023"></span> **<a href="#R023">R023</a>**|	Permitir redirecionamento para links externos em postagens |	Entrevista 02 Eugênio |	SHOULD | F | Sistema |
| <span id="R024"></span> **<a href="#R024">R024</a>**|	Permitir Tweets curtos como um diário pessoal sem necessariamente ter imagens. |	Entrevista 02 Eugênio |	MUST |	F | Sistema |
| <span id="R025"></span> **<a href="#R025">R025</a>**|	O usuário deve ser capaz de buscar informações em um campo de pesquisa. | Entrevista da Aline |	MUST |	F | Usuário |
| <span id="R026"></span> **<a href="#R026">R026</a>**|	O usuário deve ser capaz de seguir outros usuários. |	Entrevista da Aline |	MUST |	F | Usuário |
| <span id="R027"></span> **<a href="#R027">R027</a>**|	O usuário deve ser capaz de visualizar todos os tweets postados dos usuários o qual é seguidor. | Entrevista da Aline |	MUST | F | Usuário |
| <span id="R028"></span> **<a href="#R028">R028</a>**|	O usuário deve ser capaz de criar um tweet com no máximo 280 caracteres. |	Entrevista da Aline, Entrevista 01 Eugênio |	MUST |	F | Usuário |
| <span id="R029"></span> **<a href="#R029">R029</a>**|	O usuário deve ser capaz de enviar mensagens diretas (Direct Message) para outros usuários. |	Entrevista da Aline |	MUST |	F | Usuário |
| <span id="R030"></span> **<a href="#R030">R030</a>** |	O usuário deve ser capaz de criar uma conta no Twitter. |	Entrevista da Aline |	MUST |	F | Usuário | 
| <span id="R031"></span> **<a href="#R031">R031</a>** |	O usuário deve possuir um nome de usuário único iniciado pelo caractere “@”. |	Entrevista da Aline |	MUST |	F | Usuário |
| <span id="R032"></span> **<a href="#R032">R032</a>** |	O usuário deve ser capaz de inserir imagens, gifs e/ou vídeos durante a criação de um tweet. |	Entrevista da Aline | SHOULD | F | Usuário |
| <span id="R033"></span> **<a href="#R033">R033</a>**|	O usuário deve ser capaz de denunciar posts que contém conteudos imprórios e/ou prejudiciais. |	Entrevista do Bruno |	SHOULD | F | Usuário |
| <span id="R034"></span> **<a href="#R034">R034</a>**|	O usuário deve ser capaz de criar uma sequência de tweets. |	Entrevista da Aline |	COULD |	F | Usuário |

***
## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 11/09/2019 | Aline Laureano | Criação da página, adição da descrição da página e da tabela de requisitos com a priorização MoSCoW. | 0.1 |
| 04/10/2019 | Eugênio Sales | Refatoração de requisitos após inspeção | 0.2 |
| 24/11/2019 | Lorrany Azevedo | Adição de links aos id's dos requisitos | 0.3 |
