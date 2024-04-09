# Orientações sobre estilo e boas práticas de codificação Java
### Este documento destina-se a estabelecer um conjunto de padrões de estilo e boas práticas de codificação em Java, visando promover a qualidade, a manutenção e a escalabilidade em projetos de engenharia de software. O cumprimento destas diretrizes ajudará a equipe a desenvolver um código consistente, legível e eficiente.
&nbsp;

# 1. Entendendo estilo e boas práticas
## 1.1 O que são?
Quando falamos sobre estilo e boas práticas no mundo da programação, estamos basicamente conversando sobre aquelas regras não escritas (bom, algumas são escritas) que fazem toda a diferença em pedaços de código.
Essas diretrizes e convenções são a bússola que os programadores seguem para garantir que seus códigos não sejam apenas um monte de palavras e números jogados de qualquer jeito. Elas ajudam a tornar o código mais limpo, como um texto bem formatado que é fácil de ler e entender.

## 1.2 Para que servem?
Adotar boas práticas de codificação e um estilo consistente não é apenas uma questão de cortesia profissional, é essencial para manter o código compreensível não só para a atual equipe de desenvolvimento mas também para aqueles que venham a ser integrados posteriormente no projeto, além de permitir que todos possam e consigam achar o que procuram no código.

&nbsp;
# 2. Aspectos:
## 2.1 Legibilidade:
É a facilidade com que um código pode ser lido e compreendido por outros programadores (ou até mesmo por você mesmo, no futuro).
Ela pode ser influenciada por fatores como nomes expressivos e descritivos para variáveis, funções e classes que sigam um padrão. Tais padrões sendo PascalCase para classes e interfaces, camelCase para variáveis e métodos e o UPPER_SNAKE_CASE para constantes.

Nosso projeto, neste aspecto, utiliza os padrões citados acima: 
- PascalCase: classes e interfaces.
- camelCase: variáveis e métodos.
- UPPER_SNAKE_CASE: para constantes.

## 2.2 Estrutura e formatação:
É a maneira como o código é organizado e apresentado visualmente. Esses é um elemento que influencia diretamente a legibilidade do código.
Juntos, a estrutura e a formatação do código desempenham um papel crucial na manutenção da qualidade do software. Códigos bem estruturados e formatados não são apenas mais agradáveis de ler e trabalhar, mas também facilitam a detecção de erros, a revisão de código por pares e a incorporação de novos desenvolvedores ao projeto.

### 2.2.1 Estrutura:
Diz respeito à sua organização lógica e arquitetônica. Isso inclui a maneira como as classes, funções, módulos e outros componentes são organizados, bem como a relação entre eles.
Alguns elementos estruturais são:
- Modularização: Dividir o código em módulos ou componentes com responsabilidades claras e bem definidas.
- Hierarquia e Herança: Organizar classes e objetos de maneira hierárquica para promover a reutilização de código.
- Padrões de Projeto: Aplicar padrões de projeto reconhecidos para resolver problemas comuns de design de software de maneira eficaz.

### 2.2.2 Formatação:
Trata da apresentação visual do código, incluindo aspectos como indentação, uso de espaços e linhas em branco, e convenções de nomenclatura. Embora possa parecer trivial à primeira vista, a formatação consistente e intuitiva torna o código mais acessível e fácil de ler.
Alguns elementos da formatação são:
- Indentação: Usar espaços ou tabs para criar uma hierarquia visual, facilitando a identificação de blocos de código, como corpos de funções, loops e condicionais.
- Espaçamento: Utilizar espaços em branco adequadamente, como entre operadores e operandos, para tornar o código mais claro.
- Linhas em Branco: Inserir linhas em branco entre declarações ou blocos de código para separar visualmente componentes lógicos distintos.
- Convenções de Nomenclatura: Seguir um conjunto consistente de regras para a nomenclatura de variáveis, funções, classes e outros identificadores, como camelCase ou snake_case.

## 2.3 Princípios de Programação:
São diretrizes fundamentais que orientam os desenvolvedores na criação de software.
Eles servem como um conjunto de melhores práticas acumuladas ao longo dos anos pela comunidade de desenvolvimento de software. Adotar esses princípios pode levar a um código de maior qualidade e a projetos de software mais bem-sucedidos. 

### Alguns princípios famosos:
### 2.3.1 DRY (Don't Repeat Yourself)
Este princípio enfatiza a importância de evitar a repetição de código. A ideia é que cada peça de informação deve ter uma representação única, não ambígua e definitiva dentro do sistema. Seguir o princípio DRY pode reduzir a quantidade de código redundante, facilitando a manutenção e a atualização do software.

### 2.3.2 KISS (Keep It Simple, Stupid)
O princípio KISS sugere que a simplicidade deve ser uma meta-chave no design de software, e que se deve evitar a complexidade desnecessária. Isso não significa que todo software deve ser simples, mas que os desenvolvedores devem procurar a solução mais simples que resolva o problema efetivamente.

