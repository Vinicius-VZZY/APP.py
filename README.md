#### Vinicius Guimarães Urquiza (VZZY)


# Desafio 1
<<<<<<< HEAD
=======

## VCS (Sistema de Controle de Versões)


Um Sistema de Controle de Versões (SCV) é uma ferramenta que ajuda a gerenciar mudanças em um projeto de software, documento ou qualquer outro tipo de arquivo. Ele permite que você controle e gerencie diferentes versões de um arquivo ou conjunto de arquivos, mantendo um registro de todas as alterações feitas.

#### Vantagens no uso do VCS

- Registrar todas as alterações feitas em um arquivo ou projeto;
- Identificar quem fez cada alteração e quando;
- Reverter para uma versão anterior se necessário;
- Trabalhar em paralelo com outros desenvolvedores ou colaboradores sem conflitos;
- Manter um registro de todas as alterações para auditoria ou propósitos de conformidade.

Sistema de Controle de Versões Centralizado (CVCS): Nesse modelo, todos os arquivos e histórico de alterações são armazenados em um servidor central. Os usuários devem se conectar ao servidor para realizar alterações ou obter atualizações.

Sistema de Controle de Versões Distribuído (DVCS): Nesse modelo, cada usuário tem uma cópia completa do projeto e do histórico de alterações em seu computador local. Isso permite que os usuários trabalhem offline e sincronizem suas alterações posteriormente.

Exemplos de Sistemas de Controle de Versões populares incluem Git, SVN, Mercurial e Perforce.


# Desafio 2

## Defina o que é programação orientada a objetos (POO) e cite seus pilares

A Programação Orientada a Objetos (POO) é um paradigma de programação que organiza o código em objetos que contêm dados e funções que operam sobre esses dados, permitindo uma abordagem mais modular, flexível e escalável para o desenvolvimento de software.

#### Pilares/Princípios: Os quatro pilares fundamentais da POO são:

- Abstração: Representar objetos do mundo real ou conceitos abstratos como entidades que possuem características e comportamentos.
- Encapsulamento: Ocultar a implementação interna de um objeto e expor apenas as informações necessárias ao exterior, protegendo assim a integridade dos dados.
- Herança: Permitir que um objeto herde as características e comportamentos de outro objeto, facilitando a reutilização de código e a criação de hierarquias de objetos.
- Polimorfismo: Permitir que objetos de diferentes classes respondam a mensagens ou chamadas de métodos de forma diferente, dependendo do contexto e do tipo de objeto.

Além disso, outros princípios importantes da POO incluem:

- Composição: Criar objetos compostos por outros objetos, permitindo a criação de estruturas mais complexas.
- Interface Segregation: Dividir interfaces em partes menores e mais específicas, tornando mais fácil a implementação e a manutenção.
- Single Responsibility Principle (SRP): Cada objeto ou classe deve ter apenas uma responsabilidade ou função bem definida.

#### Exemplifique e explique um cenário de abstração:

A abstração é um conceito fundamental na Programação Orientada a Objetos (POO) que permite representar objetos do mundo real ou conceitos abstratos como entidades que possuem características e comportamentos.
Imagine que você está criando um sistema de gerenciamento de veículos. Você pode abstrair o veículo como uma entidade que tem as seguintes características:

marca (atributo)
modelo (atributo)
ano (atributo)
E os seguintes comportamentos:

ligar() (método)
desligar() (método)
acelerar() (método)
Nesse exemplo, a abstração permite representar o veículo como uma entidade que pode ser manipulada e gerenciada de forma independente, sem se preocupar com os detalhes internos do funcionamento do veículo.


# Desafio 3
>>>>>>> Desafio3

## VCS (Sistema de Controle de Versões):


<<<<<<< HEAD
Um Sistema de Controle de Versões (SCV) é uma ferramenta que ajuda a gerenciar mudanças em um projeto de software, documento ou qualquer outro tipo de arquivo. Ele permite que você controle e gerencie diferentes versões de um arquivo ou conjunto de arquivos, mantendo um registro de todas as alterações feitas.

#### Vantagens no uso do VCS:

- Registrar todas as alterações feitas em um arquivo ou projeto;
- Identificar quem fez cada alteração e quando;
- Reverter para uma versão anterior se necessário;
- Trabalhar em paralelo com outros desenvolvedores ou colaboradores sem conflitos;
- Manter um registro de todas as alterações para auditoria ou propósitos de conformidade.

Sistema de Controle de Versões Centralizado (CVCS): Nesse modelo, todos os arquivos e histórico de alterações são armazenados em um servidor central. Os usuários devem se conectar ao servidor para realizar alterações ou obter atualizações.

Sistema de Controle de Versões Distribuído (DVCS): Nesse modelo, cada usuário tem uma cópia completa do projeto e do histórico de alterações em seu computador local. Isso permite que os usuários trabalhem offline e sincronizem suas alterações posteriormente.

Exemplos de Sistemas de Controle de Versões populares incluem Git, SVN, Mercurial e Perforce.

# Desafio 4

## Defina com suas palavras qual é a responsabilidade das camadas: entity,controller, repository e service em um sistema organizado em camadas de uma API:

Em uma API organizada em camadas, cada camada tem uma responsabilidade específica para garantir que o sistema seja escalável, flexível e fácil de manter. Aqui estão as definições das responsabilidades das camadas:

##### Entity (Entidade)

A camada de entidade é responsável por representar os dados do sistema. Uma entidade é uma classe que define a estrutura e os comportamentos de um objeto de negócios, como um usuário, um produto ou uma ordem. A responsabilidade da camada de entidade é:

- Definir a estrutura dos dados do sistema
- Implementar comportamentos básicos dos objetos de negócios
- Ser a fonte de verdade para os dados do sistema

#### Repository (Repositório)

A camada de repositório é responsável por gerenciar a persistência dos dados do sistema. Um repositório é uma classe que define como os dados são armazenados e recuperados do banco de dados ou de outra fonte de dados. A responsabilidade da camada de repositório é:

- Gerenciar a persistência dos dados do sistema
- Fornecer uma interface para acessar e manipular os dados
- Abstrair a complexidade do banco de dados ou da fonte de dados

#### Service (Serviço)

A camada de serviço é responsável por implementar a lógica de negócios do sistema. Um serviço é uma classe que define como as entidades e repositórios são utilizados para realizar operações de negócios, como autenticar um usuário ou processar uma ordem. A responsabilidade da camada de serviço é:

- Implementar a lógica de negócios do sistema
- Coordenar as interações entre as entidades e repositórios
- Fornecer uma interface para acessar as funcionalidades do sistema

#### Controller (Controlador)

A camada de controlador é responsável por receber e processar as solicitações da API. Um controlador é uma classe que define como as solicitações são recebidas, validadas e processadas, e como as respostas são enviadas de volta ao cliente. A responsabilidade da camada de controlador é:

- Receber e processar as solicitações da API
- Validar e sanitizar os dados de entrada
- Chamar os serviços para realizar as operações de negócios
- Enviar as respostas de volta ao cliente

Essas camadas trabalham juntas para garantir que o sistema seja escalável, flexível e fácil de manter. Cada camada tem uma responsabilidade específica e bem definida, o que ajuda a reduzir a complexidade do sistema e a facilitar a manutenção e o desenvolvimento.