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
# Aspectos:
## 2. Legibilidade:
É a facilidade com que um código pode ser lido e compreendido por outros programadores (ou até mesmo por você mesmo, no futuro).
Ela pode ser influenciada por fatores como nomes expressivos e descritivos para variáveis, funções e classes que sigam um padrão. Tais padrões sendo PascalCase para classes e interfaces, camelCase para variáveis e métodos e o UPPER_SNAKE_CASE para constantes.

Nosso projeto, neste aspecto, utiliza os padrões citados acima: 
- PascalCase: classes e interfaces.
- camelCase: variáveis e métodos.
- UPPER_SNAKE_CASE: para constantes.

## 3 Estrutura e formatação:
É a maneira como o código é organizado e apresentado visualmente. Esses é um elemento que influencia diretamente a legibilidade do código.
Juntos, a estrutura e a formatação do código desempenham um papel crucial na manutenção da qualidade do software. Códigos bem estruturados e formatados não são apenas mais agradáveis de ler e trabalhar, mas também facilitam a detecção de erros, a revisão de código por pares e a incorporação de novos desenvolvedores ao projeto.

### 3.1 Estrutura:
Diz respeito à sua organização lógica e arquitetônica. Isso inclui a maneira como as classes, funções, módulos e outros componentes são organizados, bem como a relação entre eles.
Alguns elementos estruturais são:
- Modularização: Dividir o código em módulos ou componentes com responsabilidades claras e bem definidas.
- Hierarquia e Herança: Organizar classes e objetos de maneira hierárquica para promover a reutilização de código.
- Padrões de Projeto: Aplicar padrões de projeto reconhecidos para resolver problemas comuns de design de software de maneira eficaz.

### 3.2 Formatação:
Trata da apresentação visual do código, incluindo aspectos como indentação, uso de espaços e linhas em branco, e convenções de nomenclatura. Embora possa parecer trivial à primeira vista, a formatação consistente e intuitiva torna o código mais acessível e fácil de ler.
Alguns elementos da formatação são:
- Indentação: Usar espaços ou tabs para criar uma hierarquia visual, facilitando a identificação de blocos de código, como corpos de funções, loops e condicionais.
- Espaçamento: Utilizar espaços em branco adequadamente, como entre operadores e operandos, para tornar o código mais claro.
- Linhas em Branco: Inserir linhas em branco entre declarações ou blocos de código para separar visualmente componentes lógicos distintos.
- Convenções de Nomenclatura: Seguir um conjunto consistente de regras para a nomenclatura de variáveis, funções, classes e outros identificadores, como camelCase ou snake_case.

## 4 Princípios de Programação:
São diretrizes fundamentais que orientam os desenvolvedores na criação de software.
Eles servem como um conjunto de melhores práticas acumuladas ao longo dos anos pela comunidade de desenvolvimento de software. Adotar esses princípios pode levar a um código de maior qualidade e a projetos de software mais bem-sucedidos. 

### Alguns princípios famosos:
### 4.1 DRY (Don't Repeat Yourself)
Este princípio enfatiza a importância de evitar a repetição de código. A ideia é que cada peça de informação deve ter uma representação única, não ambígua e definitiva dentro do sistema. Seguir o princípio DRY pode reduzir a quantidade de código redundante, facilitando a manutenção e a atualização do software.

### 4.2 KISS (Keep It Simple, Stupid)
O princípio KISS sugere que a simplicidade deve ser uma meta-chave no design de software, e que se deve evitar a complexidade desnecessária. Isso não significa que todo software deve ser simples, mas que os desenvolvedores devem procurar a solução mais simples que resolva o problema efetivamente.

### 4.3 YAGNI (You Ain't Gonna Need It)
Originário da programação extrema (XP), esse princípio aconselha os desenvolvedores a não adicionar funcionalidades até que elas sejam realmente necessárias. Isso evita gastar tempo e recursos em partes do software que podem nunca ser usadas ou que adicionam complexidade desnecessária ao projeto.

### 4.4 Encapsulamento
Encapsulamento é a prática de ocultar os detalhes internos do funcionamento de uma classe e expor apenas o necessário para o mundo exterior. Isso protege os dados internos da classe e é fundamental para a abstração.

### 4.5 Separation of Concerns (Separação de Preocupações)
Este princípio defende que um software deve ser dividido em seções distintas, onde cada seção aborda uma preocupação específica. Isso facilita a manutenção e a atualização do software, além de tornar o código mais fácil de entender.

