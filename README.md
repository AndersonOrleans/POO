# 💻 Programação Orientada a Objetos (POO)

---

## 📚 Paradigmas de Programação

Um **paradigma de programação** representa um padrão de pensamento que orienta um conjunto de atividades relacionadas, definindo como os problemas são compreendidos e resolvidos por meio de linguagens de programação.

---

## 📖 Classificação segundo Sebesta (2018)

Sebesta (2018) divide as linguagens de programação em quatro categorias principais:

1. **Imperativas**  
2. **Lógicas**  
3. **Funcionais**  
4. **Orientadas a Objetos**

Essas categorias se enquadram como **paradigmas de programação** e podem ser classificadas em dois grandes grupos:

- **Imperativo**
- **Declarativo**

---

## 🔎 Imperativo x Declarativo

📌 **Paradigma Imperativo**  
De acordo com Silva, Leite e Oliveira (2019) apud Simão (2018), o paradigma de programação imperativo contempla:
- O **paradigma procedural**  
- O **paradigma orientado a objetos (POO)**  

📌 **Paradigma Declarativo**  
O paradigma de programação declarativo subdivide-se em:
- O **paradigma funcional**  
- O **paradigma lógico**

---

## ✅ Conclusão

- Os **paradigmas de programação** são formas de organizar o pensamento e a resolução de problemas em computação.  
- O **imperativo** foca em *como* o programa deve ser executado (passo a passo).  
- O **declarativo** foca em *o que* deve ser resolvido, abstraindo os detalhes da execução.  
- A **POO (Programação Orientada a Objetos)** é uma evolução dentro do paradigma imperativo, trazendo conceitos como **abstração, herança, polimorfismo e encapsulamento**.


<img width="701" height="378" alt="01" src="https://github.com/user-attachments/assets/d5176a1e-5994-4b3c-a0ad-3c30a6ff7f89" />


## 🔹 2. Paradigma de Programação Orientado a Objetos

---

## ✨ Objetos Tangíveis

No mundo real, um **carro** possui **atributos** como **cor**, **marca** e **modelo**, além de **comportamentos** como **acelerar** e **frear**.  
Na POO, isso é representado por uma **classe Carro**, com **atributos** e **métodos** correspondentes.

📌 **Definição:** Objetos tangíveis são aqueles que podem ser percebidos fisicamente, ou seja, possuem presença física, podem ser tocados e vistos.  
Exemplos: canetas, carros, livros, eletrodomésticos.

---

## 💡 Objetos Intangíveis

Além dos tangíveis, também existem os **objetos intangíveis**, que não podem ser tocados, mas podem ser modelados.  
Um exemplo é uma **conta bancária**, que possui:

- **Atributos**: saldo, número da conta  
- **Métodos**: depositar(), sacar()  

Esses objetos não têm presença física, mas são essenciais no mundo da modelagem computacional.

---

## 🏷️ Classes e Objetos

Na POO, cada objeto é representado por uma **classe**.  
A partir da observação do mundo real, podemos **classificar** os objetos por suas características, identificando a qual classe eles pertencem.  

👉 Esse processo é chamado de **operação de classificação**.

📌 Exemplos:  
- Em uma sala de aula com 30 alunos → temos **30 objetos Aluno** da classe `Aluno`.  
- Em um curso com vários professores → temos **objetos Professor** que pertencem à classe `Professor`.  

---

## 📖 Fundamentos segundo Bezerra (2015)

1. Qualquer coisa é um **objeto**.  
2. Objetos realizam tarefas por meio da **requisição de serviços** a outros objetos.  
3. Cada objeto pertence a uma determinada **classe**. Uma classe agrupa objetos similares.  
4. A **classe** é um repositório para comportamento associado ao objeto.  
5. **Classes** são organizadas em **hierarquias**.  

---

## ✅ Conclusão

O paradigma de Programação Orientada a Objetos (POO) nos permite modelar tanto **objetos tangíveis** quanto **intangíveis** do mundo real.  
Através de **atributos** e **métodos**, representamos características e comportamentos, enquanto as **classes** organizam e agrupam os objetos, tornando possível criar sistemas mais próximos da realidade.


# 🔹 3. Pilares da Orientação a Objetos

A Programação Orientada a Objetos (POO) é sustentada por três pilares principais: **Encapsulamento**, **Herança** e **Polimorfismo**.  
Cada um deles contribui para organização, reuso de código e flexibilidade no desenvolvimento de sistemas.

---

## 🔒 Encapsulamento

O **encapsulamento** é o princípio de agrupar **dados** e **métodos** que operam sobre esses dados dentro de uma mesma unidade: a **classe**.  
Ele também controla o acesso, garantindo que informações sensíveis não sejam alteradas de forma indevida.

### ✅ Benefícios do Encapsulamento

- **Segurança:** proteção contra acessos e modificações indevidas.  
- **Modularidade:** separação de responsabilidades, facilitando manutenção e entendimento do código.  

