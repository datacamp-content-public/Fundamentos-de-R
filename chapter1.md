---
title: 'Template Chapter 1'
description: 'This is a template chapter.'
---

## Como fazer este curso

```yaml
type: NormalExercise 
lang: r
xp: 100 
skills: 1
key: 9f723bb0b0   
```


No editor à direita, você deverá digitar códigos em R para resolver os exercícios. Quando você clicar no botão amarelo "Submit Answer", cada linha do código será interpretada e executada pelo R. Em seguida, você receberá uma mensagem se o seu código está correto ou não. A saída do seu código em R será mostrada no console no canto inferior direito.

R faz uso do sinal de `#` para adicionar comentários, a fim de permitir a você e outras pessoas entenderem o funcionamento do seu código. Igual no Twitter! Comentários não são executados como um código em R, então eles não irão influenciar no seu resultado. Por exemplo, no editor à direita, `# Calcule 3 + 4` é um comentário.

Você pode também executar comandos em R diretamente no console ao lado. Esta é uma boa forma de experimentar novos códigos em R, já que sua submissão não será corrigida ou validada.


`@instructions`
- O editor à direita possui um código de exemplo. Você consegue identificar quais linhas são códigos em R e quais são comentários?
- Adicione uma linha de código que calcule a soma de 6 + 12, e clique no botão ‘Submit Answer’.

`@hint`
Adicione uma linha em R que calcule 6 + 12, exatamente igual ao código de exemplo!

`@pre_exercise_code`

```{r}

```


`@sample_code`

```{r}
# Calcule 3 + 4
3 + 4

# Calcule 6 + 12

```


`@solution`

```{r}
# Calcule 3 + 4
3 + 4

# Calcule 6 + 12
6 + 12
```


`@sct`

```{r}
source("http://bit.ly/carregaR")
test_output_contains("18", incorrect_msg = "Tenha certeza que você inseriu uma nova linha que some 6 + 12. Não inicie esta linha com um `#`, senão o código não será executado!")
success_msg("Parabéns! Veja como o console mostra você o resultado do seu código. Agora, já que você está familiarizado com a interface do curso, vamos aprender R!")
```


---

## <<<New Exercise>>>

```yaml
type: NormalExercise 
lang: r
xp: 100 
skills: 1
key: ea55f984b3   
```





`@instructions`


`@hint`


`@pre_exercise_code`

```{r}

```


`@sample_code`

```{r}

```


`@solution`

```{r}

```


`@sct`

```{r}

```