## 5. Manutenibilidade:
É, basicamente, a medida de quão fácil é manter, modificar, corrigir, ou estender um sistema ou aplicação ao longo do tempo, um software com alta manutenibilidade é aquele que pode ser atualizado ou adaptado com esforço mínimo.
A essa dedicação à manutenibilidade garante que nosso projeto possa suportar mudanças, melhorias e atualizações, e, assim, evoluir com o passar do tempo.

A manutenibilidade depende de fatores como:
- Legibilidade do código.
- Modularidade: A capacidade de o software ser dividido em componentes ou módulos independentes que podem ser atualizados, substituídos ou reutilizados sem afetar o restante do sistema.
- Testabilidade.
- Documentação.
- Padrões e convenções de codificação.
- Uso de tecnologias e ferramentas estáveis:

## 6. Eficiência
É a medida de quão efetivamente um sistema de software utiliza os recursos disponíveis, como tempo de processamento, memória, e capacidade de armazenamento, para realizar as suas tarefas. A eficiência está profundamente entrelaçada com o desempenho do software e é um critério crucial na avaliação da qualidade do sistema. 

### Divisões da eficiência:
### 6.1 Eficiência de Espaço
Trata da quantidade de recursos de hardware que o software utiliza durante sua execução. Um programa eficiente em termos de espaço utiliza a memória de forma otimizada, evitando desperdício, e ocupa o mínimo de espaço de armazenamento necessário.

### 6.2 Eficiência de Tempo
Refere-se à velocidade com que um programa executa suas operações. Um software eficiente em termos de tempo realiza suas tarefas rapidamente, minimizando a espera do usuário ou o consumo de processamento. Isso é particularmente crítico em sistemas que requerem resposta em tempo real ou que processam grandes volumes de dados.

A eficiência pode ser alcançada das seguintes formas: 
- Escolha de algoritmos apropriados.
- Otimização de código.
- Gerenciamento de recursos.
- Design modular.
- Testes e Monitoramento.

## 7. Segurança
Refere-se às medidas e práticas adotadas para proteger um sistema de software contra acessos não autorizados, alterações, roubo, ou destruição de informações, bem como proteção contra ataques que possam comprometer a disponibilidade, integridade e confidencialidade dos dados e dos recursos do sistema.
A importância da segurança em sistemas de software não pode ser subestimada, dada a crescente dependência da sociedade em tecnologia digital e a prevalência de ameaças cibernéticas. Uma falha de segurança pode resultar em perdas financeiras significativas, danos à reputação, perda de confiança do usuário, e em casos extremos, riscos à segurança física dos envolvidos.

### 7.1 Aspectos da segurança:
### 7.1.1 Confidencialidade
Garantir que a informação é acessível apenas por aqueles devidamente autorizados. Isso envolve a proteção de dados sensíveis contra interceptação ou visualização por partes não autorizadas.

### 7.1.2 Integridade
Proteger os dados e o código contra alterações não autorizadas.

### 7.1.3 Disponibilidade
Assegurar que os sistemas de software e os dados estejam disponíveis quando necessário pelos usuários autorizados. Isso envolve proteger o sistema contra ataques que visam interromper o serviço, como ataques de negação de serviço (DoS).

### 7.1.4 Autenticação e Autorização
Verificar a identidade dos usuários antes de conceder acesso ao sistema e garantir que eles tenham permissão apenas para as operações e dados apropriados para seus papéis.

### 7.1.5 Não Repúdio
Garantir que ações realizadas no sistema possam ser atribuídas a um usuário específico de forma incontestável, o que é importante para transações legais e auditorias.

&nbsp;
### 7.2 Estratégias para garantir a segurança:
### 7.2.1 Desenvolvimento Seguro
Integrar considerações de segurança em todas as fases do ciclo de vida do desenvolvimento de software, desde a concepção até a manutenção, seguindo práticas como a programação defensiva.

### 7.2.2 Criptografia
Utilizar criptografia para proteger dados sensíveis em trânsito e em repouso, garantindo que, mesmo se interceptados, os dados não possam ser lidos ou utilizados por atacantes.

### 7.2.3 Testes de segurança 
Realizar testes regulares de segurança, incluindo testes de penetração e análises de vulnerabilidade, para identificar e corrigir falhas de segurança antes que possam ser exploradas.

### 7.2.4 Gestão de patch e atualizações 
Manter o software atualizado, aplicando patches e atualizações de segurança de forma oportuna para corrigir vulnerabilidades conhecidas.

### 7.2.5 Educação e Conscientização
Promover a conscientização sobre segurança entre os desenvolvedores, operadores e usuários do sistema, enfatizando a importância de práticas seguras.

## 8. Testabilidade
É, em resumo, a medida que define quão facilmente um sistema de software pode ser submetido a testes para validar sua funcionalidade, performance e conformidade com os requisitos especificados. Em outras palavras, a testabilidade refere-se à capacidade de um sistema ser testado de forma eficaz e eficiente
Essa qualidade é crucial, pois influencia diretamente a extensão e a facilidade com que os desenvolvedores e testadores podem identificar defeitos, realizar diagnósticos de falhas e validar as características do sistema antes de sua entrega.

### 8.1 Fatores que influenciam a testabilidade
### 8.1.1 Design modular 
Sistemas projetados com uma arquitetura modular, onde as funções estão claramente separadas e são independentes umas das outras, são mais fáceis de testar. Isso permite que testes sejam realizados isoladamente em componentes específicos sem interferência de outras partes do sistema.

### 8.1.2 Documentação clara
A presença de documentação detalhada, incluindo especificações de requisitos e descrições de design, facilita a criação de casos de teste que cobrem todos os aspectos esperados do software.

### 8.1.3 Interfaces definidas
Sistemas com interfaces bem definidas entre seus componentes permitem testes de integração mais simples, pois cada interface pode ser testada de forma independente.

### 8.1.4 Possibilidade de observação e controle
A capacidade de observar as saídas de um sistema em resposta a entradas definidas e controlar as condições sob as quais os testes são executados também é crucial para a testabilidade.

### 8.1.5 Ferramentas de suporte ao teste
A disponibilidade de ferramentas que podem automatizar a execução de testes, gerenciar casos de teste e simular condições de operação do sistema pode aumentar significativamente a testabilidade.

&nbsp;
### 8.2 Benefícios da Alta Testabilidade
### 8.2.1 Detecção Precoce de Defeitos 
Sistemas com alta testabilidade permitem a identificação e correção de defeitos no início do ciclo de desenvolvimento, reduzindo os custos de correção.

### 8.2.2 Qualidade e confiabilidade
A capacidade de testar o software de forma abrangente antes da entrega contribui para a qualidade geral do produto e para a satisfação do usuário final.

### 8.2.3 Facilitação da manutenção
Software que é fácil de testar tende a ser mais fácil de manter, já que modificações podem ser validadas rapidamente através de testes.

### 8.2.4 Agilidade no desenvolvimento 
Projetos com alta testabilidade podem se adaptar mais rapidamente a mudanças nos requisitos, pois as implicações de tais mudanças podem ser validadas de forma eficiente através de testes.

## 9. Consistência
Refere-se à uniformidade na aplicação de princípios de design, padrões de codificação, convenções de nomenclatura, interfaces de usuário e outras práticas de desenvolvimento em todo o projeto ou sistema.
A consistência é crucial para garantir que o software seja intuitivo, manutenível e escalável. Ela afeta vários aspectos do desenvolvimento de software e da experiência do usuário final.

### 9.1 Aplicações da consistência:
### 9.1.1 Consistência no design de interface
Refere-se à uniformidade na aparência e no comportamento das interfaces de usuário. Isso inclui o uso consistente de cores, tipografia, elementos gráficos, terminologia e mecanismos de interação. A consistência na interface do usuário ajuda os usuários a aprender e a se adaptar ao software mais rapidamente, melhorando a experiência do usuário.

### 9.1.2 Consistência no código
Envolve seguir padrões de codificação uniformes, convenções de nomenclatura e estilos de formatação em todo o código fonte. Isso facilita a leitura, compreensão e manutenção do código por diferentes desenvolvedores, além de ajudar a prevenir erros.

### 9.1.3 Consistência em padrões de design
A aplicação consistente de padrões de design em todo o projeto ajuda a resolver problemas comuns de maneira uniforme. Isso não apenas melhora a qualidade do design do software, mas também facilita a comunicação entre os membros da equipe, já que todos têm um entendimento comum das soluções implementadas.

### 9.1.4 Consistência na documentação
Manter um estilo e formato consistentes na documentação técnica, incluindo comentários no código, manuais de usuário e documentos de especificação, facilita a compreensão e a utilização das informações fornecidas.

### 9.1.5 Consistência em testes
Aplicar uma abordagem consistente para a criação de testes e critérios de aceitação garante que todos os componentes do sistema sejam verificados de forma abrangente e uniforme, aumentando a confiabilidade do software.

&nbsp;
### 9.2 Benefícios da consistência:
### 9.2.1 Melhora a colaboração
A consistência facilita a colaboração entre os membros da equipe, pois todos seguem as mesmas diretrizes e padrões.

### 9.2.2 Aumenta a eficiência 
Reduz o tempo necessário para entender diferentes partes do sistema, permitindo que os desenvolvedores e designers se concentrem em solucionar problemas em vez de decifrar estilos inconsistentes.

### 9.2.3 Facilita a manutenção 
Software consistente é mais fácil de manter e atualizar, pois as alterações em um componente podem ser aplicadas de maneira previsível a outros componentes similares.

### 9.2.4 Melhora a qualidade do produto
Ao garantir que o software seja desenvolvido de maneira uniforme e de acordo com as melhores práticas, a consistência contribui para a qualidade geral e a estabilidade do produto.

## 10. Performance e Otimização
Referem-se ao processo de melhorar a eficiência de um sistema de software, garantindo que ele execute suas funções da maneira mais eficaz possível, usando o mínimo de recursos como tempo de processamento, memória e largura de banda. 
Essa área é fundamental porque afeta diretamente a experiência do usuário, os custos operacionais e a capacidade do software de escalar para atender a demandas crescentes.

### 10.1 Estratégias de otimização:
### 10.1.1 Análise de Performance 
Envolve o uso de ferramentas e técnicas para monitorar e analisar o comportamento do sistema sob diferentes condições de carga para identificar gargalos de performance.

### 10.1.2 Otimização de algoritmos 
Escolher ou projetar algoritmos que reduzam a complexidade computacional das operações críticas, melhorando o tempo de resposta e a eficiência do processamento.

### 10.1.3 Gerenciamento de memória 
Implementar técnicas para usar a memória de forma mais eficiente, incluindo a otimização do uso de cache, a minimização do overhead de memória e a eliminação de vazamentos de memória.

### 10.1.4 Concorrência e paralelismo 
Aproveitar sistemas de múltiplos núcleos ou distribuídos para executar tarefas em paralelo, aumentando a throughput (vazão) e reduzindo o tempo de processamento para tarefas intensivas.

### 10.1.5 Otimização de banco de dados
Inclui a normalização de dados, indexação eficiente, e a otimização de consultas para melhorar a velocidade de acesso e manipulação de dados.

### 10.1.6 Minimização de recursos de rede 
Reduzir o tamanho dos dados transmitidos, utilizar técnicas de compressão e otimizar os protocolos de comunicação para diminuir a latência e o uso de largura de banda.

&nbsp;
### 10.2 Desafios na Otimização
### 10.2.1 Compromissos 
Otimizar um aspecto do sistema pode afetar negativamente outro. Por exemplo, aumentar a performance pode resultar em maior consumo de memória. É crucial encontrar um equilíbrio adequado entre diferentes recursos.

### 10.2.2 Evolução do sistema 
À medida que o sistema evolui, novos recursos e mudanças podem afetar a performance. A otimização é um processo contínuo que deve acompanhar o desenvolvimento do software.

### 10.2.3 Variedade de ambientes de execução 
O software pode ser executado em uma ampla gama de hardware e redes, cada um com suas próprias características de performance. As otimizações devem considerar essa diversidade.

## 11. Qualidade do Código
Na engenharia de software, a qualidade do código é uma métrica que avalia o quão bem o código-fonte de um software atende a certos critérios estabelecidos que geralmente incluem aspectos como legibilidade, manutenibilidade, eficiência, testabilidade, entre outros.
Ou seja, a qualidade do código é resultado final de todos os aspetos já citados.

### 11.1 Estratégias para melhorar a qualidade do código
- Revisão de código.
- Refatoração.
- Testes automatizados.
- Documentação.


### Adotar estas práticas não apenas melhorará a qualidade do software desenvolvido, mas também facilitará a colaboração dentro da equipe de desenvolvimento. É crucial que todos os membros da equipe estejam comprometidos em seguir estas diretrizes para alcançar os objetivos do projeto com eficiência e eficácia.

&nbsp;
# Team City
## O que é?
TeamCity é uma plataforma de integração contínua (CI) e entrega contínua (CD) desenvolvida pela JetBrains. A ferramenta automatiza o processo de construção de código (build), teste e deploy, facilitando a detecção precoce de problemas.
Essa ferramenta é de suma importancia pois automatiza o processo de build e teste, por tal razão utilizaremos ela para testar o peojwto SprintCampus.

## Primeiros passos
