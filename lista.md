Questões objetivas
1) O que o código a seguir faz?

Uma imagem

Escolha a opção que responde corretamente:

a) **Imprime os números pares de 1 a 10**

b) Imprime os números ímpares de 1 a 10.

c) Imprime os números pares de 2 a 10.

d) Imprime os números ímpares de 2 a 10.

2) Identificar a linha que falta no código para criar uma classe Veiculo com atributo marca, e uma classe Carro que herda de Veiculo com um método ligar().

Uma imagem

No lugar onde está escrito “// linha” qual das opções abaixo deve estar para funcionar corretamente o código?

**A) let carro = new Carro("Toyota");**

B) let ligar = new ligar("Toyota");

C) class Moto extends Veiculo {};

D) carro1.ligar();

3) Qual é o valor de resultado após a execução deste código?

Uma imagem

Escolha a opção que responde corretamente:

**A) 18**

B) 16

C) 14

D) 12

4) Como você criaria um método acelerar() em uma classe Carro, que recebe um parâmetro velocidade e o adiciona a um atributo velocidadeAtual?

**A) Uma imagem**

B) Uma imagem

C) Uma imagem

D) Uma imagem

5) Qual a forma correta de definir uma classe Carro em JavaScript, com um método ligar() e um atributo marca?

**A) Uma imagem**

B) Uma imagem

C) Uma imagem

D) Uma imagem

6) Observe o código abaixo:

Uma imagem

Qual será a saída do código acima?

**A) "Olá, meu nome é João. Olá, meu nome é Maria."**

B) "Olá, meu nome é ."

C) "João Maria"

D) "undefined undefined"

Questões dissertativas
7) Vamos criar um programa em JavaScript para entender classes, métodos e atributos! Classe Animal:

Crie uma classe chamada Animal.
Adicione dois atributos: nome e idade.
Adicione um método chamado descrever() na classe Animal.
Este método deve exibir no console uma descrição do animal com seu nome e idade.
Criando e manipulando Animais:

Crie dois objetos da classe Animal: um chamado "cachorro" e outro "gato", com idades distintas.
Para cada animal, chame o método descrever() para ver a descrição no console.
Dica: Utilize console.log() para exibir as informações!

// Definindo a classe Animal
class Animal {
  // Construtor da classe com os atributos nome e idade
  constructor(nome, idade) {
    this.nome = nome;
    this.idade = idade;
  }

  // Método para descrever o animal
  descrever() {
    console.log(`Nome: ${this.nome}, Idade: ${this.idade} anos`);
  }
}

// Criando objetos da classe Animal
const cachorro = new Animal("Cachorro", 3);
const gato = new Animal("Gato", 2);

// Chamando o método descrever() para cada animal
cachorro.descrever();
gato.descrever();


8) Nos últimos dias tivemos a oportunidade de ter contato com Programação Orientada a Objetos, e tivemos contato com o tema "herança". Herança é um princípio de orientação a objetos, que permite que classes compartilhem atributos e métodos. Ela é usada na intenção de reaproveitar código ou comportamento generalizado ou especializar operações ou atributos. Então vamos praticar esse conteúdo nessa questão. Vamos criar um programa em JavaScript para entender classes, métodos, atributos e herança!

Classe Animal:

Crie uma classe chamada Animal.
Adicione dois atributos: nome e idade.
Adicione um método descrever() que exiba no console uma descrição do animal com seu nome e idade.
Classe Gato (Herda de Animal):

Crie uma classe chamada Gato que herda da classe Animal.
Adicione um atributo extra cor específico para gatos.
Adicione um método miar() que exiba no console o som que um gato faz.
Criando Animais:

Crie dois objetos da classe Animal: um chamado cachorro e outro gato, com idades distintas.
Para o gato, também defina a cor.
Chamando os Métodos:

Para cada animal, chame o método descrever() para ver a descrição no console.
Para o gato, chame o método miar() para "ouvir" o som que ele faz (é também para ver o som no console).
Dica: Utilize console.log() para exibir as informações!

// Definindo a classe Animal
class Animal {
  // Construtor da classe com os atributos nome e idade
  constructor(nome, idade) {
    this.nome = nome;
    this.idade = idade;
  }