📌 Em resumo, o encapsulamento **esconde a complexidade** e garante que os dados só sejam modificados seguindo as regras de negócio.

---

## 🏛️ Herança

A **herança** é o mecanismo que permite a reutilização de código.  
Uma **subclasse** pode herdar atributos e métodos de uma **superclasse**, formando uma **hierarquia de classes**.

### ✅ Benefícios da Herança

- **Reusabilidade:** aproveitamento de código já existente.  
- **Extensibilidade:** criação de novas funcionalidades a partir de classes base.  
- **Facilidade de Manutenção:** alterações na superclasse se refletem automaticamente nas subclasses.  
- **Hierarquia Lógica:** promove design mais organizado e entendimento das relações entre classes.  

📌 Assim, a herança possibilita um **reuso eficiente** e **expansão natural** dos sistemas.

---

## 🔄 Polimorfismo

O **polimorfismo** permite que uma mesma **interface** seja utilizada para representar diferentes tipos de objetos.  
Isso significa que o mesmo método pode ter implementações distintas dependendo do objeto que o invoca.

### 🛠️ Exemplo

- Criamos uma interface **Movimento** com os métodos `mover()` e `parar()`.  
- Cada veículo (carro, caminhão, moto) deve implementar essa interface.  
- O comportamento é diferente:  
  - 🚚 O caminhão aciona freio a ar.  
  - 🚗 O carro aciona freio a disco.  

Apesar das diferenças, sabemos que **todos diminuem a velocidade até parar**.

### ✅ Benefícios do Polimorfismo

- Flexibilidade no código.  
- Garantia de que diferentes objetos terão um **comportamento adequado** ao executar o mesmo método.  
- Simplificação no uso, pois podemos tratar objetos diferentes de forma uniforme.  

---

## 📌 Conclusão

Os três pilares da POO trabalham juntos para:

- **Encapsular** dados e proteger informações.  
- **Reutilizar e organizar** o código por meio da herança.  
- **Garantir flexibilidade e consistência** através do polimorfismo.  

Eles tornam a programação mais próxima do mundo real, favorecendo a construção de sistemas robustos, modulares e fáceis de manter.


<img width="745" height="385" alt="02" src="https://github.com/user-attachments/assets/de597041-d238-49cf-8ccc-9434aea5204e" />

# 🎭 Abstração

A **abstração** é um dos pilares fundamentais da Programação Orientada a Objetos (POO).  
Ela se refere ao processo de **simplificação da complexidade de um sistema**, focando apenas nos **aspectos essenciais** de um objeto e ocultando os **detalhes de implementação**.

---

## 📌 Como funciona

Na POO, a abstração é alcançada por meio de:

- **Classes Abstratas** → servem como modelos, não podem ser instanciadas diretamente.  
- **Interfaces** → definem contratos (métodos) que devem ser implementados pelas classes concretas.  

Isso permite que os desenvolvedores trabalhem com conceitos de **alto nível**, sem precisar conhecer os detalhes internos de cada objeto.

---

## 💡 Quando aplicar a Abstração

A abstração é usada quando lidamos com **conceitos genéricos** que precisam ser **especializados** em tipos mais específicos.  
Assim, garantimos que apenas objetos concretos sejam manipulados, evitando incertezas no sistema.

---

## 🏦 Exemplo: Sistema Bancário

Imagine um sistema que trabalha com contas bancárias.  

- Existe o **tipo abstrato** `Conta`.  
- Existem duas subclasses concretas:  
  - `ContaCorrente`  
  - `ContaPoupanca`  

Ambas são contas, mas cada uma possui **características próprias**.  

📌 Para qualquer movimentação (como um **saque** ou **depósito**), é necessário ter certeza de **qual conta** está sendo utilizada.  

- A classe `Conta` é **abstrata** e não pode ser instanciada.  
- As movimentações só podem ocorrer em objetos concretos:  
  - `ContaCorrente`  
  - `ContaPoupanca`  

Exemplo inválido:
Conta c = new Conta(); // ❌ Não permitido

Exemplo correto:
Conta c1 = new ContaCorrente();
Conta c2 = new ContaPoupanca();

---

## ✅ Benefícios da Abstração

- **Redução da complexidade** → foca apenas no que é essencial.  
- **Organização do código** → separa responsabilidades de maneira clara.  
- **Evita incertezas** → garante que operações ocorram apenas em objetos concretos.  
- **Flexibilidade** → facilita a especialização e expansão do sistema.  

---

## 📌 Conclusão

A abstração permite que trabalhemos com **modelos conceituais** em alto nível, enquanto os detalhes específicos ficam para as classes concretas.  
No exemplo bancário, isso garante que movimentações financeiras sempre sejam feitas em **contas reais** (corrente ou poupança), e nunca em uma conta genérica.


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



