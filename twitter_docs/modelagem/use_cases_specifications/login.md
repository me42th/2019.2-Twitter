<span style="margin-left: 40%;">![Twitter Logo](../../images/twitter-logo-100px.png)</span>

***
# Caso de Uso: Efetuar Login

***
##Diagrama

***
**Autore(s):** Bruno Henrique, Eugênio Sales e Aline Laureano. </br>
**Versão:** *0.2 (última versão)*

<span style="margin-left: 10%;">![Login Use Case](../images/v2-UC-Login.jpg)</span>

***
**Autores:** Bruno Henrique e Eugênio Sales.</br>
**Versão:** *0.1*

<span style="margin-left: 10%;">![Login Use Case](../images/UC-Login.png)</span>

***
##Especificações
***

### <a href="#">UC01</a> - Efetuar Login
**Autores:** Bruno Henrique e Eugênio Sales.</br>
**Versão:** *0.1*

|  |  |
|------|-------|
| **Descrição** | Autenticar o acesso do usuário a rede social, tendo acesso a todo conteúdo relacionado a suas especificações e interações. |
| **Ator(es)** | Usuário |
| **Pré-Condições** | * Possuir cadastro/conta no Twitter </br> * Acesso a Internet <br/> * Aplicativo mobile ou desktop|
| **Pós-Condições** | Acesso a homepage e funcionalidades existentes no sistema |
| **Fluxo Princtipal** |[FP01] Este fluxo é necessário para o usuário utilizar/acessar o sistema<br/>1. O ator abre o aplicativo do twitter </br> 2. O sistema fornece a página de login </br> 3.  O ator fornece os campos de username e senha<br/> 4. O ator clica em "Entrar" <br/> 5. O sistema autentica o usuário e seus dados|
| **Fluxo(s) Alternativos** | [FA01] Este fluxo relata o primeiro contato do usuário com a plataforma<br/>1. O ator abre o aplicativo do twitter </br> 2. O sistema fornece a página de login e sing up </br> 3. O sistema fornece parte de cadastro(sing up) <br/> 4. O ator cadastra seus dados <br/> 5. O sistema busca identificar e confirmar a identidade do futuro usuário<br/>6. O sistema autentica o usuário e seus dados |
| **Fluxo(s) de exceção** | [FE01-A] O fluxo a seguir exprime uma adversidade do usuário no sistema<br/> 1. O ator abre o aplicativo do twitter <br/> 2. O sistema fornece a página de login <br/>3. O ator não se recorda de suas credenciais de acesso<br/>4. O sistema oferece suporte de recuperação de credenciais <br/> 5. O sistema fornece refatoração dos daos<br/> 6. O sistema autentica o usuário e seus dados <br/> [FE01-B] O usuário não possui acesso a Internet|
||

### <a href="#">UC02</a> - Efetuar Cadastro

**Autore(s):** Aline Laureano. </br>
**Versão:** *0.1*

|  |  |
|------|-------|
| **Descrição** |Funcionalidade responsável por cadastrar novos usuários na aplicação. |
| **Ator(es)** | Visitante e Usuário. |
| **Pré-Condições** | O Visitante deve ter conexão com a internet. |
| **Pós-Condições** | O Visitante terá uma nova conta cadastrada no Twitter.</br>O Visitante vai se tornar um novo Usuário da aplicação.|
| **Fluxo Principal** | [FP01] Fluxo iniciado quando um Visitante deseja se cadastrar no Twitter:</br>1. O Visitante clica em “Inscrever-se”;</br>2. O Visitante digita o seu nome e o seu número de celular;</br>3. O Visitante clica em “Avançar”;</br>4. O Visitante seleciona as opções para personalizar a experiência dele com o Twitter;</br>5. O Visitante clica em “Avançar” novamente;</br>6. O Visitante confirma os seus dados e clica em “Inscrever-se”;</br>7. O Visitante recebe um código de verificação no seu celular;</br>8. O Visitante digita o código de verificação na página de cadastro do Twitter;</br>9. O Visitante digita o seu nome de usuário do Twitter;</br>10. O Visitante é redirecionado como Usuário para uma a sua conta cadastrada no Twitter. |
| **Fluxo(s) Alternativos** | - |
| **Fluxo(s) de exceção** | [FE01] Falha de conexão com a internet:</br>No passo 1 do [FP01] ocorre uma falha de conexão com a Internet. |

***

## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 27/09/2019 | Bruno Henrique | Adição descrição e atores| 0.1 |
| 27/09/2019 | Eugênio Sales | Adição de fluxos alternativos e excessão | 0.2 |
| 27/09/2019 | Erick Giffoni | Melhorias na edição da página | 0.2.1 |
| 30/09/2019 | Bruno Henrique | Refatorando a página | 0.2.2 |
| 25/11/2019 | Aline Laureano | Padronização do layout desta página com as demais páginas de Casos de Uso e adição da:</br>- Versão 0.2 do diagrama;</br>- Versão 0.1 da UC02.  | 0.3 |
