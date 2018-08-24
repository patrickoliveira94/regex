# Regex

Projeto para testes de expressões regulares

Para acessar a página clique [aqui.](https://patrickoliveira94.github.io/regex/)

## Exemplos de expressões regulares

### Extrair CPF:

```sh
Target: João Fulano,123.456.789-00,21 de Maio de 1993,(21) 3079-9987,Rua do Ouvidor,50,20040-030,Rio de Janeiro
```

```sh
Pattern 1: \d{3}\.\d{3}\.\d{3}-\d{2}
```

```sh
Pattern 2: \d{3}\.?\d{3}\.?\d{3}[.-]?\d{2}
```

* **Pattern 1:** Considera apenas a formatação padrão XXX.XXX.XXX-XX
* **Pattern 2:** Aceita outras formatações, como: XXX.XXX.XXX.XX, XXXXXXXXXXX, XXXXXXXXX-XX
 
 ### Quantifiers

```sh 
? zero ou uma vez.
```

```sh 
* zero ou mais vezes.
```

```sh 
+ uma ou mais vezes.
```

```sh 
{n} exatamente n vezes.
```

```sh 
{n,} no mínimo n vezes.
```

```sh 
{n,m} no mínimo n vezes, no máximo m vezes.
```
