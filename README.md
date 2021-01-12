<h1 align="left">
  Primeiros Passos com <a href="https://dart.dev/">Dart</a>
</h1>

<h3 align="center">Conhecendo a Linguagem</h3>

<h5 align="left">Introdução ao Dart</h5>

<ul>
  <li><a href="https://dartpad.dev/?">DartPad</a></li>
</ul>

<hr />

<h5 align="left">
  <a href="https://github.com/lucasrmagalhaes/primeirosPassosComDart-DIO/blob/master/dart/primeiroCodigo.dart">primeiroCodigo.dart</a>
</h5>

<hr />

<h3 align="center">Trabalhando com Variáveis</h3>

<h5 align="left">String, int e double</h5>

```
void main() {
  
  // Criando um produto.
  String produto = "Arroz";
  
  // Quantidade de sacos de arroz.
  int quantidade = 20;
  
  // Preço do arroz.
  double preco = 10.99;
  
  print(produto);
  print(quantidade);
  print(preco);
  
}
```

<hr />

<h5 align="left">Bool e concatenação</h5>

<pre>
void main() {
  
  // Criando um produto.
  String produto = "Arroz";
  print(produto);
  
  // Quantidade de sacos de arroz.
  int quantidade = 20;
  
  // Preço do arroz.
  double preco = 10.99;
  
  print(produto);
  print(quantidade);
  print(preco);
  
  bool entrega = true;
  
  produto = "Arroz Branco";
  print("O $produto está $preco");
  
}
</pre>

<pre>
Console

Arroz
Arroz
20
10.99
O Arroz Branco está 10.99
</pre>

<hr />

<details>
    <summary>Certifique seu conhecimento</summary>

<h1 align="center">Certifique seu conhecimento</h1>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>O operador ++, tem por objetivo:
</strong><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Incrementar em um o valor de uma variável ou expressão.
 <br />
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Qual das seguintes linhas não é permitido por Dart?
</strong><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;bool entrega = 1;
 <br />
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Qual dessas operações nos mostrará um erro?
</strong><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;int valor1 = 10; double valor2 = 20; int valor3 = valor1* valor2;
 <br />
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>O operador  ==, tem por objetivo:
</strong><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Comparar o valor de duas expressões e retornar um valor lógico dessa comparação em formato bool, verdadeiro ou falso.
 <br />
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>Qual a maneira correta de declarar a variavel Produto, que é do tipo String em Dart?
</strong><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;String Produto;
 <br />

</p>

</details>