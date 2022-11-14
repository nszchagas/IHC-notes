---
title: Atividade Avaliativa 2 - Avaliação de um Site
author: "Nicolas Chagas Souza (20/0042327)"
date: 13/11/2022 
geometry: left=2cm,right=2cm,top=1cm,bottom=2cm
output: 
    pdf_document:
        extra_dependencies: ["float"]
---

## Introdução

O site [Resultados - TSE](https://resultados.tse.jus.br/oficial/app/index.html#/eleicao/resultados) tem como objetivo apresentar os resultados, estatísticas e dados das urnas referentes às eleições. O site destina-se a todos interessados nos resultados da eleição, um perfil de usuários com 16 anos ou mais, eleitores e com maior familiaridade com tecnologia, haja vista que os resultados também podem ser acompanhados pelo noticiário.

## Avaliação Heurística

A metodologia de avaliação escolhida foi a **avaliação heurística**, que consiste em uma inspeção sistemática da interface, em busca de problemas de usabilidade. A inspeção baseia-se em diretrizes de usabilidade, chamadas heurísticas. Na seção seguinte estão descritas as heurísticas que foram avaliadas.

## Metodologia

Ao longo da avaliação foram levadas em consideração as seguintes heurísticas, identificadas por códigos para facilitar a citação.

| Código | Descrição |
| :-: | - |
| H1 | Visibilidade do estado do sistema |
| H2 | Correspondência entre o sistema e o mundo real |
| H3 | Controle e liberdade do usuário |
| H4 | Consistência e padronização |
| H5 | Reconhecimento em vez de memorização |
| H6 | Flexibilidade e eficiência de uso |
| H7 | Projeto estético e minimalista |
| H8 | Prevenção de erros |
| H9 | Ajuda ao usuário para reconhecer, diagnosticar e recuperar-se de erros |
| H10 | Ajuda e documentação |
: Heurísticas

A avaliação foi realizada pelo avaliador Nicolas Chagas Souza.

## Dados Coletados

A avaliação revelou três problemas de usabilidade, que estão descritos a seguir.

### Problema 1

Abaixo estão registradas as figuras que ilustram o primeiro problema identificado, que é uma violação da heurística H2 - correspondência entre o sistema e o mundo real. As nomenclaturas **totalização**, **RDV** e **log** utilizadas nos menus estão distantes da realidade do público alvo.

![Menu de navegação.](imgs/20-06-37.png)

![Página de Dados de Urna](imgs/20-07-06.png)

| **Correspondência entre o sistema e o mundo real** |
| - |
| **Verificação:** $\newline$  O vocabulário e ícones utilizados no sistema está de acordo com o repertório cultural do público alvo? |
|  **Grau de severidade:** $\newline$  ($\ \ $) 0 - Sem importância $\newline$ ($\ \ $) 1 - Cosmético $\newline$ (X) 2 - Pequeno $\newline$ ($\ \ $) 3 - Grande $\newline$ ($\ \ $) 4 - Catastrófico |
| **Descrição do problema**:
| **Local:** Menu de navegação superior e página de dados da urna, que pode ser acessada pelo menu de navegação.
| **Causa:** As nomenclaturas utilizadas (**totalização, RDV** e **log**) não estão de acordo com o repertório cultural do usuário.
| **Efeito sobre o usuário:** Breve confusão.
| **Efeito sobre a tarefa:** Nenhum.
| **Correções possíveis:** $\newline$ - Adicionar um texto de explicação sobre o menu que apareça quando o usuário posicionar o cursor sobre a tela. $\newline$  - Inclusão de um subtítulo no menu indicando o significado dessas palavras. $\newline$  - Alteração de **log** por **relatório**.|
:Relato de resultados - Problema 1

$\pagebreak$

### Problema 2

Abaixo está ilustrado o segundo problema identificado, a configuração da pesquisa não é intuitiva para o usuário.

![Ausência de indicativo de onde fazer a configuração da pesquisa](imgs/20-08-04.png){width=90%}

O caminho para configurar a pesquisa está ilustrado abaixo.

![Primeiro passo: definir a localização](imgs/20-44-38.png){width=90%}

![Segundo passo: selecionar a cidade](imgs/20-44-48.png){width=90%}

![Terceiro passo: selecionar a zona e a seção](imgs/20-44-56.png){width=90%}

| **Reconhecimento em vez de memorização** |
| - |
| **Verificação:** $\newline$  O usuário precisa se lembrar de uma informação para utilizar o sistema? |
|  **Grau de severidade:** $\newline$  ($\ \ $) 0 - Sem importância $\newline$ ($\ \ $) 1 - Cosmético $\newline$ (X) 2 - Pequeno $\newline$ ($\ \ $) 3 - Grande $\newline$ ($\ \ $) 4 - Catastrófico |
| **Descrição do problema**:
| **Local:** Página Dados de Urna, que pode ser acessada por meio do menu superior de navegação.
| **Causa:** As nomenclaturas utilizadas (**totalização, RDV** e **log**) não estão de acordo com o repertório cultural do usuário.
| **Efeito sobre o usuário:** Frustração.
| **Efeito sobre a tarefa:** Atraso na execução da tarefa.
| **Correções possíveis:** $\newline$ - Incluir um link no texto "configure sua pesquisa acima", que abra a janela de seleção da região. $\newline$ - Incluir um ícone de ajuda, que direcione para uma página com instruções de uso. $\newline$ |
:Relato de resultados - Problema 2

### Problema 3

| **Ajuda e Documentação** |
| - |
| **Verificação:** $\newline$  Existem páginas de ajuda ou tutoriais para auxiliar o usuário? |
|  **Grau de severidade:** $\newline$  ($\ \ $) 0 - Sem importância $\newline$ ($\ \ $) 1 - Cosmético $\newline$ (X) 2 - Pequeno $\newline$ ($\ \ $) 3 - Grande $\newline$ ($\ \ $) 4 - Catastrófico |
| **Descrição do problema**:
| **Local:** Não se aplica.
| **Causa:** Não há uma página de ajuda com perguntas frequentes e tutoriais de uso da ferramenta.
| **Efeito sobre o usuário:** Frustração.
| **Efeito sobre a tarefa:** Nenhum.
| **Correções possíveis:** $\newline$ - Incluir uma página de ajuda. $\newline$ - Incluir tutoriais de uso nas páginas do sistema.|
:Relato de resultados - Problema 2

## Referências Bibliográficas

- MACIEL, C. _et al_. Avaliação Heurística de Sítios na Web. Niterói, RJ: UFF, 2004.

- Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.
