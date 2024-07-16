# String
Em Go, uma string é uma sequência de caracteres usada para representar texto. Você pode criar uma string colocando o texto entre aspas duplas ("). Por exemplo:

```go
Copy code
var nome string = "João"
saudacao := "Olá, mundo!"
```

---

# Boolean
Um boolean em Go é um tipo de dado que pode ter apenas dois valores: true ou false. Este tipo é frequentemente usado em testes condicionais. Por exemplo:

```go
Copy code
var isAdult bool = true
hasPermission := false
```

---

# Null
Em Go, não existe o conceito de null como em outras linguagens. Em vez disso, Go usa nil para representar um valor nulo ou indefinido para certos tipos de dados como ponteiros, slices, maps, canais, interfaces e funções. Por exemplo:

```go
Copy code
var ptr *int = nil
```

---

# Undefined
Em Go, todas as variáveis devem ser inicializadas antes do uso. Não existe o conceito de undefined como em JavaScript. Variáveis declaradas sem um valor inicial são automaticamente inicializadas com o valor zero do seu tipo (por exemplo, 0 para inteiros, false para booleanos, "" para strings, e nil para tipos de referência como ponteiros, slices, etc.). Por exemplo:

```go
Copy code
var idade int // idade é inicializada com 0
```

# Object
Go não possui um tipo object genérico como em outras linguagens. Em vez disso, Go usa structs para agrupar variáveis de diferentes tipos sob um único nome. Uma struct é uma coleção de campos. Por exemplo:

```go
Copy code
type Pessoa struct {
    Nome      string
    Idade     int
    Profissao string
}
var maria = Pessoa{"Maria", 30, "Engenheira"}
```

--

# Array
Um array em Go é uma coleção de elementos de mesmo tipo com tamanho fixo. Arrays são úteis para armazenar listas de dados de tamanho conhecido. Por exemplo:

```go
Copy code
var numeros [5]int = [5]int{1, 2, 3, 4, 5}
frutas := [3]string{"maçã", "banana", "laranja"}
```

---

# Function
Uma function (função) em Go é um bloco de código que pode ser chamado e executado em qualquer momento. Funções permitem reutilização de código e podem aceitar argumentos e retornar valores. Por exemplo:

```go
Copy code
func saudacao(nome string) string {
    return "Olá, " + nome + "!"
}
fmt.Println(saudacao("Pedro")) // Olá, Pedro!
```

---

Esses são alguns dos conceitos básicos em Go. Entender esses elementos é fundamental para se tornar proficiente na linguagem.
