Sistema de Biblioteca com Persistência
Sistema criado para a disciplina de Programação Orientada a Objetos (POO) do curso de Ciência da Computação na UFPB.

A ideia foi criar um sistema simples para cadastrar e gerenciar livros, onde é possível adicionar um livro informando título, autor, ISBN, ano de publicação e preço. O sistema também permite pesquisar e remover livros, além de verificar se um livro é considerado clássico (mais de 50 anos). Os dados são salvos em arquivo para que não se percam ao fechar o programa.

O que o sistema faz
Cadastrar livros com título, autor, ISBN, ano de publicação e preço
Buscar livro pelo ISBN
Listar todos os livros cadastrados
Remover livro pelo ISBN
Verificar se o livro é um clássico (mais de 50 anos desde a publicação)
Salvar e carregar os dados de um arquivo .dat
Classes principais
Classe	Descrição
Livro	Representa um livro (implementa Serializable)
SistemaLivro	Gerencia os livros usando um HashMap
ISistemaBiblioteca	Interface documentada com Javadoc
GravadorDeDados	Salva e recupera os dados em arquivo
ProgramaPrincipal	Programa principal com cadastro, pesquisa e remoção
LivroJaExisteException	Exceção para livro duplicado
LivroNaoEncontradoException	Exceção para livro não encontrado
SistemaLivroTest	Testes com JUnit 5
Tecnologias
Java 17+
JUnit 5
Maven
Autor
Abner Matheus dos Santos Silva