  // Método para descrever o animal
  descrever() {
    console.log(`Nome: ${this.nome}, Idade: ${this.idade} anos`);
  }
}

// Definindo a classe Gato que herda de Animal
class Gato extends Animal {
  // Construtor da classe Gato, que chama o construtor da classe Animal
  constructor(nome, idade, cor) {
    super(nome, idade);
    this.cor = cor;
  }

  // Método específico para gatos: miar()
  miar() {
    console.log("Miau!");
  }
}

// Criando objetos da classe Animal
const cachorro = new Animal("Cachorro", 3);
const gato = new Gato("Gato", 2, "Preto");

// Chamando o método descrever() para cada animal
cachorro.descrever();
gato.descrever();

// Chamando o método miar() apenas para o objeto gato
gato.miar();

9) Vamos criar um programa em JavaScript para somar notas!

Classe SomadorDeNotas:

Crie uma classe chamada SomadorDeNotas.
Adicione um atributo total inicializado com 0 para armazenar a soma das notas.
Método adicionarNota:

Adicione um método chamado adicionarNota(nota) na classe SomadorDeNotas.
Este método deve receber um parâmetro nota e somá-lo ao atributo total.
Criando o Somador e Adicionando Notas:

Crie um objeto da classe SomadorDeNotas, chamado somador.
Utilize o método adicionarNota(nota) para adicionar algumas notas ao somador.
Chamando o Método para Ver o Total:

Após adicionar todas as notas, chame um método verTotal() para exibir o total das notas adicionadas.
Dica: Utilize console.log() para exibir as informações!


10) Imagine que você está criando um programa em JavaScript para uma escola. Neste programa, existem diferentes tipos de funcionários, cada um com suas próprias características. Considere as seguintes classes:

Funcionário:

atributo: Nome
atributo: Idade
atributo: Salário base
método: calcularSalario() - Este método calcula o salário total do funcionário. Para cada tipo de funcionário, o cálculo será diferente.
Professor (herança de Funcionário):

atributo: Disciplina
atributo: Horas de aula por semana
método: calcularSalario() - Para calcular o salário do professor, multiplicamos suas horas de aula pelo valor da hora/aula.
Agora, sua tarefa é escrever um código em JavaScript que crie as classes Funcionário e Professor, com suas características e métodos descritos acima. Depois de criar as classes, crie:

Dois objetos do tipo Professor com informações fictícias.
Para cada objeto, chame o método calcularSalario() e mostre o salário calculado no console.
Certifique-se de explicar cada parte do código utilizando comentários, explicando para que serve cada atributo e método, bem como a lógica por trás do cálculo de salário para o tipo de funcionário Professor.

// Definindo a classe Funcionário
class Funcionario {
  // Construtor da classe com os atributos nome, idade e salário base
  constructor(nome, idade, salarioBase) {
    this.nome = nome;
    this.idade = idade;
    this.salarioBase = salarioBase;
  }

  // Método para calcular o salário total (será sobrescrito nas subclasses)
  calcularSalario() {
    return this.salarioBase; // Salário base para funcionários genéricos
  }
}

// Definindo a classe Professor que herda de Funcionário
class Professor extends Funcionario {
  // Construtor da classe Professor, que chama o construtor de Funcionário e adiciona os atributos específicos
  constructor(nome, idade, salarioBase, disciplina, horasAulaSemana) {
    super(nome, idade, salarioBase);
    this.disciplina = disciplina;
    this.horasAulaSemana = horasAulaSemana;
  }

  // Sobrescrevendo o método calcularSalario para professores
  calcularSalario() {
    // Cálculo do salário do professor: multiplicando horas de aula pelo valor da hora/aula
    const valorHoraAula = 20; // Valor fictício da hora/aula
    return this.salarioBase + (this.horasAulaSemana * valorHoraAula);
  }
}

// Criando dois objetos do tipo Professor com informações fictícias
const professor1 = new Professor("Professor 1", 35, 3000, "Matemática", 20);
const professor2 = new Professor("Professor 2", 40, 3500, "História", 15);

// Chamando o método calcularSalario() para cada objeto e mostrando o salário calculado no console
console.log(`${professor1.nome}: Salário total = ${professor1.calcularSalario()} reais`);
console.log(`${professor2.nome}: Salário total = ${professor2.calcularSalario()} reais`);
