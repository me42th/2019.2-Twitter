<span style="margin-left: 40%;">![Twitter Logo](../../images/twitter-logo-100px.png)</span>
***
# Cenários 1.0
Esta página apresenta a última versão de todos os cenários modelados para este projeto com o app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">Twitter</a>**.</br>

Um cenário é uma estratégia reconhecida para compreender as interações entre ambiente e sistema, bem como elicitar a parte comportamental do software, sua dinâmica e/ou seu fluxo.

Agora os cenários desta página se apresentam em um formato de tabela com cada ocorrência de léxico sendo um ***<a href"#">link</a>*** para a sua definição.
***
# Alguns cenários para o app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">Twitter</a>**
### **<a href="../../lexicos/lexicos-1_0/#lxTrending">Trending</a>** Topics
**Autor** : Erick Giffoni </br>
**Versão:** 0.2 </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#lxTrending">trending</a>** topics |
|**Objetivo:**|	Acompanhar quais são os assuntos mais falados no **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** em determinado momento. |
|**Contexto:**|	Navegação no app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** |
|**Atores:**|	Usuário |
|**Recursos:**|	- Servidores do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** devem estar funcionando;</br>- Outros usuários precisam estar falando sobre algum assunto em comum;</br>- Usuário deve acessar o app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Usuários devem usar uma palavra-chave sobre o assunto ou uma **<a href="../../lexicos/lexicos-1_0/#lxHashtag">hashtag</a>** (#) para identificar o tema do assunto. |
|**Exceção:**|- App não abre;</br>- Usuário tem o celular roubado;</br>- Não há assuntos sendo discutidos no momento;</br>- Servidores do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** param de funcionar. |
|**Episódios:**|- Usuário abre o app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Usuário clica no ícone de pesquisa;</br>- Usuário seleciona "**<a href="../../lexicos/lexicos-1_0/#lxTrending">trending</a>**";</br>- Usuário escolhe um dos assuntos e acompanha os **<a href="../../lexicos/lexicos-1_0/#lxTweet">tweets</a>**;</br>- Usuário pesquisa um assunto;</br>- Usuário pesquisa uma **<a href="../../lexicos/lexicos-1_0/#lxHashtag">hashtag</a>**. |

### **<a href="../../lexicos/lexicos-1_0/#lxLogin">Login</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.2  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#lxLogin">Login</a>** |
|**Objetivo:**|	Autenticar e possibilitar o acesso a plataforma do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**. |
|**Contexto:**|	Contato inicial com a aplicação. |
|**Atores:**|	Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Email ou Telefone Móvel;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação;</br>- Aplicativo restringido. |
|**Episódios:**|- Usuário baixa o aplicativo;</br>- O usuário cede suas credenciais;</br>- O sistema autentica as informações do usuário;</br>- O usuário consegue acesso a plataforma e todas as suas funcionalidades. |


### Enviar Mensagem
**Autor** : Eugênio Sales </br>
**Versão:** 0.2  </br>

|   |   |
|---|---|
|**Titulo:**|	enviar mensagem |
|**Objetivo:**|	Comunicar-se diretamente com outro usuário do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** |
|**Contexto:**|	Privacidade na comunicação |
|**Atores:**|	Usuário |
|**Recursos:**|- Outro usuário deve ser encontrado na barra de pesquisa;</br>- Internet;</br>- O usuário deve estar logado em sua conta. |
|**Exceção:**|- A internet cair durante o serviço;</br>- Um usuário bloquear o outro. |
|**Episódios:**|	- O usuário abre o app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Usuário clica no ícone de mensagem;</br>- Usuário abre a barra de pesquisa para encontrar outro usuário;</br>- Usuário escolhe o outro;</br>- Usuário envia a mensagem. |

### Criar **<a href="../../lexicos/lexicos-1_0/#lxTweet">Tweets</a>**
**Autor** : Lorrany Azevedo </br>
**Versão:** 0.2  </br>

|   |   |
|---|---|
|**Titulo:**|	criar **<a href="../../lexicos/lexicos-1_0/#lxTweet">tweets</a>** |
|**Objetivo:**|	Criar publicações que podem ser textos, imagens, vídeos, gifs, emojis, entre outros. |
|**Contexto:**|	Navegação pelo app do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** |
|**Atores:**|	Usuários |
|**Recursos:**|	- Servidores do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Computador, celular ou tablet;</br>- O usuário precisa estar conectado a internet;</br>- O usuário precisa estar logado em sua conta do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**. |
|**Exceção:**|- Queda dos servidores;</br>- Problemas na internet;</br>- Problemas no hardware que está sendo utilizado. |
|**Episódios:**|- Usuário abre a aplicação do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Usuario clica em "criar novo tweet";</br>- Usuário escreve o que irá publcicar;</br>- Usuário clica em "**<a href="../../lexicos/lexicos-1_0/#lxTweetar">tweetar</a>**" para publicar o seu tweet. |

### Explorar
**Autor** : Fernando Aguilar </br>
**Versão:** 0.2  </br>

|   |   |
|---|---|
|**Titulo:**|	explorar |
|**Objetivo:**|	Descobrir novos conteúdos com base nas categorias de sugestões feitas pelo **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**. |
|**Contexto:**|	- Navegação no app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- O usuário pode navegar por novos **<a href="../../lexicos/lexicos-1_0/#lxTweet">tweets</a>** e explorar assuntos de acordo com as categorias pré-definidas. |
|**Atores:**|	Usuário |
|**Recursos:**|	Acessar sugestões **<a href="../../lexicos/lexicos-1_0/#lxParaVoce">para você</a>**, Notícias, Esportes, Divrersão, Entreterimento, **<a href="../../lexicos/lexicos-1_0/#lxTrending">trending</a>** topics, etc. |
|**Exceção:**|	- O app não abre;</br>- Não há notícias recomendadas;</br>- O usuário não possui conexão com a rede e portanto as notícias não são exibida. |
|**Episódios:**|	- O usuário abre o app **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Ele clica no icone explorar;</br>- O usuário escolhe um tópico da lista para ler;</br>- Ele clica no tópico e é redirecionado para a nova página. |

### Comentar **<a href="../../lexicos/lexicos-1_0/#lxTweet">Tweets</a>**
**Autor** : Aline Laureano </br>
**Versão:** 0.2  </br>

|   |   |
|---|---|
|**Titulo:**|	comentar **<a href="../../lexicos/lexicos-1_0/#lxTweet">tweets</a>** |
|**Objetivo:**|	comentar um tweet publicado. |
|**Contexto:**|	Navegar e interagir com o app do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**. |
|**Atores:**|	Usuários |
|**Recursos:**|- Servidores do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Computador, celular ou tablet;</br>- O usuário precisa estar conectado à Internet;</br>- O usuário precisa estar com o **<a href="../../lexicos/lexicos-1_0/#lxLogin">Login</a>** na sua conta efetuado. |
|**Exceção:**|- Queda dos servidores do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- Falha de conexão com a Internet;</br>- Problemas no hardware que está sendo utilizado; |
|**Episódios:**|- O usuário navega e visualiza os **<a href="../../lexicos/lexicos-1_0/#lxTweet">tweets</a>** publicados no **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**;</br>- O usuário escolhe um tweet em que ele deseja comentar;</br>- O usuário clica no símbolo de realizar um comentário;</br>- O usuário digita o seu comentário;</br>- O usuário clica no botão "Responder" para publicar o seu comentário. |

### **<a href="../../lexicos/lexicos-1_0/#sugerir">Sugerir Conteúdo</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.1  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#sugerir">Sugerir Conteúdo</a>** |
|**Objetivo:**|	Sugerir conteúdo(posts) pra o usuário **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**. |
|**Contexto:**|	Usuário abre o aplicativo para conferir a sua timeline |
|**Atores:**|	Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Aplicativo instalado;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação |
|**Episódios:**|- Usuário abre o aplicativo;</br>- O usuário visualiza seu feed;</br>- O sistema insere postagens relacionadas;</br>|


### **<a href="../../lexicos/lexicos-1_0/#visu">Visualizar Anúncios</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.1  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#visu">Sugerir Conteúdo</a>** |
|**Objetivo:**|	Visulizar anúncios **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>**. |
|**Contexto:**|	Usuário abre o aplicativo para navegar em sua timeline |
|**Atores:**|Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Aplicativo instalado;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação <br/>- Ausência de Anuncintes|
|**Episódios:**|- Usuário abre o aplicativo;</br>- O usuário nvega pelo app;</br>- O sistema insere *Promoted Posts* na timeline do usuário</br>|


### **<a href="../../lexicos/lexicos-1_0/#fav">Favoritar</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.1  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#sugerir">Curtir/Favoritar</a>** |
|**Objetivo:**|	Interagir com posts realizados na rede social do Twitter **<a href="../../lexicos/lexicos-1_0/#fav">twitter</a>**.|
|**Contexto:**|	Usuário abre o aplicativo para conferir a sua timeline |
|**Atores:**|	Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Aplicativo instalado;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação |
|**Episódios:**|- Usuário abre o aplicativo;</br>- O usuário visualiza um post em sua timeline;</br>- O usuário clica no icone de favoritar</br>|

### **<a href="../../lexicos/lexicos-1_0/#ret">Retweetar</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.1  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#sugerir">Compartilhar</a>** |
|**Objetivo:**|	Interagir com posts realizados na rede social do Twitter **<a href="../../lexicos/lexicos-1_0/#ret">twitter</a>**.|
|**Contexto:**|	Usuário abre o aplicativo para conferir a sua timeline |
|**Atores:**|Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Aplicativo instalado;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação |
|**Episódios:**|- Usuário abre o aplicativo;</br>- O usuário visualiza um post em sua timeline;</br>- O usuário clica no icone de Retweetar</br>|


### **<a href="../../lexicos/lexicos-1_0/#avisar">Notificar</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.1  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#avisar">Notificar</a>** |
|**Objetivo:**| Relatar acontecimentos(postagens, comentários, etc) ligados ao usuário e suas interações  **<a href="../../lexicos/lexicos-1_0/#avisar">twitter</a>**.|
|**Contexto:**|	Usuário é notificado em sua barra de notificações do celular |
|**Atores:**|Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Aplicativo instalado;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação |
|**Episódios:**|- Usuário recebe notificação;</br>- O usuário visualiza a postagem ou comentário em questão;</br>|


### **<a href="../../lexicos/lexicos-1_0/#seguir">Seguir</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.1  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#seguir">Following/Seguidor</a>** |
|**Objetivo:**| Interligar usuários na plataforma  **<a href="../../lexicos/lexicos-1_0/#avisar">twitter</a>**.|
|**Contexto:**|	Usuário deseja ver postagens relacionadas a outro usuário |
|**Atores:**|Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Aplicativo instalado;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação |
|**Episódios:**|- Usuário abre o perfil de outro user;</br>- O usuário tem acesso ao perfil de outra pessoa</br>- Usuário clica em seguir|


### **<a href="../../lexicos/lexicos-1_0/#denunciar">Denunciar</a>**
**Autor** : Bruno Duarte </br>
**Versão:** 0.1  </br>

|   |   |
|---|---|
|**Titulo:**|	**<a href="../../lexicos/lexicos-1_0/#denunciar">Denunciar</a>** |
|**Objetivo:**| Retirar conteúdos ofensivos e/ou inapropriados da plataforma  **<a href="../../lexicos/lexicos-1_0/#avisar">twitter</a>**.|
|**Contexto:**|	Usuário deseja que determinada postagem seja retirada por ferir direitos humanos |
|**Atores:**|Usuário, Sistema |
|**Recursos:**|- Acesso a Internet;</br>- Aplicativo instalado;</br>- Aplicativo do **<a href="../../lexicos/lexicos-1_0/#lxTwitter">twitter</a>** ou Desktop. |
|**Exceção:**|- Sem acesso a Internet;</br>- Baixa nos Servidores da Aplicação |
|**Episódios:**|- Usuário ver determinada postagem;</br>- O usuário clica na postagem</br>- O sistema lista as funcionalidades<br/>- O usuário denuncia a postagem<br/>- O sistema avaliará de acordo com as diretrizes internas do Twitter|

***

***
## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 11/10/2019 | Aline Laureano | Criação da página, adição da descrição da página & dos cenários em formato de tabela com alguns links para os léxicos. | 0.1 |
| 15/10/2019 | Aline Laureano | Adição dos links para os léxicos. | 0.2 |
|13/11/2019|Bruno Duarte|Adicionando mais cenários|0.3|