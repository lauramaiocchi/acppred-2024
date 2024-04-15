# acppred

By Laura de Vargas Maiocchi

anticancer peptide prediction software

## Setup

Run the following comand to install the acppred program (mamba is required).

```
$ make setup
```

- 'Makefile' arquivo que centraliza os comandos a serem executados pelo programa 'make'.
- Environment.yml: são arquivos de execução ambiente mamba (conda) (dependências). Possibilidade de criar um environment.yml arquivo que vai descrever o ambiente de software do projeto. 
- Environment.txt arquivo de instalação pip (bibliotecas).
  
- **O que é a ferramenta conda, e qual a sua utilidade no desenvolvimento de programas em Python?**
    O conda é uma ferramenta para criação de Ambientes Virtuais, estes são pastas dentro do computador que possuem todos os requisitios para executar um programa específico. Ou seja, o Conda é uma ferramenta de gerenciamento de ambientes e dependências em Python (e também em outros, como R). Ele é amplamente usado para simplificar o processo de instalação e gerenciamento de bibliotecas, permitindo que você crie ambientes isolados onde pode instalar diferentes versões de pacotes sem interferir no ambiente global do sistema. A principal utilidade do Conda no desenvolvimento de programas em Python incluem: o gerenciamento de pacotes, podendo instalar, atualizar e remover pacotes facilmente. Além de permitir que você crie ambientes virtuais independentes uns dos outros, onde você pode instalar diferentes versões de pacotes e até mesmo versões diferentes do Python. Isso é útil quando você está trabalhando em vários projetos que têm dependências conflitantes.

  Uma das melhores características do Conda é sua capacidade de resolver automaticamente dependências. Quando você instala um pacote, o Conda verifica todas as dependências necessárias e as instala automaticamente, garantindo que tudo funcione corretamente. A portabilidade: pode-se facilmente compartilhar ambientes de trabalho com outras pessoas. Isso torna mais fácil reproduzir o ambiente de desenvolvimento em diferentes máquinas, garantindo consistência e evitando problemas de compatibilidade. E também a facilidade de uso: sua sintaxe simples e intuitiva o torna acessível mesmo para iniciantes, e sua documentação abrangente é uma grande ajuda para resolver problemas comuns.

- **Como funciona a ferramenta ACPred? Qual a sua finalidade?**
  É uma ferramenta de predição de peptídeos anticâncer. É possível realizar essa predição por meio de técnicas de apredizagem de máquina. A ferramenta, treinada, irá analisar as características requeridas, como por exemplo composição de aminoácidos, com a finalidade de predizer ao pesquisador se tal peptídeo possui ou não, atividade anticâncer.

- **O que são aplicações CLI? Quais os comandos e opções (argumentos) criadas para a ferramenta desenvolvidas no projeto?**
   Aplicações CLI, são aplicações de uma interface de linha de Comando, uma forma de interação do usuário com o computador, realizada por meio de comandos de texto possibilitando a execução de várias tarefas. **FINALIZAR**

- **O que é back-end e front-end no contexto de aplicação web?**
  O front-end é responsável pela interface do usuário e pela interação do usuário, enquanto o back-end é responsável pelo processamento de dados. Ambas as partes trabalham juntas para fornecer uma experiência completa e funcional aos usuários de uma aplicação web.
  O **front-end** é a parte da aplicação web com a qual os usuários interagem diretamente em seus navegadores. Consiste em tecnologias como HTML, CSS e JavaScript, que são usadas para criar a interface do usuário e a experiência do usuário. Responsável pela apresentação e interação do usuário, incluindo o layout, design, cores, animações e eventos de interação. As principais responsabilidades do front-end incluem renderizar páginas da web, validar entradas do usuário, enviar solicitações para o back-end e exibir dados retornados pelo back-end. Manda requisições e recebe requisições.
  O **back-end** é a parte da aplicação web que lida com o processamento de dados e a comunicação com o servidor. Ele consiste em uma variedade de tecnologias, como linguagens de programação (como Python, Java), frameworks (como Django, Flask), bancos de dados e servidores web. Responsável por processar solicitações do front-end, executar operações no banco de dados, autenticar usuários, gerar respostas dinâmicas e fornecer dados para o front-end. Ele pode envolver a implementação de Interfaces de Programação de Aplicações para permitir a comunicação entre o front-end e o back-end.

- **O que são testes unitários? Qual a sua importância no desenvolvimento de software?**
  Os Testes unitários são uma prática de desenvolvimento de software na qual partes individuais do código são testadas de forma isolada para garantir que funcionem conforme o esperado. (Uma unidade pode ser uma função, um método de classe ou até mesmo um pequeno bloco de código).
  A importância dos testes unitários no desenvolvimento de software é significativa, garantindo qualidade, pois ajudam a garantir que cada parte do código funcione conforme o esperado, ajudando a identificar e corrigir erros precocemente no ciclo de desenvolvimento, reduzindo a quantidade de bugs que podem surgir em estágios posteriores. Também facilitam a integração contínua e entrega contínua, uma vez que os testes unitários são uma parte essencial desse processo, sendo executados automaticamente sempre que há uma alteração no código, garantindo que o software seja entregue de forma consistente e confiável. Além disso, quando é preciso fazer alterações em um código existente, os testes unitários garantem que as mudanças não quebrem o comportamento existente. Isso dá confiança aos desenvolvedores para fazer alterações no código sem medo de introduzir novos bugs inadvertidamente.






