
# Exemplos de InstanciaÃ§Ã£o de Tipos em C#

## ðŸ”¹ Tipos Primitivos

```csharp
int numero = 10;
double decimalComPonto = 3.14;
float decimalCurto = 2.5f;
bool verdadeiroOuFalso = true;
char letra = 'A';
string texto = "OlÃ¡, mundo!";
```

---

## ðŸ”¹ Arrays

```csharp
int[] numeros = new int[] { 1, 2, 3 };
string[] nomes = { "Ana", "JoÃ£o", "Carlos" };
```

---

## ðŸ”¹ Listas (List<T>)

```csharp
using System.Collections.Generic;

List<int> listaNumeros = new List<int> { 1, 2, 3 };
List<string> listaNomes = new List<string>();
listaNomes.Add("Maria");
```

---

## ðŸ”¹ DicionÃ¡rios (Dictionary<TKey, TValue>)

```csharp
using System.Collections.Generic;

Dictionary<string, int> idadePorNome = new Dictionary<string, int>();
idadePorNome["Ana"] = 25;
```

---

## ðŸ”¹ Objetos (Classes personalizadas)

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

## ðŸ”¹ Structs

```csharp
struct Ponto {
    public int X, Y;
}

Ponto ponto = new Ponto { X = 10, Y = 20 };
```

---

## ðŸ”¹ Enums

```csharp
enum Cor { Vermelho, Verde, Azul }

Cor corFavorita = Cor.Verde;
```

---

## ðŸ”¹ Tuplas

```csharp
var tupla = (Nome: "Carlos", Idade: 28);
Console.WriteLine(tupla.Nome);  // Carlos
```

---

## ðŸ”¹ Nullable Types

```csharp
int? idade = null;
bool? ativo = true;
```
