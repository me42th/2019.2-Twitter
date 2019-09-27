<span style="margin-left: 40%;">![Twitter Logo](../../images/twitter-logo-100px.png)</span>
***
# Caso de Uso - Trending Topics
<span style="margin-left: 30%;">![Trending Topics Use Case](../images/TrendingTopics.png)</span>

**Autores:** Erick, Fernando </br>
**Versão:** 0.1

***

# Especificações

## UC021 - Clicar em um Assunto

|  |  |
|------|-------|
| **Descrição** | O usuário é capaz de abrir um tópico em destaque |
| **Ator(es)** | Usuário |
| **Pré-Condições** | * Deve haver tópicos </br> * O tópico deve estar entre os mais populares na localização |
| **Pós-Condições** | O sistema abrirá a página com [tweets](https://requisitos-de-software.github.io/2019.2-Twitter/modelagem/lexicos/lexicos/#tweet) relacionados ao tópico |
| **Fluxo Principal** | [FP21] Este fluxo se inicia quando o usuário escolhe um dos tópicos </br> 1. Ele abre o aplicativo do twitter </br> 2. Ele clica na aba buscar </br> 3. Ele seleciona [trending](https://requisitos-de-software.github.io/2019.2-Twitter/modelagem/lexicos/lexicos/#trending) <br> 4. Ele clica no tópico  |
| **Fluxo(s) Alternativos** | * [FA21-A] O usuário não clica em nenhum tópico </br> * [FA21-B] O usuário [reporta](#uc23-reportar) o tópico  |
| **Fluxo(s) de exceção** | [FE21] O sistema apresenta uma mensagem de erros e [atualiza](#uc24-atualizar) a página |


## UC22 - Mudar Localização

| | |
|------|-------|
| Descrição | O usuário pode mudar a localização dele no aplicativo para conseguir visualizar [trending topics](https://requisitos-de-software.github.io/2019.2-Twitter/modelagem/use_cases_specifications/trending_topics/#caso-de-uso-trending-topics) relevantes </br>daquela região|
| Ator(es) | Usuário |
| Pré-Condições | * Sistema está funcionando |
| Pós-Condições | * O app volta para a tela anterior </br> * O usuário clica em "done" |
| Fluxo Principal | [FP22] Esse fluxo se inicia quando o usuário, a partir da tela "trending", clica no ícone de engrenagem no </br>canto superior direito e seleciona a opção de mudar localização. A partir daí ele escolhe o novo local e depois </br>conclui a tarefa clicando no ícone de concluído |
| Fluxo(s) Alternativos | * [FA22-A] O usuário seleciona o ícone da engrenagem, mas em seguida clica em voltar </br> * [FA22-B] O usuário seleciona a engrenagem, depois clica em mudar localização mas não muda efetivamente, </br>e volta para a aba anterior|
| Fluxo(s) de exceção | FE22] O sistema apresenta uma mensagem de erros e [atualiza](#uc24-atualizar) a página |


## UC23 - Reportar

| | |
|------|-------|
| Descrição | O usuário pode reportar um [trend](https://requisitos-de-software.github.io/2019.2-Twitter/modelagem/lexicos/lexicos/#trending)(assunto) de forma a classificá-lo como spam, abusivo, réplica ,não relevante </br> ou baixa qualidade|
| Ator(es) | Usuário |
| Pré-Condições | * Existir um tweet </br> * Sistema deve estar no ar|
| Pós-Condições | * O tweet será investigado pelo Twitter </br> * Usuário continua a navegar </br> * Usuário pode bloquear o autor do tweet|
| Fluxo Principal | [FP23] Esse fluxo se inicia quando o usuário seleciona a opção de reportar um assunto, a partir da tela "trending", </br>então escolhe a categoria a qual quer reportar |
| Fluxo(s) Alternativos | [FA23] O usuário seleciona a opção de reportar mas, logo em seguida, volta à tela anterior|
| Fluxo(s) de exceção | [FE23] O sistema apresenta uma mensagem de erros e [atualiza](#uc24-atualizar) a página |


## UC24 - Atualizar

| | |
|------|-------|
| Descrição | O usuário pode deslizar a tela para baixo e, dessa forma, forçar a atualização da tela "trending" |
| Ator(es) | Usuário |
| Pré-Condições | * App está funcionando |
| Pós-Condições | * A tela está atualizada </br>* Usuário continua a navegação |
| Fluxo Principal | [FP24] O usuário desliza a tela para baixo e a tela é atualizada |
| Fluxo(s) Alternativos | [FA24] O usuário não atualiza a tela porque o sistema faz isso automaticamente |
| Fluxo(s) de exceção | [FE24] O sistema apresenta uma mensagem de erros e [atualiza](#uc24-atualizar) a página |

**Autores:** Erick, Fernando </br>
**Versão:** 0.1

***

## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 26/09/2019 | Fernando Aguilar | Criação da página | 0.1 |
| 27/09/2019 | Erick Giffoni | - Melhorias na página </br> - Adição de mais especificações | 0.2 |
| 27/09/2019 | Erick Giffoni e Fernando Aguilar | Adição de mais especificações | 0.3 |
