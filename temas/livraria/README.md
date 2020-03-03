# Bem-vindo ao processo seletivo da Ewave 

## Desafio

A editora "To do" é uma empresa multinacional que atua no seguimento de venda de livros físicos, possui mais de 20 lojas espalhadas pelo mundo, seu sucesso é devido a qualidade de atendimento e atualização constante de sua biblioteca com rapidez e dedicação em tudo o que fazem. 

Com esse enorme sucesso, se propos a ajudar as instituições de ensino com emprestimos de seu variado catalogo de livros para os Estudantes. 
Tendo em vista essa necessidade, foi visto a necessidade de desenvolver um sistema que controla-se esses emprestimos

##Contexto

Para a implementação desse sistema foram elencados os seguintes requisitos:

#### Usuarios
 
* Deve-se permitir a inclusão/alteração/inativação dos usuarios com os seguinte atributos:

    1. Nome
    2. Endereço
    3. CPF
    4. Instituição de Ensino
    5. Telefone
    6. E-mail

#### Instituição de Ensino 
* Deve-se permitir a inclusão/alteração/inativação com os seguintes atributos:
    1. Nome
    2. Endereço
    3. CPNJ
    4. Telefone

#### Livros
* Deve-se permitir a inclusão/alteração/inativação dos livros com os seguinte atributos:

    1. Título 
    2. Gênero
    3. Autor     
    4. Sinopse
    5. Capa (imagem)

 
## Itens Obrigatórios

   * Todo usuario deve ter um nome, um cpf, e (telefone ou e-mail)
   * Toda instituição de ensino deve ter nome, endereço, cnpj e telefone.
   * Todo livro deve ter título, gênero, autor e capa.

## Regras

* Todo usuario pode emprestar no maximo 2 livros.
* Todo emprestimo deve ser no maximo de 30 dias para cada livro.
* Informar ao Administrador do Sistema caso um livro extrapole o prazo máximo de dias emprestado.
* O Usuário que infringir a regra dos dias fica impossibilitado de emprestar qualquer outro livro até a devolução e só poderá emprestar novamente após 30 dias.
* Livros emprestados deverão estar indisponiveis para outros Usuários.
* Permitir reservar livros. 
 
