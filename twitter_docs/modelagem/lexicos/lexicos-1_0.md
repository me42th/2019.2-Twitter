<span style="margin-left: 40%;">![Twitter Logo](../../images/twitter-logo-100px.png)</span>
***
# Léxicos 1.0

Esta página apresenta a última versão de todos os léxicos modelados para este projeto com o app **<a href="#lxTwitter">Twitter</a>**.</br>

Agora os léxicos desta página se apresentam em um formato de tabela com cada ocorrência de léxico sendo um ***<a href"#">link</a>*** para a sua definição.

**LAL - Léxico Ampliado da Linguagem**

Trata-se de uma técnica que compõe os [cenários](../cenarios/cenarios.md) de forma a descrever os símbolos de uma linguagem. </br> Nesse caso, essa técnica descreve alguns termos relacionados ao software em questão.

Cada símbolo tem um nome, uma noção e um impacto, sendo que : </br>

- noção : é o que significa o símbolo (denotação); </br>
- impacto : é o efeito do símbolo na aplicação ou o efeito de algo na aplicação sobre o símbolo (conotação).

Símbolos também possuem uma classificação, que pode ser : estado ; verbo ; objeto ; sujeito.
***
# Alguns léxicos para o app **<a href="#lxTwitter">Twitter</a>**

<span id="lxTrending"></span>
## **<a href="#lxTrending">Trending</a>**