### 2.3.3 YAGNI (You Ain't Gonna Need It)
Originário da programação extrema (XP), esse princípio aconselha os desenvolvedores a não adicionar funcionalidades até que elas sejam realmente necessárias. Isso evita gastar tempo e recursos em partes do software que podem nunca ser usadas ou que adicionam complexidade desnecessária ao projeto.

### 2.3.4 Encapsulamento
Encapsulamento é a prática de ocultar os detalhes internos do funcionamento de uma classe e expor apenas o necessário para o mundo exterior. Isso protege os dados internos da classe e é fundamental para a abstração.

### 2.3.5 Separation of Concerns (Separação de Preocupações)
Este princípio defende que um software deve ser dividido em seções distintas, onde cada seção aborda uma preocupação específica. Isso facilita a manutenção e a atualização do software, além de tornar o código mais fácil de entender.

## 2.4 Manutenibilidade:
É, basicamente, a medida de quão fácil é manter, modificar, corrigir, ou estender um sistema ou aplicação ao longo do tempo, um software com alta manutenibilidade é aquele que pode ser atualizado ou adaptado com esforço mínimo.
A essa dedicação à manutenibilidade garante que nosso projeto possa suportar mudanças, melhorias e atualizações, e, assim, evoluir com o passar do tempo.

A manutenibilidade depende de fatores como:
- Legibilidade do código.
- Modularidade: A capacidade de o software ser dividido em componentes ou módulos independentes que podem ser atualizados, substituídos ou reutilizados sem afetar o restante do sistema.
- Testabilidade.
- Documentação.
- Padrões e convenções de codificação.
- Uso de tecnologias e ferramentas estáveis:

## 2.5 Eficiência
É a medida de quão efetivamente um sistema de software utiliza os recursos disponíveis, como tempo de processamento, memória, e capacidade de armazenamento, para realizar as suas tarefas. A eficiência está profundamente entrelaçada com o desempenho do software e é um critério crucial na avaliação da qualidade do sistema. 

### Divisões da eficiência:
### 2.5.1 Eficiência de Espaço
Trata da quantidade de recursos de hardware que o software utiliza durante sua execução. Um programa eficiente em termos de espaço utiliza a memória de forma otimizada, evitando desperdício, e ocupa o mínimo de espaço de armazenamento necessário.

### 2.5.2 Eficiência de Tempo
Refere-se à velocidade com que um programa executa suas operações. Um software eficiente em termos de tempo realiza suas tarefas rapidamente, minimizando a espera do usuário ou o consumo de processamento. Isso é particularmente crítico em sistemas que requerem resposta em tempo real ou que processam grandes volumes de dados.

A eficiência pode ser alcançada das seguintes formas: 
- Escolha de algoritmos apropriados.
- Otimização de código.
- Gerenciamento de recursos.
- Design modular.
- Testes e Monitoramento.

## 2.6 Segurança
Refere-se às medidas e práticas adotadas para proteger um sistema de software contra acessos não autorizados, alterações, roubo, ou destruição de informações, bem como proteção contra ataques que possam comprometer a disponibilidade, integridade e confidencialidade dos dados e dos recursos do sistema.
A importância da segurança em sistemas de software não pode ser subestimada, dada a crescente dependência da sociedade em tecnologia digital e a prevalência de ameaças cibernéticas. Uma falha de segurança pode resultar em perdas financeiras significativas, danos à reputação, perda de confiança do usuário, e em casos extremos, riscos à segurança física dos envolvidos.

### 2.6.1 Aspectos da segurança:
### 2.6.1.1 Confidencialidade
Garantir que a informação é acessível apenas por aqueles devidamente autorizados. Isso envolve a proteção de dados sensíveis contra interceptação ou visualização por partes não autorizadas.

### 2.6.1.2 Integridade
Proteger os dados e o código contra alterações não autorizadas.

### 2.6.1.3 Disponibilidade
Assegurar que os sistemas de software e os dados estejam disponíveis quando necessário pelos usuários autorizados. Isso envolve proteger o sistema contra ataques que visam interromper o serviço, como ataques de negação de serviço (DoS).

### 2.6.1.4 Autenticação e Autorização
Verificar a identidade dos usuários antes de conceder acesso ao sistema e garantir que eles tenham permissão apenas para as operações e dados apropriados para seus papéis.

### 2.6.1.5 Não Repúdio
Garantir que ações realizadas no sistema possam ser atribuídas a um usuário específico de forma incontestável, o que é importante para transações legais e auditorias.

