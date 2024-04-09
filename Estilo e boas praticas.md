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

## 2.3 Manutenibilidade:
É, basicamente, uma medida de quão fácil é manter e evoluir um sistema de software ao longo do tempo.

Nosso projeto:
- Está limpo e legível; 
- Contém documentação;
- Segue o padrão de design OO;
- Usa Git para versionamento;
- Utiliza testes (JUnit).

## 2.4 Eficiência
Trata-se de diretrizes e principios que otimizam o algoritmo.

Nosso projeto:
- Otimiza consultas do banco de dados;
- Evita a criação desnecessária de objetos;
- Evita loops desnecessários;
- Usa a arquitetura API REST.

## 2.5 Segurança
Envolve a aplicação de medidas de segurança em todas as fases do ciclo de vida do desenvolvimento de software, desde a concepção até a manutenção, para prevenir, detectar e corrigir falhas de segurança.

Nosso projeto:
- Realiza testes de penetração e análise de vulnerabilidades regularmente para identificar e corrigir potenciais falhas de segurança em sua API.
- Implementa um manejo de erros consistente que não revela detalhes internos da implementação ou informações sensíveis.
- Segue práticas recomendadas de codificação segura, como validação de entrada, sanitização de dados (remove ou neutraliza qualquer dado que possa ser perigoso ou malicioso) e uso de APIs seguras.

Identificar a presença de segurança em um código de projeto é um processo constante que necessita de vigilância e adaptação as novas ameaças. Integrar a segurança desde o início do desenvolvimento e mantê-la como uma preocupação constante ao longo do ciclo de vida do projeto para criar um código seguro.

## 2.6 Testabilidade
Quando falamos sobre testabilidade no mundo do desenvolvimento de software, estamos basicamente nos referindo à quão amigável nosso sistema ou componente é para ser testado e o nosso design facilita a realização de testes que validam se tudo está funcionando como deveria. A testabilidade é influenciada por um monte de coisas – desde a clareza com que definimos o que queremos que nosso software faça, até como organizamos seu código em módulos que podem ser facilmente examinados individualmente.

No nosso projeto, levamos a testabilidade a sério desde o início. Não a vemos apenas como uma caixa que precisa ser marcada, mas como uma parte vital da criação de um software realmente robusto e confiável. Aqui está o que fazemos para garantir que nosso software seja tão testável quanto possível:
- Testes Unitários: cada unidade de código recebe atenção individual para garantir que está em forma e funcionando como deveria. 
- JUnit para Automatizar Testes: o JUnit é basicamente o assistente dos testes unitários. Ele ajuda a automatizar esses testes, o que significa que podemos rodá-los rapidamente e com frequência, sem ter que fazer tudo manualmente.

## 2.7 Consistência
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
