# POO
______________________________________________________________________________________________________________

## Paradigmas de Programação:
  - Paradigma representa um padrão de pensamento que orienta um conjunto de atividades relacionadas.

## Sebesta (2018) divide as linguagens de programação em quatro categorias:
  
01 - Imperativas

02 - Lógicas

03 - Funcionais

04 - Orientadas a objetos

Elas se enquadram como paradigmas de programação, e podem ser classificadas em **imperativo** e **declarativo**.

Segundo Silva, Leite e Oliveira (2019) apud Simão (2018), o paradigma de programação imperativo contempla o paradigma procedural e o paradigma orientado a objetos.  Por outro lado, o paradigma de programação declarativo subdivide-se em paradigma funcional e paradigma lógico.


<img width="701" height="378" alt="01" src="https://github.com/user-attachments/assets/d5176a1e-5994-4b3c-a0ad-3c30a6ff7f89" />


## 2. Paradigma de Programação Orientado a Objetos: 

## Tangível:

No mundo real, um **carro** tem **atributos** como **cor**, **marca** e **modelo**, e comportamentos como **acelerar** e **frear**. Na POO, isso é representado por uma **classe Carro** com ***atributos** e **métodos** correspondentes.

Cabe lembrar que objetos tangíveis são aqueles que podem ser percebidos fisicamente, ou seja, todo aquele que possui uma presença física que pode ser tocada e vista.

## Intangível: 

No mundo real, mas pode ser modelada com **atributos** como **saldoe** **número da conta**, e **métodos** como **depositar** e **sacar**.

Os objetos tangíveis têm dimensões e peso e ocupam um lugar no espaço no mundo real, por exemplo, canetas, carros, livros e eletrodomésticos.

Na POO cada objeto é representado por uma classe. Pela forma como observamos os objetos do mundo real, temos plena condições de separá-los por suas características, isto é, identificar a qual classe o objeto pertence, a isso chamamos 
de operação de classificação.

Na POO cada objeto é representado por uma classe. Pela forma como observamos os objetos do mundo real, temos plena condições de separá-los por suas características, isto é, identificar a qual classe o objeto pertence, a isso chamamos 
de operação de classificação. Por exemplo, em uma sala de aula com 30 alunos, assumimos que esses são 30 objetos alunos da classe Aluno. Um curso tem vários professores, logo, temos objetos professores que são representados por uma classe Professor. Embora os termos objeto e classe já estejam evidentes nessa
introdução. 


"1. Qualquer coisa é um objeto.

2. Objetos realizam tarefas por meio da requisição de serviços a outros objetos.

3. Cada objeto pertence a uma determinada classe. Uma classe agrupa objetos similares.

4. A classe é um repositório para comportamento associado ao objeto.

5. Classes são organizadas em hierarquias. (Bezerra, 2015, n. p.)"

## 3. Pilares da Orientação a Objetos:

### Encapsulamento: 

Encapsulamento é o princípio de agrupar dados e métodos que operam sobre esses dados em uma única unidade, a classe. Ele também controla o acesso aos dados, protegendo-os de modificações não autorizadas. Os benefícios oferecidos pelo encapsulamento estão relacionados à segurança e modularidade.

**Segurança:** 

Oferece proteção aos dados contra acessos e modificações indevidas.

**Modularidade** 

Permite a separação de preocupações, facilitando a manutenção e a compreensão do código.

Por meio do encapsulamento, é possível esconder a complexidade e garantir a proteção dos dados, evitando que sejam modificados sem passar devidamente por regras de negócios do projeto.

### Herança:

A Herança é o mecanismo pelo qual é possível o reuso de códigos, de forma que uma classe (subclasse) pode herdar atributos e métodos de outra (superclasse). Isso permite a criação de uma hierarquia de classes promovendo a reutilização de 
código.

Assim, os benefícios da herança giram em torno da reusabilidade e extensibilidade.

**Reusabilidade** 

Facilita o reuso de código já existente.

**Extensibilidade** 

Permite a criação de novas funcionalidades com base em classes existentes.

**Facilidade de Manutenção**

Alterações na superclasse se refletem automaticamente nas subclasses.

**Hierarquia Lógica** 

Facilita a compreensão do relacionamento entre classes e promove um design mais organizado.

### Polimorfismo:

Polimorfismo é um princípio da POO que permite que uma única interface seja usada para representar diferentes tipos de objetos. Isso significa que o mesmo método pode ter diferentes implementações dependendo do objeto que o invoca. Por exemplo, se os veículos se movem e param, é possível descrever uma interface Movimento declarando os dois métodos: mover e parar. 
A partir dessa declaração, toda subclasse veículo deve declarar a interface Movimento e implementar os métodos mover e parar de forma apropriada de acordo com o tipo de veículo. Por exemplo, um caminhão aciona o sistema de freio a ar para travar as rodas, por outro lado, um carro aciona o sistema de freios a disco para bloquear as suas rodas. 
Assim, nota-se que tanto o caminhão quanto o carro (que são subclasses de veículos) têm sistemas de frenagem para travar as rodas, no entanto, os comportamentos e as formas de acionamento são diferentes. A certeza que temos é que ao acionar os freios ambos os veículos devem diminuir a velocidade até parar. 
Com a aplicação do polimorfismo, teremos a garantia de que, se um método for declarado, uma implementação adequada haverá de existir.

