# Projeto: Cálculo de Notas Trimestrais do Aluno

## 📝 Descrição

Este é um programa de console desenvolvido em C# que calcula a nota final de um aluno a partir de suas três notas trimestrais. O sistema avalia se o aluno atingiu a nota mínima para aprovação e, caso contrário, informa a pontuação que faltou para alcançar o resultado desejado.

## ✨ Funcionalidades

* Lê o nome do aluno via console.
* Lê as três notas trimestrais do aluno.
* Calcula a nota final somando as três notas inseridas.
* Verifica o status do aluno:
    * **APROVADO**: Se a nota final for igual ou superior a 60.0 pontos.
    * **REPROVADO**: Se a nota final for inferior a 60.0 pontos.
* Caso reprovado, exibe a quantidade de pontos que faltaram para atingir a média 60.0.

## 🚀 Tecnologias Utilizadas

* **C#**: Linguagem de programação principal.
* **.NET 8.0**: Framework de desenvolvimento.

## 📂 Estrutura do Projeto

O projeto está organizado com os seguintes arquivos principais:

```
/Course
|-- Aluno.cs            # Contém a classe Aluno com os atributos e métodos de negócio.
|-- Program.cs          # Contém a lógica de execução e interação com o usuário.
|-- ExercicioNota.csproj # Arquivo de configuração do projeto.
|-- Course.sln          # Arquivo de solução do Visual Studio.
```

* `Aluno.cs`: Define a classe `Aluno` e seus membros:
    * **Atributos**: `Nome`, `Nota1`, `Nota2`, `Nota3`.
    * **Métodos**:
        * `NotaFinal()`: Retorna a soma das notas trimestrais.
        * `Aprovado()`: Retorna um valor booleano indicando se a nota final é suficiente para aprovação.
        * `NotaRestante()`: Calcula a diferença para a nota mínima caso o aluno seja reprovado.
* `Program.cs`: Responsável por orquestrar a execução do programa, recebendo os dados e exibindo os resultados no console.

## 🏃 Como Executar o Projeto

1. Faça o download ou clone o repositório para a sua máquina local.
2. Abra um terminal ou console de comando na pasta raiz do projeto.
3. Execute o comando abaixo para compilar e rodar a aplicação:
   ```bash
   dotnet run --project Course/ExercicioNota.csproj
   ```
4. Siga as instruções exibidas no console para inserir os dados solicitados.
