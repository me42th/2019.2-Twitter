<span style="margin-left: 40%;">![Twitter Logo](../../images/twitter-logo-100px.png)</span>
***

# NFR Framework

<p>Diagramas desenvolvidos:</p>
  - <a href="#nfr_geral">**Diagrama Geral;**</a>
  - <a href="#nfr_seguranca">**Diagrama de Segurança;**</a>
  - <a href="#nfr_usabilidade">**Diagrama de Usabilidade;**</a>
  - <a href="#nfr_performance">**Diagrama de Desempenho ou Performance;**</a>

***

## **Diagrama Geral**

> - Junção dos NFR'S de segurança, usabilidade e desempenho

### Modelagem

<span id="nfr_geral"></span>
![NFR geral](images/geral.png)

***

## **Diagrama de Segurança**
> - **Confidencialidade:**
>     - Criptografia;
>     - Integridade do banco de dados;
>     - Termo de serviço.
> - **Unidade da conta** - Somente quem tem a senha consegue acessar a conta:
>     - Garantir o vínculo com apenas um email;
>     - Autenticação:
>         - Conferir se a conta existe:
>             - O nome de usuário e a senha fornecidos não correspondem às informações em nossos registros. Verifique-as e tente novamente.
>         - Autenticação de dois fatores:
>             - Email;
>             - SMS;
>             - Google Authentication.
>         - Não sou um robô;
>         - Sistema contra ataque de busca exaustiva de chave.
>     - Recuperação de senha:
>         - Via email;
>         - Via pergunta de segurança.
>     - Redefinir senha;
> - **Redundância:**
>     - Backup do banco de dados.

### Modelagem

<span id="nfr_seguranca"></span>
![NFR Twitter Segurança](images/NFR-Seguranca.png)

***

## **Diagrama de Usabilidade**
> - **Visabilidade eficiente do Status do Sistema:**
>     - Ver posts publicados em tempo real;
>     - Atualização automática do feed.
> - **Facilidade de Uso:**
>     - Uso de linguagem apropriada:
>         - Uso de linguagem própria relacionada às ações do usuário.
>     - Ícones intuitivos:
        - Ícones com legendas auto-explicativas.
> - **Design e estética razoávelmente intuitiva:**
>     - Aparência agradável ao usuário:
>         - Aplicar o design da aplicação em todas as áreas delas;
>         - Utilizar uma paleta de cores para o design da aplicação.

### Modelagem

<span id="nfr_usabilidade"></span>
![NFR Twitter Usabilidade](images/NFR-Usabilidade.jpg)

***

## **Diagrama de Desempenho ou Performance**
> - **Espaço:**
>     - Datacenters.
> - **Tempo de resposta:**
>     - Taxa de transferência.
>         - Usar formato descompactado;
>         - Usar indexação.

## Modelagem

<span id="nfr_performance"></span>
![NFR Twitter Performance](images/NFR-Performance.png)

***

## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 20/10/2019 | Fernando Aguilar | Criação da página e ajuste para a adição do diagrama de segurança. | 0.1 |
| 21/10/2019 | Bruno Duarte | Ajuste da página para a adição do diagrama de performance. | 0.2 |
| 21/10/2019 | Eugênio Sales | Ajuste da página para a adição do diagrama de performance. | 0.3 |
| 21/10/2019 | Aline Laureano e Lorrany Azevedo | Ajuste da página para a adição do diagrama de usabilidade. | 0.4 |
| 21/10/2019 | Lorrany Azevedo | Ajuste da página para a adição do diagrama Geral. | 0.5 |
| 22/10/2019 | Aline Laureano | Padronização do layout da página e adição dos links internos para os diagramas. | 0.6 |