<img width="745" height="385" alt="02" src="https://github.com/user-attachments/assets/de597041-d238-49cf-8ccc-9434aea5204e" />

### Abstração:

A abstração é um dos pilares fundamentais da Programação Orientada a Objetos (POO), que se refere ao processo de simplificação da complexidade de um sistema
ao focar apenas nos aspectos essenciais de um objeto, enquanto oculta os detalhes de implementação. Em POO, a abstração é alcançada por meio de classes
abstratas e interfaces que definem um conjunto de métodos que devem ser implementados pelas classes concretas. Isso permite que os desenvolvedores
trabalhem com conceitos de alto nível sem se preocupar com os detalhes internos dos objetos. Aplica-se o conceito de abstração em situações em que conceitos
muito genéricos requerem especialização para tratar das especificidades de objetos.

Para evitar incertezas em relação ao tipo de Conta do cliente, o importante é assumir que existe um tipo abstrato Conta e duas subclasses concretas
ContaPoupanca e ContaCorrente. Neste caso, sabe-se que ambas são contas, mas para qualquer tipo de movimentação (por exemplo, um saque ou depósito) é 
necessário ter a certeza em qual conta está ocorrendo um determinado tipo de movimentação. Aplicando-se o conceito de abstração na POO, apenas as classes
Concretas podem se tornar objetos, por outro lado, classes Abstratas não têm essa possibilidade. Desta forma, jamais será possível instanciar um objeto genérico
(Conta), fazendo com que as movimentações ocorram apenas em objetos concretos do tipo ContaPoupanca ou ContaCorrente.

<img width="898" height="575" alt="03" src="https://github.com/user-attachments/assets/e265498e-3591-4a54-90c3-7acb4cf8fe2c" />


# 💻 Abstração em POO - Exemplo Conta Bancária

Este repositório apresenta um exemplo simples de **Programação Orientada a Objetos (POO)** utilizando o conceito de **abstração** aplicado ao domínio de contas bancárias.

---

## 📌 Conceito

Na POO, a **abstração** é utilizada para representar ideias ou modelos genéricos que **não podem ser instanciados diretamente**, mas servem como base para classes mais específicas.

No exemplo, temos:

- **Conta (classe abstrata)**  
  Representa o conceito genérico de uma conta bancária. Define atributos e métodos comuns a todas as contas, como:
  - número da conta  
  - nome do titular  
  - saldo  
  - operações como `sacar()` e `depositar()`  

- **ContaCorrente (classe concreta)**  
  Subclasse que herda de `Conta` e implementa regras específicas, como uso de **cheque especial** no saque.

- **ContaPoupanca (classe concreta)**  
  Subclasse que herda de `Conta` e implementa regras de movimentação típicas da poupança, além de possibilitar o cálculo de **rendimentos**.

---

## 🚫 Por que a classe Conta não pode ser instanciada?

A classe `Conta` é **abstrata** porque ela representa apenas um **modelo genérico**.  
Não faria sentido criar diretamente uma conta do tipo `Conta`, pois seria impossível saber se ela é **corrente** ou **poupança**, o que poderia gerar **incertezas** nas movimentações.

Exemplo inválido:
```java
Conta c = new Conta(); // ❌ Não permitido
```

Exemplo correto:
```java
Conta c1 = new ContaCorrente();
Conta c2 = new ContaPoupanca();
```

---

## 🛠️ Vantagens da Abstração

- ✅ Evita ambiguidades: toda movimentação ocorre em um tipo de conta específico.  
- ✅ Código organizado: atributos e métodos comuns ficam na classe `Conta`.  
- ✅ Facilidade de manutenção: novas contas podem ser criadas herdando de `Conta`.  
- ✅ Polimorfismo: permite tratar `ContaCorrente` e `ContaPoupanca` de forma uniforme quando necessário.  

---

## 📂 Estrutura do Projeto

```
src/
 ├── Conta.java          // Classe abstrata
 ├── ContaCorrente.java  // Subclasse concreta
 └── ContaPoupanca.java  // Subclasse concreta
```

---

## 📖 Exemplo de Uso

```java
public class Main {
    public static void main(String[] args) {
        Conta c1 = new ContaCorrente("João", 1000, 500);
        Conta c2 = new ContaPoupanca("Maria", 2000);

        c1.sacar(1200); // Usa cheque especial
        c2.depositar(300); // Depósito na poupança

        System.out.println(c1);
        System.out.println(c2);
    }
}
```

---

## 📌 Conclusão

Este exemplo mostra como aplicar **abstração** em POO para garantir que um sistema bancário sempre saiba em qual **tipo de conta concreta** uma movimentação está ocorrendo, evitando inconsistências e organizando melhor o código.



