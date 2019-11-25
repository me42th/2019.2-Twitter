<span style="margin-left: 40%;">![Twitter Logo](../images/twitter-logo-100px.png)</span>

---

# Inspeção - Cenários

---

## Cenários

## <a href="#">**Verificação**</a>

### Critérios de aceitação - _Check-list_

**Autor dos critérios:** Bruno Duarte


> 1. A quantidade atual de cenários consegue cobrir um número satisfatório de possíveis eventos pertinentes a interação do usuário com o Twitter? (*Referência 1*)

> 2. Não possuem ambiguidades e redundâncias (*Referência 1*)

> 3. Objetivos Precisos e Concretos  (*Referência 1 e 2*)

> 4. Hyperlinks funcionando corretamente (*Referência 3*)

> 5. Os Cenários contemplam todos os tópicos necessários para realização da estratégia? (*Referência 3*)

> 6. O tempo presente deve ser preferido na descrição
episódios. (*Referência 2*)

> 7. Todos os atores mencionados nos episódios estão
incluidos no componente ator? (*Referência 4*)

> 8. Nível de detelhamento semelhante entre os Cenários (*Referência 2*)

> 9. A entidade **Contexto** apresenta a **Localização** e a **Pré-Condição** do cenário descrito (*Referência 4*)
***

### Avaliação técnica inicial

***

*Versão do artefato:* 0.2 </br>
*Link para o artefato:* <a href="../../modelagem/cenarios/cenarios-1_0.md">**[Cenários]**</a> </br>
*Autor da avaliação técnica:* Bruno Duarte</br>

| Critério nº | Atende ao critério? | Classificação do defeito | Tipo do defeito | Pontos a serem trabalhados |
|-------------|---------------------|--------------------------|-----------------|----------------------------|
| 1 | Não | Grave | Máximo | Os **membros do grupo** deverão criar mais cenários para mapear e maximizar as possibilidades do usuário na plataforma |
| 2 | Não| Mediano | Mínimo |  Alguns Cenários podem ser sintetizados em um único cenário. Exemplo: O cenário comentar tweet pode ser merjado no cenário de criar tweets |
| 3 | Sim | - | - | - |
| 4 | Não | Simples | Mínimo | Linkar corretamente os respectivos cenários e léxicos nas tabelas de documentação |
| 5 | Sim | - | - | - |
| 6 | Sim | - | - | - |
| 7 | Não | Simples| Mínimo | Alguns atores não estão descritos na entidade **Atores**. Em alguns casos não incluiram o próprio sistema como ator do cenário. |
| 8 | Sim | - | - | - |
| 9 | Não | Mediano | Mediano | Na parte de **Contexto** não especificam-se a *Pré-Condição* nem a *Localização* do Cenário  |

---


### Levantamento de Dados a partir da Avaliação

| Critério | Quantidade de Cenários que Atendem o Critério | Quantidade de Cenários que **Não** Atendem o Critério |Cenários a serem Refatorados|
|-------------|---------------------|--------------------------|-----------------|
| Não possuem ambiguidades e redundâncias |   5 | 1 |Comentar Tweets |
| Objetivos Precisos e Concretos | 6 | 0 | - |
| Hyperlinks Funcionando Corretamente | 0 | 6 | Trending Topics, Login, Enviar Mensagem, Criar Tweets, Explorar Comentar Tweets|
|Os Cenários contemplam todos os tópicos necessários para realização da estratégia | 6 | 0 | - |
| O tempo verbal presente deve ser preferido na descrição episódios | 6 | 0 | - |
| Todos os atores mencionados nos episódios estão incluidos no componente ator? | 1 | 5 | Trending Topics, Enviar Mensagem, Criar Tweets, Explorar Comentar Tweets |
| A entidade Contexto apresenta a Localização e a Pré-Condição do cenário descrito | 0 | 6 | Trending Topics, Login, Enviar Mensagem, Criar Tweets, Explorar Comentar Tweets |
---
## <a href="#">**Validação**</a>
Validação realizada somente nos artefatos que forem refatorados segundo a avaliação técnica acima.

***
### Validação por *Persona*

***
#### Definição da *Persona*
> *Autor:* Bruno H. Sousa Duarte</br>

Calebe é um jovem de 24 anos, que cursa Economia. Para passar o tempo e ficar por dentro dos memes e novidades do Brasil e no mundo, Calebe gostaria de uma rede social mais discreta e eficiente em relação a outras redes, por esses motivos decidiu usar o Twitter. Calebe era uma pessoa que tinha bastante contato com a rede social, ele era o candidato perfeito para validar e indicar cenários de como é sua interação com o aplicativo.

***
#### Resultado da Validação por persona - na visão da *Persona*

Calebe gostou de ver que seu *hobbie* poderia ajudar na pesquisa de universitários e procurou mapear todos os cenários. Calebe indicou títulos e caminhos de como realizava as ações e possíveis excessões. Calebe gostou de participar da entrevista e da forma informal que os dados foram coletados e aprovou a forma não burocrática de levantar informações de usuários.
***
### Validação por técnica
> *Autor:* Bruno H. Sousa Duarte</br>

Os critérios propostos no checklist foram satisfeitos e refatorados. Além disso houve a realização de mais cenários que também seguiram o padrão solicitados.

***
## Referências

1. Leite, J.C.S.P., Hadad, G.D.S., Doorn, J.H., Kaplan, G.N.: A Scenario Construction
Process, Requirements Engineering Journal, Vol.5, N° 1, 2000, pp. 38-61

2. Hsia, P.et al: Formal Approach to Scenario Analysis. IEEE Software, vol. 11 no. 2,1994. pp.33-41.

3. Leite, Julio & Rossi, Gustavo & Balaguer, Federico & Maiorana, Vanesa & Kaplan, Gladys & Hadad, Graciela & Oliveros, Alejandro. (1997). Enhancing a requirements baseline with scenarios. Requirements Engineering. 2. 184-198. 10.1007/BF02745371. 

4. **[C&L]** <a href="http://pes.inf.puc-rio.br/cel/index_old.htm"> Uma ferramenta para Edição e Visualização de Cenários e Léxicos.</a>
---


## Versionamento de edições desta página


| Data       | Autor            | Descrição         | Versão |
| ---------- | ---------------- | ----------------- | ------ |
| 03/11/2019 | Bruno Duarte | Criação da Página | 0.1    |
| 03/11/2019 | Bruno Duarte | Adicionando Checklist de Verificação | 0.2    |


***
