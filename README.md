# Projeto-DIO-Sistema-Banc-rio-em-POO-com-Python
Projeto com fins educativos com python

## 📌 Objetivo

Criar um sistema bancário simples utilizando conceitos de orientação a objetos, simulando operações bancárias como:

* Cadastro de clientes
* Criação de contas
* Depósitos
* Saques
* Histórico de transações

---

## 🚀 Tecnologias Utilizadas

* Python 3
* Programação Orientada a Objetos (POO)

---

## 🧠 Conceitos Aplicados

Durante o desenvolvimento foram utilizados diversos conceitos importantes da POO:

* Classes e Objetos
* Herança
* Encapsulamento
* Classes Abstratas
* Polimorfismo
* Composição
* Métodos especiais

---

## 📂 Estrutura do Projeto

### Cliente

Responsável por armazenar os dados do cliente e suas contas.

### PessoaFisica

Herda da classe Cliente e adiciona:

* CPF
* Nome
* Data de nascimento

### Conta

Classe responsável pelas operações bancárias:

* saque
* depósito
* saldo

### ContaCorrente

Herda da classe Conta e adiciona:

* limite de saque
* quantidade de saques permitidos

### Historico

Armazena todas as transações realizadas pelo cliente.

### Transacao

Classe abstrata usada como base para:

* Saque
* Deposito

---

## ▶️ Funcionalidades

✔️ Criar cliente
✔️ Criar conta corrente
✔️ Realizar depósitos
✔️ Realizar saques
✔️ Exibir saldo
✔️ Registrar histórico de transações

---

## 💻 Exemplo de Execução

```bash
Testando cadastro de conta do cliente
Sucesso! Cliente registrado: Lola

Conta Corrente número 2 criada com sucesso!

=== TESTANDO SISTEMA COM HISTÓRICO ===
-> Depósito: R$ 200.0
-> Saque: R$ 50.0

=== TESTANDO SAQUE ===
Saldo final após o saque: R$ 100.00
```

---

## 📚 Aprendizados

Esse projeto foi importante para praticar:

* modelagem de sistemas
* organização de código
* reutilização de classes
* boas práticas em Python
* estruturação utilizando POO

---

## 🔮 Melhorias Futuras

* Interface gráfica
* Persistência de dados
* Sistema de login
* Banco de dados SQLite
* Transferências entre contas
* Extrato completo

---

## 👩‍💻 Autor

Projeto desenvolvido por Carol Anjos durante os estudos de Python e Programação Orientada a Objetos.

