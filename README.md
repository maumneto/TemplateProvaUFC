# **Modelo de Prova e Lista de Exercícios**

[Read this page in English](README-en.md)
## **Sobre**

Esse projeto tem o objetivo de criar um template para provas e listas de exercícios para a Universidade Federal do Ceará (UFC). Para isso, foi criado um arquivo de estilização **documentufc.sty**, o qual possui um conjunto de ambientes e comandos relacionados a este documento.

Este documento é direcionado aos professores da UFC que desejam ter um template LaTeX para suas avaliações e/ou listas de exercícios.

## **Dicas**

Se você precisa inserir questões:
```tex
\begin{question}
    \item Descrição da Questão.
\end{question}
```

Se você precisa inserir questões de multipla escolhas:
```tex
\begin{multiplechoices}
    \choice item 1
    \choice item 2
    \choice item 3
    \choice item 4
\end{multiplechoices}
```

Use o comando **\pontuation{valor}** caso precise inserir a pontuação para determinada questão:
```tex
\begin{question}
    \item Question Description.\pontuation{3.5}
\end{question}
```

## **Autor**
<b>Desenvolvido por Maurício Moreira Neto</b>

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maumneto@gmail.com)[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maumneto/)[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@maumneto)[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maumneto)