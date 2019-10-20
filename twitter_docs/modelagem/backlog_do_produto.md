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

|Épico | ID |	Eu como |	Desejo |	Para que eu possa |	Tarefas & Critérios de aceitação |	Rastro |
|------|----|---------|--------|--------------------|----------------------------------|---------|
|Cadastro | <a href="#US01">**[US01]**</a> | Visitante |	Realizar cadastro | 	Me tornar um usuário do Twitter. | <a href="#US01">**Link para a [US01]**</a> | <a href="../use_cases_specifications/user_case_geral/#UC02">**UC02;**</a> <a href="../use_cases_specifications/login/">**Caso de uso - Login;**</a> <a href="../../elicitacao/requisitos/#R030">**R030;**</a> |
|Central de ajuda| <a href="#US02">**[US02]**</a> | Usuário |	Acessar a central de ajuda | 	Sanar dúvidas sobre o funcionamento e a utilização do Twitter. | <a href="#US02">**Link para a [US02]**</a> | <a href="../use_cases_specifications/user_case_geral/#UC20">**UC20;**</a> <a href="../../elicitacao/storytelling/#storytelling01">**Storytelling 01;**</a> |

***

## Lista das Histórias de usuário

<span id="US01"></span>
### <a href="#US01">**[US01]**</a> Eu, como usuário, desejo realizar cadastro.
#### Tarefas:
- Criar página de cadastro para o Twitter;
- Montar integração e validação do número de telefone do visitante com a conta a ser criada;
- Montar cadastro do nome usuário único para a conta a ser criada.

#### Critérios de aceitação:
- O visitante deve ser capaz de acessar a página de cadastro do Twitter;
- O visitante deve conseguir validar o seu número de celular inserindo um código de confirmação enviado pelo Twitter por SMS;
- Após a validação, o visitante é redirecionado para a sua conta de usuário do Twitter;
- Após a validação, o visitante consegue inserir o seu nome de usuário para a sua conta do Twitter.

<span id="US02"></span>
### <a href="#US02">**[US02]**</a> Eu, como usuário, desejo acessar a central de ajuda.

#### Tarefas:
- Criar página para a Central de ajuda;
- Inserir barra de pesquisa de dúvidas na página de Central de ajuda;

#### Critérios de aceitação:
- O usuário deve ser capaz de acessar a página de Central de ajuda;
- Caso exista(m) resultado(s), a barra de pesquisa retorna resultado(s) da Central de ajuda de acordo com a pesquisa feita pelo usuário.

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
