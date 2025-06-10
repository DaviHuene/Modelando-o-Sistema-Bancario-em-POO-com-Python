
# 💸 Sistema Bancário em Python (Terminal)

Este projeto é uma simulação de sistema bancário orientado a objetos desenvolvido em Python puro, com interface de linha de comando. Ele permite criar usuários, contas, realizar saques, depósitos e consultar extratos de forma simples e estruturada.

## 🚀 Funcionalidades

- Criar novo usuário (cliente)
- Criar conta bancária (corrente)
- Realizar depósitos
- Realizar saques (com limite de valor e quantidade)
- Exibir extrato da conta
- Listar todas as contas cadastradas

## 🧱 Arquitetura

O sistema segue boas práticas de **POO (Programação Orientada a Objetos)**:

- `Cliente` (e `PessoaFisica`)
- `Conta` e `ContaCorrente`
- `Transacao` com subclasses `Saque` e `Deposito`
- `Historico` para armazenar as movimentações

## 🖥️ Como usar

1. Clone o projeto ou baixe os arquivos `.py`.

2. Execute no terminal:

```bash
python nome_do_arquivo.py
```

3. Siga o menu interativo:

```text
================== MENU ===================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova Conta
[lc] Listar Contas
[nu] Novo Usuário
[q] Sair
===========================================
```

## 🧪 Exemplo de uso

- Primeiro, crie um usuário (`nu`)
- Depois, crie uma conta para ele (`nc`)
- Faça um depósito (`d`) e, em seguida, um saque (`s`)
- Veja o extrato com (`e`)

## 📦 Requisitos

- Python 3.7+
- (Opcional) [`rich`](https://github.com/Textualize/rich) para uma interface colorida:
  ```bash
  pip install rich
  ```

## 📁 Estrutura sugerida

```
sistema_bancario/
├── banco.py          # (ou outro nome, com seu código principal)
├── README.md
```

## 📌 Limites

- Saques limitados a 3 por dia
- Valor máximo por saque: R$500,00
- Apenas uma conta por cliente neste modelo simplificado

## 🛠️ Melhorias futuras

- Suporte a múltiplas contas por cliente
- Interface gráfica (Tkinter ou PyQt)
- Armazenamento em arquivo ou banco de dados
- Autenticação de usuário

## 🧑‍💻 Autor

Desenvolvido por [Seu Nome Aqui] – sinta-se livre para modificar e evoluir o projeto.

---

Feito com ❤️ em Python.
