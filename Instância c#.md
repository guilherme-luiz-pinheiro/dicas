
# Exemplos de Instâncias de Tipos em C#

## Tipos Primitivos

```csharp
int numero = 10;
double decimalComPonto = 3.14;
float decimalCurto = 2.5f;
bool verdadeiroOuFalso = true;
char letra = 'A';
string texto = "OlÃ¡, mundo!";
```

---

## Arrays

```csharp
int[] numeros = new int[] { 1, 2, 3 };
string[] nomes = { "Ana", "JoÃ£o", "Carlos" };
```

---

## Listas (List<T>)

```csharp
using System.Collections.Generic;

List<int> listaNumeros = new List<int> { 1, 2, 3 };
List<string> listaNomes = new List<string>();
listaNomes.Add("Maria");
```

---

## Dicionários (Dictionary<TKey, TValue>)

```csharp
using System.Collections.Generic;

Dictionary<string, int> idadePorNome = new Dictionary<string, int>();
idadePorNome["Ana"] = 25;
```

---

## Objetos (Classes personalizadas)

```csharp
class Pessoa {
    public string Nome;
    public int Idade;
}

// Instanciando
Pessoa p = new Pessoa();
p.Nome = "Lucas";
p.Idade = 30;
```

---

## Structs

```csharp
struct Ponto {
    public int X, Y;
}

Ponto ponto = new Ponto { X = 10, Y = 20 };
```

---

## Enums

```csharp
enum Cor { Vermelho, Verde, Azul }

Cor corFavorita = Cor.Verde;
```

---

## Tuplas

```csharp
var tupla = (Nome: "Carlos", Idade: 28);
Console.WriteLine(tupla.Nome);  // Carlos
```

---

## Nullable Types

```csharp
int? idade = null;
bool? ativo = true;
```
