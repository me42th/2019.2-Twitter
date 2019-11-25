</br>
</br>
<span style="margin-left: 40%;">![Twitter Logo](../images/twitter-logo-100px.png)</span>

***
# Especificação Suplementar

***
*Autor do documento:* Aline Laureano</br>
*Versão:* 0.1</br>

***
##Sumário

  - **[Sobre o documento:](#sobre)**
    - [Visão geral](#visaogeral);
    - [Finalidade](#finalidade);
    - [Escopo do Twitter](#escopo);
  - **[Requisitos não-funcionais:](#req_nao_funcionais)**
    - [1 - Confiabilidade](#1confiabilidade);
    - [2 - Desempenho](#2desempenho);
    - [3 - Funcionalidade](#3funcionalidade);
    - [4 - Suportabilidade](#4suportabilidade);
    - [5 - Usabilidade](#5usabilidade);
  - **[Referências](#referencias)**


***
<span id="sobre"></span>
##Sobre o documento:

<span id="visaogeral"></span>
###Visão Geral
O que mais influencia o sucesso de um software é a definição de bons requisitos não-funcionais que atendam às necessidades do seu domínio de atuação. Logo, definir requisitos não-funcionais é essencial para se desenvolver um software de qualidade.

O presente documento busca esclarecer a quais são os requisitos não-funcionais presentes no Twitter.

<span id="finalidade"></span>
###Finalidade
A finalidade desse documento é apresentar os requisitos não-funcionais do sistema do Twitter, através de:

  - Técnicas de elicitação e modelagem trabalhadas neste projeto;
  - E seguindo o modelo para classificação de atributos de qualidade de software, FURPS+.

<span id="escopo"></span>
###Escopo do Twitter
Segundo a página [*Sobre*](https://about.twitter.com/pt.html) do próprio Twitter:
> "**O Twitter é**

> o lugar certo para saber mais sobre o que está acontecendo no mundo e sobre o que as pessoas estão falando agora."

E para atingir essa finalidade, o Twitter consiste em uma rede social e um servidor para microblogging, que permite aos usuários enviar e receber atualizações pessoais de outros contatos, por meio das suas plataformas.

***
<span id="req_nao_funcionais"></span>
##Requisitos não-funcionais:

<span id="1confiabilidade"></span>
###1 - Confiabilidade

  - **Garantia de segurança mínima no armazenamento de dados:**
    - O Twitter segue critérios mínimos para a segurança do armazenamento de dados dos seus usuários.

  - **Garantia de atualização de informações pessoais:**
    - O usuário do Twitter dever poder alterar os seus dados pessoais caso desejar.

  - **Garantia de disponibilidade:**
    - O Twitter está disponível aos seus usuários tanto na plataforma Web quanto na Mobile durante 24 horas por dia, caso eles tenham acesso à Internet.

<span id="2desempenho"></span>
###2 - Desempenho
O tempo de resposta do sistema deverá ser o mínimo possível. Para garantir este desempenho, essa necessidade deverá ter uma verificação mais acurada para que sejam geradas soluções que resolvam esta questão de desempenho na fase de implementação do Twitter.

<span id="3funcionalidade"></span>
###3 - Funcionalidade
As funcionalidades do Twitter podem ser vistas nos seguintes artefatos deste projeto:

  - [Requisitos & MoSCoW](../../elicitacao/requisitos/);
  - [Backlog do Produto](../backlog_do_produto/);
  - [Caso de Uso - Geral](../use_cases_specifications/user_case_geral/);
  - [Caso de Uso - Login](../use_cases_specifications/login/);
  - [Caso de Uso - Trending Topics](../use_cases_specifications/trending_topics/);
  - [Matriz Backward-from](../../pos_rastreabilidade/backward_from/);
  - [Matriz Forward-from](../../pos_rastreabilidade/forward_from/);
  - [Matriz Geral de rastreabilidade](../../pos_rastreabilidade/matriz_geral/);

<span id="4suportabilidade"></span>
###4 - Suportabilidade
O Twitter está disponível para uso em uma plataforma Web e nas principais plataformas Mobile do mercado através dos sistemas operacionais mobile Android e IOS.

<span id="5usabilidade"></span>
###5 - Usabilidade

  - **Facilidade de uso**
    - O usuário do Twitter é capaz de utilizá-lo através de ações simples, o que torna quase desnecessário o usuário ter um treinamento prévio para a realização da maioria das ações disponíveis.

  - **Central de ajuda**
    - Caso o usuário sinta alguma dificuldade na utilização do Twitter, ele fornece em sua plataforma uma central de ajuda ao usuário capaz de sanar qualquer dúvidas que surgirem.

  - **Feedback instantâneo**
    - O Twitter tem como prioridade os resultados instantâneos inclusive para as ações realizadas pelos usuários, que sempre vão receber feedback visuais como respostas para as ações que eles executarem.

***
<span id="referencias"></span>
## Referências
1. **[Open Access]** [Twitter - Sobre.](https://about.twitter.com/pt.html) (acesso em: Novembro de 2019)
2. **[Open Access]** [Twitter - Política de privacidade.](https://twitter.com/pt/privacy) (acesso em: Novembro de 2019)
3. **[Open Access]** [Requisitos Habitica - Especificação Suplementar.](https://requisitos-habitica.netlify.com/EspecificacaoSuplementar) (acesso em: Novembro de 2019)
4. **[Open Access]** [Requisitos Medium - Especificação Suplementar.](https://williamelias.github.io/Req-01-2019-medium/modelagem/especificacao_suplementar/) (acesso em: Novembro de 2019)
5. **[Open Access]** [Requisitos NuBank - Especificação Suplementar.](https://requisitos-2017-2-nubank.github.io/Nubank/siki/esp-suplementar.html) (acesso em: Novembro de 2019)
6. **[Moodle]** Serrano, Maurício. Serrano, Milene. Aula 011: Casos de Uso e Especificação Suplementar.

***
## Versionamento de edições desta página
| Data | Autor | Descrição | Versão |
|------|-------|-----------|--------|
| 24/11/2019 | Aline Laureano | Criação da página, adição do documento de Especificação Suplementar. | 0.1 |
| 25/11/2019 | Aline Laureano | Formatação no layout da página, adição do sumário com os links internos e adição das referências. | 0.2 |
