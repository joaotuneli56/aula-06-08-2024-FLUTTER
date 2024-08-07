# MATERIAL FLUTTER
**AULA 06.08.2024**

[Slide da aula](https://www.canva.com/design/DAFrFIrk-Lc/n_v7URQguV59lPi1T-Vbhg/edit)

## Programação Assincrona

As operações assincronas permitem que seu programa conclua o trabalho enquanto guarda a conclusão de outra operação.

Operações assincronas mais comuns:

- Busca dados de uma rede

- Escrevendo dados de um banco de dados

- Lendo dados de um arquivo

## Future`<T>`

T --> são os diversos tipos de features que podemos criar

## Estados de uma future

- **Não concluido** Quando você chama uma função assíncrona, ela retorna um Future incompleto. Esse Future está esperando a operação assíncrona da função terminar

```dart
Future<String>
Future<void>
```

- **Concluido** Se a operação assíncrona for bem-sucedida, o futuro será concluído com um valor. Caso contrário, ele será concluído com um erro.

Conlcui com erro

ou

Concluido com valor
```dart
Future<String>
Future<void>
```
