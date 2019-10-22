<span style="margin-left: 40%;">![Twitter Logo](../../images/twitter-logo-100px.png)</span>

***

# Backlog do produto

***

##Descrição
Este Backlog consiste em uma lista que descreve todas as funcionalidades desejadas para o Twitter. Com a finalidade de obtermos uma melhor especificação dessas funcionalidades, este Backlog apresenta a os seguintes itens de granularidade:

- **Épico** que pode englobar várias Histórias de usuário;
- **ID** da História de usuário (ou US - User history);
- Descrição da História de usuário com as colunas:
    - **Eu como**...;
    - **Desejo**...;
    - **Para que eu possa**...;
- **Tarefas** para o desenvolvimento de cada funcionalidade;
- **Critérios de aceitação** para a validação de cada História de usuário.

***
##Tabela do backlog

|Épico | ID |	Eu como |	Desejo |	Para que eu possa |	Critérios de aceitação |	Rastro |
|------|----|---------|--------|--------------------|----------------------------------|---------|
|Cadastro | <a href="#US01">**[US01]**</a> | Visitante |	Realizar cadastro | 	Me tornar um usuário do Twitter. | <a href="#US01">**Link para a [US01]**</a> | <a href="../use_cases_specifications/user_case_geral/#UC02">**UC02;**</a> <a href="../use_cases_specifications/login/">**Caso de uso - Login;**</a> <a href="../../elicitacao/requisitos/#R030">**R030;**</a> |
|Central de ajuda| <a href="#US02">**[US02]**</a> | Usuário |	Acessar a central de ajuda | 	Sanar dúvidas sobre o funcionamento e a utilização do Twitter. | <a href="#US02">**Link para a [US02]**</a> | <a href="../use_cases_specifications/user_case_geral/#UC20">**UC20;**</a> <a href="../../elicitacao/storytelling/#storytelling01">**Storytelling 01;**</a> |
| Gerenciar perfil | <a href="#US03">**[US03]**</a> | Usuário | poder trocar minha foto de perfil | passar uma imagem sobre mim da maneira que eu preferir | <a href="#US03">**Link para a [US03]**</a> | <a href="../../elicitacao/requisitos/#R030">**R002**</a> |
| Gerenciar perfil | <a href="#US04">**[US04]**</a> | Usuário | poder escolher outro nome de usuário (@) | para que eu tenha uma identificação única no Twitter | <a href="#US04">**Link para a [US04]**</a> | <a href="../../elicitacao/requisitos/#R031">**R031**</a> |
| Gerenciar perfil | <a href="#US05">**[US05]**</a> | Usuário | ter uma descrição de perfil e que esta seja editável | para que eu possa dizer aos outros usuários o que eu desejo que saibam sobre mim em poucas palavras | <a href="#US05">**Link para a [US05]**</a> | <a href="../../elicitacao/requisitos/#R002">**R002**</a> |
| Gerenciar perfil | <a href="#US06">**[US06]**</a> | Usuário | ter controle sobre quais usuários podem visualizar minhas informações (dados do perfil, tweets etc) | me sentir seguro em relação à confidencialidade dos meus dados | <a href="#US06">**Link para a [US06]**</a> | <a href="../../elicitacao/requisitos/#R020">**R020**</a> ; <a href="../../elicitacao/requisitos/#R005">**R005**</a> |
| Pesquisa | <a href="#US07">**[US07]**</a> | Usuário | buscar qualquer termo na barra de pesquisa | encontrar qualquer assunto ou tópico do meu interesse | <a href="#US07">**Link para a [US07]**</a> | <a href="../../elicitacao/requisitos/#R025">**R025**</a> ; <a href="../use_cases_specifications/user_case_geral/#UC10">**UC10;**</a>
| Pesquisa | <a href="#US08">**[US08]**</a> | Usuário | buscar uma hashtag na barra de pesquisa | me atualizar a respeito dos tópicos mais em alta | <a href="#US08">**Link para a [US08]**</a> | <a href="../../elicitacao/requisitos/#R025">**R025**</a> ; <a href="../use_cases_specifications/user_case_geral/#UC11">**UC11;**</a>
| Pesquisa | <a href="#US09">**[US09]**</a> | Usuário | conferir tópicos sugeridos baseados no meu interesse na barra de pesquisa | ter mais celeridade em buscas | <a href="#US09">**Link para a [US09]**</a> | <a href="../../elicitacao/requisitos/#R025">**R025**</a> ; <a href="../use_cases_specifications/user_case_geral/#UC12">**UC12;**</a>
***

## Lista das Histórias de usuário

<span id="US01"></span>
### <a href="#US01">**[US01]**</a> Eu, como visitante, desejo realizar cadastro.

#### Critérios de aceitação:
- Ter uma página de cadastro para o Twitter;
- Ter uma integração e uma validação do número de telefone do visitante com a conta a ser criada;
- Ter um cadastro do nome usuário único para a conta a ser criada.
- O visitante deve ser capaz de acessar a página de cadastro do Twitter;
- O visitante deve conseguir validar o seu número de celular inserindo um código de confirmação enviado pelo Twitter por SMS;
- Após a validação, o visitante é redirecionado para a sua conta de usuário do Twitter;
- Após a validação, o visitante consegue inserir o seu nome de usuário para a sua conta do Twitter.

<span id="US02"></span>
### <a href="#US02">**[US02]**</a> Eu, como usuário, desejo acessar a central de ajuda.

#### Critérios de aceitação:
- O usuário deve ser capaz de acessar a página de Central de ajuda;
- Caso exista(m) resultado(s), a barra de pesquisa retorna resultado(s) da Central de ajuda de acordo com a pesquisa feita pelo usuário.
- Ter uma página para a Central de ajuda;
- A barra de pesquisa de dúvidas deve estar na página de Central de ajuda;


<span id="US03"></span>
### <a href="#US03">**[US03]**</a> Eu, como usuário, desejo poder trocar minha foto de perfil.

#### Critérios de aceitação:
- A opção de ter uma foto de perfil deve existir ;
- O usuário pode mudar a foto no momento que quiser ;
- Outros usuários não podem mudar a foto de perfil que não seja a deles mesmos ;
- Ao mudar a foto de perfil, um <a href="../lexicos/lexicos-1_0/#lxTweet">Tweet</a> deve ser automaticamente postado pelo sistema.

<span id="US04"></span>
### <a href="#US04">**[US04]**</a> Eu, como usuário, desejo poder escolher outro nome de usuário (@).

#### Critérios de aceitação:
- A opção de ter um nome de usuário deve existir ;
- O usuário pode mudar o nome dele (@) a qualquer instante ;
- O sistema deve verificar se o nome escolhido pelo usuário está disponível ;
- O nome de usuário deve aparecer logo abaixo da foto de perfil ;

<span id="US05"></span>
### <a href="#US05">**[US05]**</a> Eu, como usuário, desejo ter uma descrição de perfil e que esta seja editável.

#### Critérios de aceitação:
- A opção de ter uma descrição de perfil deve existir ;
- A descrição de perfil não pode ultrapassar 160 caracteres ;
- A descrição de perfil deve ser visível para qualquer outro usuário, mesmo que este não siga o perfil em questão;
- A descrição de perfil deve estar localizada abaixo do nome de usuário ;
- A descrição de perfil pode ser vazia ;
- Bio deve ser uma outra maneira de falar "Descrição de perfil" ;

<span id="US06"></span>
### <a href="#US06">**[US06]**</a> Eu, como usuário, desejo ter controle sobre quais usuários podem visualizar minhas informações (dados do perfil, tweets etc).

#### Critérios de aceitação:
- O usuário pode bloquear outro usuário ;
- O usuário pode escolher, dentre as informações do perfil dele, quais são públicas (visíveis a todos) e quais são privadas (visíveis apenas para aqueles que o seguem) ;
- O usuário deve ser capaz de escolher se o perfil dele será "público" ou "privado";
- O usuário pode mudar, a qualquer instante, a confidencialidade do perfil dele como um todo (para "público" ou para "privado") ;
- O usuário pode desbloquear outro usuário que estava outrora bloqueado.

<span id="US07"></span>
### <a href="#US07">**[US07]**</a> Eu, como usuário, desejo buscar qualquer termo na barra de pesquisa

#### Tarefas:
-

#### Critérios de aceitação:
- O usuário pode inserir um texto de no máximo 500 caracteres
- O usuário pode cometer erros de digitação e deve encontrar tópicos sugeridos

<span id="US08"></span>
### <a href="#US08">**[US08]**</a> Eu, como usuário, desejo buscar uma hashtag na barra de pesquisa

#### Tarefas:
-

#### Critérios de aceitação:
- O usuário pode inserir uma hashtag de no máximo 100 caracteres
- O usuário pode cometer erros de digitação e deve encontrar hashtags sugeridas
- O usuário deve visulizar as hashtags com maior engajamento de forma ordenada
- O usuário pode filtrar a localização de busca da hashtag

<span id="US09"></span>
### <a href="#US09">**[US09]**</a> Eu, como usuário, desejo conferir tópicos sugeridos baseados no meu interesse na barra de pesquisa

#### Tarefas:
-

#### Critérios de aceitação:
- O usuário deve visualizar tópicos similares sugeridos ao buscados na barra de pesquisa
- O usuário pode clicar em um tópico sugerido e ser redirecionado para o mesmo

***
## Referências

1. **[Ebrary]** Young, Ralph. Requirements Engineering Handbook. Norwood, US:
Artech House Books, 2003.
2. **[Open Access]** Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de
Requisitos. <a href="http://livrodeengenhariaderequisitos.blogspot.com.br/">**http://livrodeengenhariaderequisitos.blogspot.com.br/**</a> (último acesso:
2019)

***

## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 20/10/2019 | Aline Laureano | Criação da página e dos textos descritivos, adição de algumas referências & inserção das US's relacionadas ao épico Cadastro e ao épico Central de ajuda com os links necessários. | 0.1 |
| 21/10/2019 | Erick Giffoni | Adição das USs referentes ao épico Gerenciar Perfil e algumas correções | 0.2 |
| 21/10/2019 | Eugênio Sales | Adição das USs referentes ao épico de Pesquisa | 0.3 |
