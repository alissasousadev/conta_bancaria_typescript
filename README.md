<br clear="both">

<h1 align="center">Projeto Conta Bancária</h1>

###

<p align="center">Um sistema de gerenciamento básico de contas bancárias implementado via linha de comando (CLI) utilizando Programação Orientada a Objetos (POO) como classes abstratas, herança, interfaces, padrões de organização de código e princípios de arquitetura em TypeScript. O projeto foi construído por etapas durante o Bootcamp Generation, simulando um cenário real de desenvolvimento de software.</p>

###

<br clear="both">

<h2 align="center">Detalhes da Implementação e Conceitos Aplicados</h2>

###

<p align="center">Inicialmente, foi criada a Classe Menu, responsável por toda a interação com o usuário via terminal. Essa classe centraliza as opções do sistema e direciona as ações para as funcionalidades correspondentes, permitindo uma navegação clara e organizada. Em seguida, o menu foi aprimorado com uma versão colorida, proporcionando uma melhor experiência visual no terminal.</p>

###

<div align="center">
  <img height="220" src="https://camo.githubusercontent.com/f7812964d77c962641f0517dab1988d84a3d7a59aa4b6751cf3631dfd4ec3a6d/68747470733a2f2f692e696d6775722e636f6d2f385553717147572e706e67"  />
</div>

###

<p align="left">O sistema foi estruturado a partir da Classe Conta, que representa uma conta bancária genérica e posteriormente foi refatorada para o modelo de Classe Abstrata, garantindo o compartilhamento de regras comuns e impedindo a instanciação direta. A partir dela, foram criadas as classes ContaCorrente e ContaPoupanca, aplicando Herança e Polimorfismo, permitindo comportamentos específicos para cada tipo de conta dentro de uma estrutura comum.<br><br>O Encapsulamento foi utilizado para proteger os atributos das classes, assegurando que o acesso e a modificação dos dados ocorram apenas por meio de métodos controlados. A tipagem estática do TypeScript foi aplicada em todo o projeto para aumentar a segurança, reduzir erros e melhorar a legibilidade do código.<br><br>Para padronizar a manipulação das contas, foi criada a Interface ContaRepository, definindo os contratos para acesso e gerenciamento dos dados, o que contribui para uma arquitetura mais flexível. A lógica de negócio ficou centralizada na Classe ContaController, responsável pelos métodos de CRUD e pelas operações bancárias de depósito, saque e transferência, seguindo uma arquitetura em camadas (Model / Controller / Repository).</p>

###

<h2 align="center">Tecnologias Utilizadas</h2>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=alissasousadev.alissasousadev&left_color=black&right_color=blue"  />
</div>

###
