# Exercicios Extra Frequência 3
**Exercício 1 – Classe e Herança**

Considere a classe `Funcionario` com os atributos:

* `id` (número do funcionário)
* `nome` (primeiro e último)
* `departamento` (ex.: Informática, Marketing)
* `cargo` (ex.: Júnior, Sénior)
* `anos_experiencia`

a. Crie a classe `Funcionario` com os atributos indicados.

b. Implemente um construtor para inicializar os atributos.

c. Elabore o método `mostrar_info` que apresente todos os atributos no ecrã.

d. Crie uma classe derivada chamada `FuncionarioCompleto` que inclua, além dos atributos herdados, `morada`, `cidade` e `telefone`. Esta classe deve ter o seu próprio construtor e método `mostrar_info`.

e. Crie um objeto de cada classe e desenvolva o código necessário para testar ambas.

---

**Exercício 2 – Validação de Dados**

Elabore a função `valida_nota` que receba como parâmetro a nota de um aluno. A nota deve ser um número entre 0 e 20.

a. Valide a nota utilizando tratamento de exceções.

b. Valide a nota através de uma verificação direta.

c. Desenvolva o programa principal que solicite a nota ao estudante, utilize ambas as validações e, no final, grave a nota num ficheiro chamado `nota.txt`.

---

**Exercício 3 – Classe e Lista de Objetos**

Considere a classe `Livro` com os atributos:

* `titulo`
* `autor`
* `ano_publicacao`
* `genero`

a. Crie a classe `Livro` com os atributos indicados.

b. Implemente um construtor e um método `mostrar_info` que apresente os detalhes do livro.

c. Crie uma lista com pelo menos 3 objetos `Livro`.

d. Desenvolva uma função que percorra a lista e imprima apenas os livros publicados depois do ano 2010.

---

**Exercício 4 – Validação de Dados com Texto**

Elabore a função `valida_email` que receba como parâmetro um endereço de email.

a. Valide se o email contém o caractere `@` e um domínio válido.

b. Utilize tratamento de exceções para capturar erros de formato.

c. Crie o programa principal que peça ao utilizador um email, aplique ambas as validações e, no final, grave o email num ficheiro chamado `emails.txt`.

---
**Exercício 5 – Classes e Métodos Especiais**

Considere a classe `Produto` com os atributos:

* `codigo`
* `descricao`
* `preco`
* `stock`

a. Crie a classe `Produto`.

b. Implemente um construtor e o método `__str__` para apresentar os dados de forma legível.

c. Crie um método `atualizar_stock` que receba um valor e some ao stock existente.

d. No programa principal, crie dois produtos, atualize o stock de ambos e apresente a informação final.

---

**Exercício 6 – Validação Numérica**

Desenvolva a função `valida_quantidade` que recebe a quantidade de artigos a comprar. A quantidade deve ser um inteiro positivo.

a. Valide o valor através de tratamento de exceções.

b. Valide o valor através de verificação simples.

c. No final, grave o valor validado num ficheiro `quantidade.txt`.

---

**Exercício 7 – Herança e Polimorfismo**

Considere a classe `Veiculo` com os atributos:

* `marca`
* `modelo`
* `ano`

a. Crie a classe `Veiculo` e o método `info`.

b. Crie duas classes derivadas: `Carro` e `Mota`, cada uma com um atributo adicional (por exemplo, `portas` no carro e `cilindrada` na mota).

c. Redefina o método `info` em ambas as subclasses.

d. No programa principal, crie objetos de cada tipo e apresente a informação de cada um usando polimorfismo.

---

**Exercício 8 – Manipulação de Ficheiros**

Crie um programa que peça ao utilizador três frases distintas.

a. Grave cada frase numa nova linha de um ficheiro chamado `frases.txt`.

b. Depois, leia novamente o ficheiro e apresente o número total de caracteres de cada linha.

c. Mostre o total acumulado de caracteres no final.

---

**Exercício 9 – Estruturas de Dados e Filtragem**

Considere uma lista de dicionários onde cada dicionário representa um cliente com:

* `nome`
* `saldo`
* `ativo` (True/False)

a. Crie manualmente uma lista com pelo menos 4 clientes.

b. Desenvolva uma função que devolva apenas os clientes ativos.

c. Desenvolva outra função que devolva apenas os clientes com saldo superior a 1000€.

d. No programa principal, apresente os clientes filtrados pelas duas condições.

---
**Exercício 10 – Classes e Encapsulamento**

Considere a classe `ContaBancaria` com os atributos:

* `titular`
* `saldo`

a. Crie a classe com atributos privados.

b. Implemente métodos para depositar, levantar e consultar saldo.

c. No programa principal, crie uma conta, faça um depósito, um levantamento e apresente o saldo final.

---

**Exercício 11 – Tratamento de Exceções em Operações Matemáticas**

Crie uma função `divide` que receba dois números e devolva o resultado da divisão.

a. Implemente tratamento de exceções para evitar divisão por zero.

b. Implemente uma validação simples sem recurso a exceções.

c. No programa principal, peça dois valores ao utilizador, chame ambas as verificações e grave o resultado em `resultado_divisao.txt`.

---

**Exercício 12 – Herança Múltipla**

Considere as classes:

* `Identificacao` (atributos: `id`, `nome`)
* `Acesso` (atributos: `nivel_acesso`)

a. Crie ambas as classes.

b. Crie a classe `UtilizadorSistema` que herda de ambas e adiciona o atributo `departamento`.

c. Implemente um método que apresente todos os dados.

d. Teste a classe no programa principal.

---

**Exercício 13 – Processamento de Texto**

Crie um programa que solicite ao utilizador um parágrafo.

a. Grave o parágrafo num ficheiro `texto.txt`.

b. Leia o ficheiro e conte o número de palavras.

c. Apresente também a palavra mais longa encontrada.

---

**Exercício 14 – Coleções e Ordenação**

Considere uma lista de objetos da classe `Filme`, cada um com:

* `titulo`
* `ano`
* `rating`

a. Crie a classe `Filme` com os atributos acima.

b. Crie pelo menos 4 filmes numa lista.

c. Desenvolva funções para ordenar os filmes por ano e por rating.

d. No programa principal, apresente as listas ordenadas.

---

