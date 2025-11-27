# Projeto-final-python-Vladimir-Gustavo-Melo-da-Silva-Francisco-Nielsen-Lemos-Pitombeira
Sistema de Gerenciamento de Livros – CRUD em Python
Este projeto faz parte do Trabalho Final da disciplina Programação I (Python).
O objetivo é desenvolver um sistema simples, funcional e totalmente baseado em terminal, utilizando conceitos fundamentais de programação.

O sistema implementa todas as operações de um CRUD:

Create (Criar)
Read (Ler/Listar)
Update (Atualizar)
Delete (Remover)
Como o Sistema Funciona
Ao executar o programa, o usuário interage com um menu principal, que permite escolher a ação desejada.
Todos os livros são armazenados em uma lista de dicionários, e cada livro possui:

id (gerado automaticamente)
título
autor
disponibilidade (True / False)
O usuário navega pelo sistema digitando números correspondentes às opções do menu.

Menu Principal
Quando o programa inicia, o seguinte menu é exibido:

===== SISTEMA DE LIVROS ===== 1 - Cadastrar livro 2 - Listar livros 3 - Atualizar livro 4 - Remover livro 5 - Relatório 6 - Sair

Cada opção executa uma função específica do CRUD.

Detalhamento das Funcionalidades
Cadastrar Livro
Permite inserir um novo livro informando:

Título
Autor
Disponibilidade (s/n)
Após o cadastro, o sistema cria automaticamente um ID único.

Exemplo de uso:

--- CADASTRAR LIVRO --- Título: Percy Jackson Autor: Rick Riordan Disponível? (s/n): s Livro cadastrado com sucesso!

Listar Livros
Exibe todos os livros já cadastrados no sistema.

Exemplo:

--- LISTA DE LIVROS --- ID: 1 | Percy Jackson - Rick Riordan (Disponível) ID: 2 | Dom Casmurro - Machado de Assis (Indisponível)

Atualizar Livro
Permite alterar dados de um livro já cadastrado.
O usuário informa o ID e escolhe o que quer alterar.

Se deixar um campo vazio, o valor atual é mantido.

Exemplo:

--- ATUALIZAR LIVRO --- Informe o ID do livro: 1 Editando: Percy Jackson - Rick Riordan Novo título (Enter para manter): Percy Jackson e o Mar de Monstros Novo autor (Enter para manter): Disponível? (s/n ou Enter p/ manter): s Livro atualizado!

Remover Livro
Remove um livro do sistema informando seu ID.

Exemplo: --- REMOVER LIVRO --- Informe o ID do livro: 2 Livro removido com sucesso!

Relatório
Mostra uma análise simples dos livros cadastrados:

Quantidade total
Quantos estão disponíveis
Quantos estão emprestados
Exemplo: --- RELATÓRIO --- Total de livros cadastrados: 4 Livros disponíveis: 3 Livros emprestados: 1

Como Executar
Certifique-se de ter o Python 3 instalado.
Baixe este repositório.
No terminal, execute o arquivo:
python sistema_livros.py

Integrantes:
Vladimir Gustavo
Franciso Lemos
