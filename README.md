# UTF-Hub por: Leonardo Tosin e Alana Maiumy

## 🔎 **Sobre o projeto**

Este é um projeto acadêmico desenvolvido em dupla por **Alana Maiumy** e **Leonardo Tosin** como parte das atividades do curso de Sistemas para Internet na **UTFPR**.  
O principal objetivo foi aplicar conhecimentos fundamentais em desenvolvimento front-end com **Angular**, focando em:

- Princípios de usabilidade e experiência do usuário;
- Estruturação de componentes reutilizáveis;
- Integração com API fake (simulada via JSON Server);
- Navegação SPA com rotas protegidas;
- Validação de formulários;
- Comunicação entre componentes e serviços.

A ideia central da aplicação é simular uma plataforma acadêmica digital (hub universitário), onde o usuário pode navegar por diferentes seções, interagir com a interface e visualizar dados dinâmicos.  
Este projeto reflete práticas modernas de desenvolvimento web, organização em equipe e versionamento com Git.

O frontend da aplicação foi desenvolvido com Angular e o backend foi simulado pela implementação de uma API Fake, usando o JSON Server.

## Video de apresentação do projeto

https://youtu.be/824cMjdzVp0 

## Endereço original de Deploy

https://github.com/LeonardoTosinPR/utf-hub. 

## Protótipo

https://www.figma.com/proto/jCW7FJocGbD31wCPnUUo7j/Prototipo-de-Tela?node-id=13-2&t=UXAZWupBoFS46Hxu-1. 


## Manual de execução
- Clonar o repositório com `git clone`
- Fazer checkout no branch `develop` que contém as modificações mais recentes
- Abrir o projeto no editor Visual Studio Code (VS Code)
- Abrir um terminal pelo VSCode ou qualquer terminal do seu Sistema Operacional apontando para o diretório raiz do projeto 
- Instalar as dependências contidas no `package.json`
  - Comando: `npm i`
- Abrir um novo terminal pelo VSCode e então executar o projeto Angular
  - Comando: `ng s -o`
  - O projeto vai iniciar (provavelmente) na porta 4200 caso não abra o projeto direto no navegador

## 🚀 Tecnologias Utilizadas

- Angular 17+
- TypeScript
- SCSS e BootStrap
- HTML5 + CSS3

## 📫 Contato
Email: alana.maiumy@gmail.com

LinkedIn: linkedin.com/in/alana-maiumy

GitHub: github.com/lanamaiumy

