<!-- Título -->
# Estrutura `for()` — Teoria em C

***Conteúdo da Aula:***

Nós utilizamos o `for()` geralmente quando sabemos exatamente a quantidade de vezes que um determinado trecho de código deverá ser executado.

A sintaxe do comando `for()` em **C** é a seguinte:

```c
for (<variável de controle> = <valor inicial>; <condição de repetição>; <incremento>){
    // Código a ser repetido.
}
```

Quando estamos utilizando o comando `for()` em **C**, uma série de parâmetros precisam ser informados.

A primeira coisa que precisamos definir é a variável de controle ou indexador.

Esta variável vai ser responsável por controlar a quantidade de vezes que o `for()` já foi executado.

Nós podemos inclusive definir um valor inicial para esta variável dentro do laço `for()`.

Logo depois, nós precisamos definir com uma condição lógica a quantidade de vezes que o laço `for()` deverá ser repetido, condição esta baseada na variável indexadora.

Por fim, nós precisamos informar o que deverá ocorrer com a variável indexadora a cada execução do `for()`.

Vamos voltar à nossa condição analisada na primeira parte do curso:

* Bater a mão na mesa seis vezes.

Nós podemos implementar esta ação em **C** da seguinte forma:

```c
int batiNaMesa = 0;
for (batiNaMesa = 1; batiNaMesa <= 6; batiNaMesa++){
    printf("Eu bati na mesa");
}
```

Veja no código acima:

* Nós definimos como sendo nossa variável indexadora a variável `batiNaMesa`.

* Falamos que, assim que o `for()` iniciar sua execução, `batiNaMesa` começará com o valor 1, valor este que será incrementado de 1 em 1 unidade a cada interação do `for()`, já que definimos no último bloco que `batiNaMesa++` é que ocorrerá a cada interação do `for()`.

* Por fim, falamos que o bloco deverá ser repetido enquanto `batiNaMesa` for menor ou igual a 6, ou seja:
  * A mensagem **“Eu bati na mesa”** será escrita enquanto batiNaMesa estiver entre 1 e 6, ou seja:
    * 6 vezes exatas.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-est-for-teo-c-est-rep-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-est-for-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-est-for-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-est-for-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-est-for-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-est-for-teo-c-est-rep-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