**Autor** : Erick Giffoni</br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxTrending">trending</a>** |
|**Noção:**|- Aba no aplicativo **<a href="#lxTwitter">twitter</a>** a qual reune um conjunto de assuntos que estão sendo mais discutidos no momento, seja por meio de **<a href="#lxHashtag">hashtags</a>** (#) ou por meio de palavras-chave;</br>- Quem reune essas informações é o algoritmo do app **<a href="#lxTwitter">twitter</a>**;</br>- Cada assunto mais falado reune um conjunto de **<a href="#lxTweet">tweets</a>** |
|**Classificação:**|	objeto |
|**Impacto(s):**|- O usuário pode interagir com os assuntos mais falados (**<a href="#lxTrending">trending</a>** topics);</br>- O usuário pode realizar um **<a href="#lxTweet">tweet</a>** relacionado a algum **<a href="#lxTrending">trending</a>** topic; |
|**Sinônimo(s):**|	assuntos mais falados, tendências. |


<span id="lxTweet"></span>
## **<a href="#lxTweet">Tweet</a>**
**Autor** : Erick Giffoni</br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|**<a href="#lxTweet">tweet</a>** |
|**Noção:**|- Tarefa realizada pelo usuário;</br>- Acontece quando o usuário quer compartilhar alguma informação no app **<a href="#lxTwitter">twitter</a>**;</br>- É como uma caixa. Nela encontram-se informações sobre o usuário que a fez, há quanto tempo foi feita, o conteúdo da caixa (a informação em si) , além da quantidade de curtidas (ou likes), quantidade de comentários e quantidade de compartilhamentos (retweets); |
|**Classificação:**|	objeto |
|**Impacto(s):**|	- O **<a href="#lxTweet">tweet</a>** está disponível para ser visualizado;</br>- O **<a href="#lxTweet">tweet</a>** pode ser apagado;</br>- O **<a href="#lxTweet">tweet</a>** pode ser denunciado;</br>- Outros usuários podem interagir com o **<a href="#lxTweet">tweet</a>**. |
|**Sinônimo(s):**|	post, postagem, retweet. |


<span id="lxEfetuarLogin"></span>
## **<a href="#lxEfetuarLogin">Efetuar login</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxEfetuarLogin">efetuar login</a>** |
|**Noção:**|	- Ter acesso à conta registrada;</br>- Acesso a plataforma. |
|**Classificação:**|	verbo |
|**Impacto(s):**|	- Usuário efetua login na aplicação. |
|**Sinônimo(s):**|	**<a href="#lxEfetuarLogin">logar</a>**, acessar, entrar. |

<span id="lxInteracoesComPostagens"></span>
## **<a href="#lxInteracoesComPostagens">Interações com Postagens</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxInteracoesComPostagens">interação com postagens</a>** |
|**Noção:**|	- Usuário pode favoritar(like) postagens de outros usuários.</br>- Ocorre quando o usuário deseja interagir com postagens de outros perfis expressando a sua opinião.</br>- Usuário deseja compartilhar determinada postagem ou comentário para que esteja presente em seu próprio **<a href="#lxPerfil">perfil</a>**. |
|**Classificação:**|	estado |
|**Impacto(s):**|	- Maior comunicação com usuários da plataforma;</br>- Liberdade de expressão do usuário na aplicação;</br>- O conteúdo compartilhado ou comentado pode ser denunciado (**<a href="#lxTweet">tweet</a>**, posts, imagens). |
|**Sinônimo(s):**|	share, like, retweetar, comentar, favoritar, compartilhar, likes, posts, postagens, retweet, coments, likar, fav. |


<span id="lxNotificacoes"></span>
## **<a href="#lxNotificacoes">Notificações</a>**
**Autor** : Eugênio Sales </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxNotificacoes">notificações</a>** |
|**Noção:**|	Ato ou efeito de levar a alguém o conhecimento de interações de outros usuários relacionadas ao seu **<a href="#lxPerfil">perfil</a>** como:</br>- Novos **<a href="#lxSeguidor">Seguidores</a>**;</br>- likes;</br>- Menções. |
|**Classificação:**|	objeto |
|**Impacto(s):**|	- Usuário gera interatividade na plataforma;</br>- Usuário aumenta sua rede de **<a href="#lxSeguidor">seguidores</a>**;</br>- **<a href="#lxPerfil">Perfil</a>** do usuário ganha relevância. |
|**Sinônimo(s):**|	menções, atualizações. |


<span id="lxSeguidor"></span>
## **<a href="#lxSeguidor">Seguidor</a>**
**Autor** : Eugênio Sales </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxSeguidor">seguidor</a>** |
|**Noção:**|	- Usuário que quer receber conteúdo de outro **<a href="#lxPerfil">perfil</a>**;</br>- Usuário que quer se manter engajado com o conteúdo de outro usuário. |
|**Classificação:**|	sujeito |
|**Impacto(s):**|	- Quanto mais **<a href="#lxSeguidor">seguidores</a>** um **<a href="#lxPerfil">perfil</a>** possui, mais influente ele se torna;</br>- O conteúdo de um **<a href="#lxPerfil">perfil</a>** é distribuído para a Home de outros perfis. |
|**Sinônimo(s):**|	rede de **<a href="#lxSeguidor">seguidores</a>**. |


<span id="lxDirectMessage"></span>
## **<a href="#lxDirectMessage">Direct Message</a>**
**Autor** : Lorrany Azevedo </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxDirectMessage">direct message</a>** |
|**Noção:**|- Tarefa realizada pelo usuário;</br>- Acontece quando o usuário deseja enviar uma **<a href="#lxDirectMessage">mensagem</a>** privada para outro;</br>- É como um chat para os usuário do **<a href="#lxTwitter">twitter</a>** terem conversar privadas com seus **<a href="#lxSeguidor">seguidores</a>**. |
|**Classificação:**|	objeto |
|**Impacto(s):**|	Mensagens que só serão visíveis para quem estiver na conversa. |
|**Sinônimo(s):**|	**<a href="#lxDirectMessage">mensagem</a>**, mensagem direta, **<a href="#lxDirectMessage">dm</a>**. |


<span id="lxTweetar"></span>
## **<a href="#lxTweetar">Tweetar</a>**
**Autor** : Lorrany Azevedo </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxTweetar">tweetar</a>** |
|**Noção:**|	- Tarefa realizada pelo usuário;</br>- Acontece quando o usuário deseja publicar um **<a href="#lxTweet">tweet</a>**;</br>- É um botão que pode ser clicado pelo usuário para que seu **<a href="#lxTweet">tweet</a>** seja publicado. |
|**Classificação:**|	verbo |
|**Impacto(s):**|	Torna um **<a href="#lxTweet">tweet</a>** disponível para que outros usuários possam vê-lo. |
|**Sinônimo(s):**|	publicar, postar. |


<span id="lxPerfil"></span>
## **<a href="#lxPerfil">Perfil</a>**
**Autor** : Fernando Aguilar </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**| **<a href="#lxPerfil">perfil</a>** |
|**Noção:**|	Conjunto das informações pessoais que identificam o usuário (nome, idade, profissão, cidade de nascimento etc.) e fica disponível em redes sociais. |
|**Classificação:**|	objeto |
|**Impacto(s):**|- Representação do objeto;</br>- Reunião de todas as qualidades pessoais ou profissionais de algúem. |
|**Sinônimo(s):**|	profile, página de usuário. |


<span id="lxParaVoce"></span>
## **<a href="#lxParaVoce">Para Você</a>**
**Autor** : Fernando Aguilar </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxParaVoce">para você</a>**  |
|**Noção:**|	Sugestões de conteúdo personalizado baseado no conteudo que você curte e nos seus amigos |
|**Classificação:**|	estado |
|**Impacto(s):**|	O sistema recomenda conteúdos populares |
|**Sinônimo(s):**|	sugestões, recommendation. |


<span id="lxTwitter"></span>
## **<a href="#lxTwitter">Twitter</a>**
**Autor** : Aline Laureano </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxTwitter">twitter</a>** |
|**Noção:**|	É uma rede social e um servidor para microblogging. |
|**Classificação:**|	objeto |
|**Impacto(s):**|	Além de permitir um usuário realizar cadastro e login, o **<a href="#lxTwitter">Twitter</a>** permite aos seus usuários enviar e receber atualizações pessoais de outros contatos, por meio da plataforma web do serviço, por SMS e por softwares específicos de gerenciamento. |
|**Sinônimo(s):**|	**<a href="#lxTwitter">Twitter</a>**, **<a href="#lxTwitter">TWITTER</a>**. |


<span id="lxHashtag"></span>
## **<a href="#lxHashtag">Hashtag</a>**
**Autor** : Aline Laureano </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Nome:**|	**<a href="#lxHashtag">hashtag</a>** |
|**Noção:**|	São palavras-chave ou termos associados a uma informação, tópico ou discussão que se deseja indexar de forma explícita no **<a href="#lxTwitter">twitter</a>**. Ela é iniciada pelo símbolo "#". |
|**Classificação:**|	objeto |
|**Impacto(s):**|	As hastags permitem o agrupamento de **<a href="#lxTweet">tweets</a>** e informações que obtenham **<a href="#lxHashtag">hashtags</a>** em comum. |
|**Sinônimo(s):**|	**<a href="#lxHashtag">#hashtag</a>**, **<a href="#lxHashtag">Hashtag</a>**. |


<span id="#search"></span>
## **<a href="#search">Pesquisar</a>**
**Autor** : Bruno Duarte</br>
**Versão:** 0.1 </br>

|   |   |
|---|---|
|**Nome:**|**<a href="#search">Pesquisar</a>** |
|**Noção:**|- Tarefa realizada pelo usuário;</br>- Acontece quando o usuário deseja saber de alguma notícia jornalística ou curiosidades do momento;</br>- É um ícone de lupa que leva a uma caixa de texto permitindo o usuário a pesquisar notícias a seu gosto |
|**Classificação:**|Verbo |
|**Impacto(s):**|	- Notícias solicitadas estarão vinculadas de acordo com o que foi digitado </br>- A fonte da informação pode ser acessada</br>- O **<a href="#lxTweet">tweet</a>** pode ser denunciado;|
|**Sinônimo(s):**|search, pesquisar, jornais. |


<span id="#report"></span>
## **<a href="#reportar">Reportar</a>**
**Autor** : Bruno Duarte</br>
**Versão:** 0.1 </br>

|   |   |
|---|---|
|**Nome:**|**<a href="#report">Reportar/Denunciar</a>** |
|**Noção:**|- Tarefa realizada pelo usuário;</br>- Acontece quando o usuário deseja que alguma postagem ou tweet sejam retirados da plataforma</br>- Atividade que visa tornar o twitter um ambiente agradável |
|**Classificação:**|Verbo |
|**Impacto(s):**|	- O Tweet ou postagem será apagado </br>- O usuário que feriu as regras será notificado</br>- O usuário pode ser penalizado.|
|**Sinônimo(s):**|reportar, censurar, denunciar. |



<span id="#share"></span>
## **<a href="#share">Compartilhar</a>**
**Autor** : Bruno Duarte</br>
**Versão:** 0.1 </br>

|   |   |
|---|---|
|**Nome:**|**<a href="#search">Pesquisar</a>** |
|**Noção:**|- Tarefa realizada pelo usuário;</br>- Acontece quando o usuário deseja divulgar algum post da plataforma;</br>- É um ícone intuitivo de compartilhamento |
|**Classificação:**|Verbo |
|**Impacto(s):**|	- O link de origem poderá ser copiado </br>- O usuário permite que aquela postagem esteja visível em seu perfil</br>|
|**Sinônimo(s):**|compartilhar, retweetar |


<span id="#favoritar"></span>
## **<a href="#search">Gostar</a>**
**Autor** : Bruno Duarte</br>
**Versão:** 0.1 </br>

|   |   |
|---|---|
|**Nome:**|**<a href="#favoritar">Curtir</a>** |
|**Noção:**|- Tarefa realizada pelo usuário;</br>- Acontece quando o usuário deseja interagir positivamente com uma postagem;</br>- É um ícone que expressa a emoção do usuário |
|**Classificação:**|Verbo |
|**Impacto(s):**|	- O usuário que publicou será notificado </br>- O sistema recomendará posts semelhantes|
|**Sinônimo(s):**|facoritar, curtir, like |
***
## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 11/10/2019 | Aline Laureano | Criação da página, adição da descrição da página & dos léxicos em formato de tabela com alguns links entre eles. | 0.1 |
| 15/10/2019 | Aline Laureano | Adição dos links entre os léxicos & edição na descrição da página. | 0.2 |
|13/11/2019|Bruno Duarte|Adicionando mais léxicos|0.3|
|||||