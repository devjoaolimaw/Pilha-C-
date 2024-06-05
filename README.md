# Pilha-C-

Este código em C# demonstra o uso básico da classe `Stack<T>`, que é uma implementação de pilha genérica na biblioteca padrão do .NET.

1. **Criação da pilha**: 
```csharp
Stack<int> pilha = new Stack<int>();
```
Uma pilha de inteiros é criada.

2. **Inserção de elementos na pilha**:
```csharp
pilha.Push(4);
pilha.Push(6);
pilha.Push(8);
pilha.Push(10);
```
Quatro elementos (4, 6, 8, 10) são inseridos na pilha usando o método `Push`.

3. **Iteração sobre os elementos da pilha**:
```csharp
foreach(int item in pilha)
{
    Console.WriteLine(item);
}
```
Os elementos da pilha são impressos usando um loop `foreach`.

4. **Remoção do elemento do topo da pilha**:
```csharp
Console.WriteLine($"Removendo o elemento do topo: {pilha.Pop()}");
```
O elemento do topo da pilha é removido e impresso usando o método `Pop`.

5. **Inserção de um novo elemento na pilha**:
```csharp
pilha.Push(20);
```
O número 20 é inserido na pilha.

6. **Iteração novamente sobre os elementos da pilha**:
```csharp
foreach(int item in pilha)
{
    Console.WriteLine(item);
}
```
Os elementos atualizados da pilha são impressos novamente.