## Checklist
#### RA1 - Prototipar e projetar interfaces gráficas de usuário, considerando princípios de usabilidade e experiência do usuário.
- [x] ID1: O aluno desenvolveu protótipos de interfaces que demonstram compreensão das diretrizes de usabilidade.
- [x] ID2: O aluno projetou interfaces responsivas que se adaptam a diferentes tamanhos de tela.
#### RA2 - Criar e reutilizar componentes em frameworks frontend, desenvolvendo interfaces modulares, responsivas e estilizadas.
- [x] ID3: O aluno desenvolveu componentes reutilizáveis que são aplicáveis em diferentes contextos da aplicação, garantindo que se adaptem de maneira responsiva em vários tamanhos de tela.
- [x] ID4: O aluno incorporou componentes de frameworks CSS para aprimorar a aparência e funcionalidade da aplicação de maneira consistente.
- [x] ID5: O aluno aplicou diretivas estruturais para renderizar elementos de forma condicional, permitindo a exibição ou ocultação de conteúdo com base em condições dinâmicas.main
- [x] ID6: O aluno utilizou diretivas estruturais para repetir elementos de interface de maneira dinâmica, a fim de criar listas, galerias ou outras visualizações baseadas em conjuntos de dados.
- [x] ID7: O aluno aplicou Pipes de maneira eficaz para formatar a apresentação de dados, garantindo que as informações exibidas sejam legíveis, esteticamente agradáveis e atendam aos requisitos de apresentação específicos para cada contexto.
#### RA3 - Sincronizar dados entre a interface gráfica e o modelo de dados, aplicando técnicas de binding para manter a consistência.
- [x] ID8: O aluno demonstrou a compreensão e a aplicação de técnicas de one-way data binding, como Interpolation e Property Binding, para exibir e atualizar dados na interface gráfica de maneira unidirecional.
- [x] ID9: O aluno demonstrou a aplicação de técnicas de event binding para capturar eventos do usuário na interface e interagir com o modelo de dados, mantendo a consistência e a sincronização entre os dois.
- [x] ID10: O aluno implementou a técnica de two-way data binding para criar uma sincronização bidirecional automática entre a interface e o modelo de dados, permitindo uma atualização eficiente dos dados em ambos os lados.
- [x] ID11: O aluno fez uso eficaz de variáveis de template para manipulação dinâmica dos dados na interface gráfica, demonstrando a capacidade de exibir informações de maneira flexível e adaptável.
#### RA4 - Implementar comunicação eficaz entre componentes, utilizando padrões de comunicação e serviços para compartilhar lógica e dados.
- [x] ID12: O aluno criou comunicação entre componentes não relacionados hierarquivamente por meio de serviços através do mecanismo de injeção de dependência, compartilhando lógica ou informações.
- [x] ID13: O aluno utilizou efetivamente as diretivas @Input e @Output para estabelecer uma comunicanção em uma hierarquia de componentes, passando e recebendo dados entre componentes de maneira segura e consistente.
#### RA5 - Criar interfaces de navegação intuitivas e responsivas, implementando roteamento em aplicações de página única (SPA).
- [x] ID14: O aluno configurou rotas para diferentes partes da aplicação, permitindo a navegação entre páginas distintas.
- [ ] ID15: O aluno demonstrou a habilidade de passar dados entre componentes que representam diferentes telas usando parâmetros de rotas, garantindo uma troca eficiente de informações.
- [ ] ID16: O aluno criou uma estrutura de navegação aninhada para representar hierarquias de conteúdo.
- [x] ID17: O aluno aplicou guardas de rotas para controlar o acesso a rotas específicas da aplicação, assegurando que somente usuários autorizados possam acessar determinadas partes da interface.
#### RA6 - Realizar requisições assíncronas para serviços web, compreendendo os protocolos e formatos de troca de dados, tratando respostas e erros.
~~- [ ] ID18: O aluno fez requisições assíncronas a uma API pública, compreendendo os protocolos HTTP e formatos de dados para no mínimo a operação GET.~~

~~- [ ] ID19: O aluno fez requisições assíncronas a uma API simulada, compreendendo os protocolos HTTP e formatos de dados para as operações GET, POST, PUT, PATCH e DELETE.~~
- [ ] ID20: O aluno tratou respostas de sucesso e erros das requisições assíncronas de forma apropriada.
- [x] ID21: O aluno aplicou validações de entrada nos campos do formulário, utilizando técnicas como expressões regulares (REGEX), e apresentou mensagens de erro claras e informativas para auxiliar os usuários a corrigir entradas incorretas.
- [x] ID22: O aluno desabilitou adequadamente o botão de submit enquanto o formulário continha campos inválidos, promovendo uma experiência de usuário mais intuitiva e evitando a submissão de dados incorretos.
- [ ] ID23: O aluno demonstrou a capacidade de utilizar Promises para tratar respostas assíncronas.
- [x] ID24: O aluno demonstrou a capacidade de utilizar Observables para tratar respostas assíncronas.
#### RA7 - Gerenciar o código-fonte de maneira eficiente, implementar boas práticas de controle de versão e colaborar em projetos de desenvolvimento.
- [x] ID25: O aluno criou um repositório no GitHub utilizando a estrutura do Gitflow, estabelecendo as branches "main" e "develop", demonstrando proficiência em boas práticas de controle de versão e organização do projeto.
- [x] ID26: O aluno colaborou de maneira efetiva com outros membros do projeto, realizando fusões (merges) e resolução de conflitos de código de forma adequada e alinhada às práticas de desenvolvimento colaborativo.
- [x] ID27: O aluno planejou, configurou e executou o processo de build da aplicação, preparando-a para produção e realizou o deploy em um ambiente de hospedagem, tornando-a prontamente acessível para uso.