### 2.6.2 Estratégias para garantir a segurança:
### 2.6.2.1 Desenvolvimento Seguro
Integrar considerações de segurança em todas as fases do ciclo de vida do desenvolvimento de software, desde a concepção até a manutenção, seguindo práticas como a programação defensiva.

### 2.6.2.2 Criptografia
Utilizar criptografia para proteger dados sensíveis em trânsito e em repouso, garantindo que, mesmo se interceptados, os dados não possam ser lidos ou utilizados por atacantes.

### 2.6.2.3 Testes de segurança 
Realizar testes regulares de segurança, incluindo testes de penetração e análises de vulnerabilidade, para identificar e corrigir falhas de segurança antes que possam ser exploradas.

### 2.6.2.4 Gestão de patch e atualizações 
Manter o software atualizado, aplicando patches e atualizações de segurança de forma oportuna para corrigir vulnerabilidades conhecidas.

### 2.6.2.5 Educação e Conscientização
Promover a conscientização sobre segurança entre os desenvolvedores, operadores e usuários do sistema, enfatizando a importância de práticas seguras.

## 2.7 Testabilidade
É, em resumo, a medida que define quão facilmente um sistema de software pode ser submetido a testes para validar sua funcionalidade, performance e conformidade com os requisitos especificados. Em outras palavras, a testabilidade refere-se à capacidade de um sistema ser testado de forma eficaz e eficiente
Essa qualidade é crucial, pois influencia diretamente a extensão e a facilidade com que os desenvolvedores e testadores podem identificar defeitos, realizar diagnósticos de falhas e validar as características do sistema antes de sua entrega.

### 2.7.1 Fatores que influenciam a testabilidade
### 2.7.1.1 Design modular 
Sistemas projetados com uma arquitetura modular, onde as funções estão claramente separadas e são independentes umas das outras, são mais fáceis de testar. Isso permite que testes sejam realizados isoladamente em componentes específicos sem interferência de outras partes do sistema.

### 2.7.1.2 Documentação clara
A presença de documentação detalhada, incluindo especificações de requisitos e descrições de design, facilita a criação de casos de teste que cobrem todos os aspectos esperados do software.

### 2.7.1.3 Interfaces definidas
Sistemas com interfaces bem definidas entre seus componentes permitem testes de integração mais simples, pois cada interface pode ser testada de forma independente.

### 2.7.1.4 Possibilidade de observação e controle
A capacidade de observar as saídas de um sistema em resposta a entradas definidas e controlar as condições sob as quais os testes são executados também é crucial para a testabilidade.

### 2.7.1.5 Ferramentas de suporte ao teste
A disponibilidade de ferramentas que podem automatizar a execução de testes, gerenciar casos de teste e simular condições de operação do sistema pode aumentar significativamente a testabilidade.

### 2.7.2 Benefícios da Alta Testabilidade
### 2.7.2.1 Detecção Precoce de Defeitos 
Sistemas com alta testabilidade permitem a identificação e correção de defeitos no início do ciclo de desenvolvimento, reduzindo os custos de correção.

### 2.7.2.2 Qualidade e confiabilidade
A capacidade de testar o software de forma abrangente antes da entrega contribui para a qualidade geral do produto e para a satisfação do usuário final.

### 2.7.2.3 Facilitação da manutenção
Software que é fácil de testar tende a ser mais fácil de manter, já que modificações podem ser validadas rapidamente através de testes.

### 2.7.2.4 Agilidade no desenvolvimento 
Projetos com alta testabilidade podem se adaptar mais rapidamente a mudanças nos requisitos, pois as implicações de tais mudanças podem ser validadas de forma eficiente através de testes.

## 2.8 Consistência
Consistência de código: Refere-se à uniformidade na forma como o código é escrito e organizado.Como convenções de nomenclatura, padrões de codificação e estilos de formatação. Ferramentas como linters e formatadores de código podem ajudar a aplicar e manter essa consistência automaticamente.

Consistência de Dados: No desenvolvimento de software, especialmente em aplicações que interagem com bancos de dados ou outras fontes de dados, a consistência de dados é crucial. Isso significa garantir que os dados estejam corretos, atualizados e sincronizados em diferentes partes da aplicação e entre diferentes sistemas.

Consistência de Design: Refere-se à aplicação coerente de padrões de design de software em todo o projeto. Em Java, isso pode incluir a aplicação de padrões de projeto estruturais, comportamentais e criacionais.

Nosso projeto:
- Utiliza padrões de codificação é estilo;
- Possui documentação;
- Tem arquitetura e design;
- Realiza testes;
- Possui gerenciamento de versões.

&nbsp;
### Adotar estas práticas não apenas melhorará a qualidade do software desenvolvido, mas também facilitará a colaboração dentro da equipe de desenvolvimento. É crucial que todos os membros da equipe estejam comprometidos em seguir estas diretrizes para alcançar os objetivos do projeto com eficiência e eficácia.
