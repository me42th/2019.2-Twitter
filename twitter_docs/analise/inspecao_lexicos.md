<span style="margin-left: 40%;">![Twitter Logo](../images/twitter-logo-100px.png)</span>

***

# Inspeção - Léxicos


## <a href="#">**Verificação**</a>

### Critérios de aceitação - _Check-list_

**Autor dos critérios:** Bruno Duarte

> 1. Os Léxicos contemplam o conjunto de entidades de entidades necessárias? (*Referência 04*)

> 2. A noção descreve o significado e as
relações fundamentais de existência do símbolo
com outros símbolos? (*Referência 03 e 04*)
 

> 3. O impacto descreve a repercussão do símbolo(léxico) no sistema? (*Referência 01*)

> 4. Circularidades (HyperLex) funcionando corretamente (*Referência 03*)

> 5. Princípio do Vocabulário Mínimo (*Referência 01*)

> 6. A Classificação do Léxico é coerente com o que está sendo descrito? (*Referência 03*)

> 7. Os Léxicos estão descritos em linguagem natural para uma comunicação saudável entre os *stakeholders (*Referência 02*)

> 8. Quantidade significativa de léxicos gerados (*Feedback Ponto de Controle 3*)

---

### Resultados da avaliação técnica inicial

*Versão do artefato:* 0.2 </br>
*Link para o artefato:* <a href="../../modelagem/lexicos/lexicos">**[Léxicos]**</a> </br>
*Autor da avaliação técnica:* Bruno Duarte</br>

| Critério nº | Atende ao critério? | Classificação do defeito | Tipo do defeito | Pontos a serem trabalhados |
|-------------|---------------------|--------------------------|-----------------|----------------------------|
| 1 | Sim | - | - |  - |
| 2 | Não| Mediano | Mínimo | Algumas noções não contemplam as relações com outros léxicos|
| 3 | Não | Simples | Mínimo | Alguns hyperlinks podem ser "forçados" nos Impactos do Sistema |
| 4 | Sim | - | - | - |
| 5 | Não | Mediano | Grave | Alguns detalhamentos acerca dos léxicos estão um pouco extensivos o que pode prejudicar a compreensão de terceiras pessoas acerca do projeto. Sintetizar algumas descrições seria viável. |
| 6 | Não | Simples| Mínimo | Conferir se a classificação condiz de fato com o que está sendo detalhado. |
| 7 | Sim | - | - | - |
| 8 | Não | Simples | Mínimo | A Confecção de mais léxicos pode ser útil para relacionar os artefatos(Hyperlex) e gerar maior abragência de informações do sistema |

---


### Levantamento de Dados a partir da Avaliação

| Critério | Quantidade de Cenários que Atendem o Critério | Quantidade de Cenários que **Não** Atendem o Critério |Cenários a serem Refatorados|
|-------------|---------------------|--------------------------|-----------------|
| Os Léxicos contemplam o conjunto de entidades de entidades necessárias |   12 | 0 |Trending, Tweet, Efetuar Login, Interações com Postagens, Notificações, Seguidor, Direct Message, Tweetar, Perfil, Para Você, Twitter, Hashtag|
| A noção descreve o significado e as relações fundamentais de existência do símbolo com outros símbolos? | 8 | 4 | Twitter, Login, Perfil, Para Você |
| O impacto descreve a repercussão do símbolo(léxico) no sistema? | 10 | 2 | Perfil, Para Você|
|Circularidades (HyperLex) funcionando corretamente| 12 | 0 | - |
| Princípio do Vocabulário Mínimo| 8 | 4 | Trending, Interações com Postagem, Perfil, Hashtag |
| A Classificação do Léxico é coerente com o que está sendo descrito? | 10 | 2 | Interação com postagens, Notificações|
| Os Léxicos estão descritos em linguagem natural para uma comunicação saudável entre os stakeholders | 12 | 0 |-|

## <a href="#">**Validação**</a>
***
### Validação por *Persona*

***
#### Definição da *Persona*
> *Autor:* Bruno H. Sousa Duarte</br>

Josué é um adolescente de 17 anos, que trabalha em um emprego de meio período e estuda no Cursinho preparatório para vestibulares. Utiliza o twitter pois é uma rede social que não tem pessoas mais próximas a ele também gosta de publicar e expressar suas opiniões em *threads*. Devido a sua curiosidade com o aplicativo, Josué possui acervo das ações e funcionalidades do sistema e prontificou-se a ajudar no levantamento de informações. 

***
#### Resultado da Validação por persona - na visão da *Persona*

Josué acabou informando diversos tópicos e contextos que podem ser utilizados como léxicos, até mesmo em questões de segurança. Josué soube se expressar e exemplificou as ações em seu próprio perfil. Josué pediu como recompensa que os entrevistadores seguissem seu perfil e twittou positivamente sobre o ocorrido, porém reclamou que não teve lanche.


***
### Validação por técnica
> *Autor:* Bruno H. Sousa Duarte</br>

Os critérios propostos no checklist foram satisfeitos e refatorados quando necessários, haviam poucos pontos a serem refatorados e foram atendidos. Como bônus houve a realização de mais léxicos que agora seguem um padrão pré-definido.

***
## Referências

1. Leite, Julio & Silva, Lyrene & Breitman, Karin. (2005). C&L: Uma Ferramenta de Apoio à Engenharia de Requisitos.. RITA. 12. 23-46. 

2. NITSCHE, Raquel; DE BORTOLI, Lis Ângela. E-LAL: Um Editor Para o Léxico Ampliado da Linguagem. INFOCOMP Journal of Computer Science, [S.l.], v. 5, n. 3, p. 59-67, sep. 2006. ISSN 1982-3363. Available at: <http://www.dcc.ufla.br/infocomp/index.php/INFOCOMP/article/view/144>. Date accessed: 03 nov. 2019

3. CUNHA, Lucas Gonçalves. Tool for elicitation of goals from language extended lexicon. 2014. 102 f. Dissertação (Mestrado em Metodologias e técnicas da Computação; Sistemas de Computação) - Universidade Federal de Viçosa, Viçosa, 2014

4. **[C&L]** <a href="http://pes.inf.puc-rio.br/cel/index_old.htm"> Uma ferramenta para Edição e Visualização de Cenários e Léxicos.</a>
---


## Versionamento de edições desta página


| Data       | Autor            | Descrição         | Versão |
| ---------- | ---------------- | ----------------- | ------ |
| 03/11/2019 | Bruno Duarte | Criação da Página | 0.1    |
| 03/11/2019 | Bruno Duarte | Adicionando Checklist de Verificação (Léxicos)| 0.2    |


***

