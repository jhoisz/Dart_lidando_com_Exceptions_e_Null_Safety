<h1 align="center"> Dart: Lidando com exceções e null safety ✅ </h1>

## Diferença entre Erro e Exceção

Exceções, diferente de erros, são situações que você pode planejar e resolver depois.

> Exemplos de **exceções**:

- `FormatException`;
- `TimeOutException`;
- `IOException`;
- Exceções personalizadas.

> Exemplos de **erros**:

- `StackOverFlowError`;
- `OutOfMemoryError`;
- `ArgumentError`;
- `TypeError`.

## Captura de exceções/erros

> Estrutura `Try/On`:

```dart
try{
    //código que pode dar erro
}on{
    //o que fazer quando há um erro
}
```

> Estrutura `Try/On Catch`:

```dart
try{
    // Código que pode gerar erro
} on Exception catch(e){
    // print(e.message);
    // print(e.source);
    print(e.toString);
}
```

> Estrutura `Try/Catch/Finally`:

```dart
try{
    // Código que pode gerar erro
} catch  (exception, stackTrace){
    print(exception);
    print(stackTrace);
} finally {
    print("Chegou no finally");
}
```

> Usando `rethrow`

:construction: Projeto em construção :construction:
