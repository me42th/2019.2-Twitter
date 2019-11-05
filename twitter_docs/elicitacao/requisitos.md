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
| R001 |	O usuário deve ser capaz de retweetar, ou seja, copiar o tweet para o seu próprio perfil. |	Entrevista 02 do Fernando, Entrevista da Aline |	MUST |	F | Usuário |
| R002 |	O usuário deve dotar de liberdade para expressar sua opinião sobre quaisquer temas sem qualquer tipo de censura imposta pelo sistema  |	Entrevista do Erick, Entrevista da Aline, Entrevista do Erick |	SHOULD |	NF | Usuário |
| R003 |	O sistema deve responder de forma rápida às ações do usuário |	Entrevista do Erick, Entrevista 01 do Fernando, Entrevista da Aline | SHOULD |	NF | Sistema |
| R004 |	Permitir a interação da aplicação com outros aplicativos |	Entrevista do Erick |	WOULD |	F | Sistema |
| R005 |	O sistema deve prover segurança e proteção dos dados submetidos |	Entrevista do Erick, Entrevista da Lorrany |	MUST |	F | Sistema |
| R006 |	Permitir a troca de informações entre usuários - numero comentarios, chats, retweet. |	Entrevista do Erick |	MUST |	F | Sistema |
| R007 |	Ter um espaço destinado a anúncios. |	Entrevista do Erick |	COULD |	F | Sistema |
| R008 |	O usuário deve ser capaz de curtir um tweet, mostrando que tem interesse naquele conteúdo. |	Entrevista 02 do Fernando, Entrevista da Aline | MUST |	F | Usuário | 
| R009 |	Permitir que o usuário saia da aplicação a partir de um anúncio. |	Entrevista do Erick |	WOULD |	F | Usuário |
| R010 |	O sistema deve ser capaz de indentificar e sugerir conteúdo das pessoas que você mais interage na plataforma, ou seja, amigos mais próximos. |	Entrevista 02 do Fernando |	SHOULD | F | Sistema |
| R011 |	Que o app tenha uma funcionalidade que sugira notícias e conteúdos novos. | 	Entrevista 01 Lorrany |	SHOULD | F | Sistema |
| R012 |	Que o app tenha cuidado ao exibir conteúdos violentos ou que possam ser ofensivos para algumas pessoas. |	Entrevista 01 Lorrany |	MUST |	F | Sistema |
| R013 |	Que o app seja mais atrativo que os concorrentes. |	Entrevista 01 Lorrany |	COULD |	NF | Sistema |
| R014 |	O sistema deve possuir uma forma de monetização que não prejudique a experiência do usuário |	Entrevista 01 Lorrany |	COULD |	F | Sistema |
| R015 |	O sistema deve atenuar a quantidade de mídia paga veiculada aos usuários |	Entrevista 01 Lorrany |	SHOULD | NF | Sistema | 
| R016 |	O sistema deve realizar sugestões de conteúdo para o usuário após um certo período ausente da plataforma. |	Entrevista 03 do Fernando |	COULD |	F | Sistema |
| R017 |	O app deve possuir um sistema de hashtags com agrupamento de tópicos de acordo com uma marca (#) antecipando a palavra. |	Entrevista 03 do Fernando |	MUST | F | Sistema |
| R018 |	O sistema deve mostrar para o usuário quais são os assuntos que estão em alta popularidade no momento - Trending Topics. |	Entrevista 03 do Fernando, Entrevista 01 Eugênio |	COULD | F | Sistema |
| R019 |	O sistema deve manter uma velocidade de atualização do feed mais rápida do que o normal da internet. |	Entrevista 03 do Fernando |	SHOULD | NF | Sistema |
| R020 |	O usuário deve ser capaz de silenciar perfis indesejados. |	Entrevista 01 Bruno |	MUST |	F | Sistema |
| R021 |	O usuário deve ter a opção de retirar/personalizar os anúncios gerados na sua timeline |	Entrevista 01 Bruno |	SHOULD | NF | Usuário |
| R022 |	Filtragem ou limitação de conteúdo. |	Entrevista 01 Bruno |	SHOULD | F | Usuário | 
| R023 |	Permitir redirecionamento para links externos em postagens |	Entrevista 02 Eugênio |	SHOULD | F | Sistema |
| R024 |	Permitir Tweets curtos como um diário pessoal sem necessariamente ter imagens. |	Entrevista 02 Eugênio |	MUST |	F | Sistema |
| R025 |	O usuário deve ser capaz de buscar informações em um campo de pesquisa. |	Entrevista da Aline |	MUST |	F | Usuário |
| R026 |	O usuário deve ser capaz de seguir outros usuários. |	Entrevista da Aline |	MUST |	F | Usuário |
| R027 |	O usuário deve ser capaz de visualizar todos os tweets postados dos usuários o qual é seguidor. | Entrevista da Aline |	MUST | F | Usuário |
| R028 |	O usuário deve ser capaz de criar um tweet com no máximo 280 caracteres. |	Entrevista da Aline, Entrevista 01 Eugênio |	MUST |	F | Usuário |
| R029 |	O usuário deve ser capaz de enviar mensagens diretas (Direct Message) para outros usuários. |	Entrevista da Aline |	MUST |	F | Usuário |
| <span id="R030"></span>R030 |	O usuário deve ser capaz de criar uma conta no Twitter. |	Entrevista da Aline |	MUST |	F | Usuário | 
| R031 |	O usuário deve possuir um nome de usuário único iniciado pelo caractere “@”. |	Entrevista da Aline |	MUST |	F | Usuário |
| R032 |	O usuário deve ser capaz de inserir imagens, gifs e/ou vídeos durante a criação de um tweet. |	Entrevista da Aline | SHOULD | F | Usuário |
| R033 |	O usuário deve ser capaz de denunciar posts que contém conteudos imprórios e/ou prejudiciais. |	Entrevista do Bruno |	SHOULD | F | Usuário |
| R034 |	O usuário deve ser capaz de criar uma sequência de tweets. |	Entrevista da Aline |	COULD |	F | Usuário |

***
## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 11/09/2019 | Aline Laureano | Criação da página, adição da descrição da página e da tabela de requisitos com a priorização MoSCoW. | 0.1 |
| 04/10/2019 | Eugênio Sales | Refatoração de requisitos após inspeção | 0.2 |
