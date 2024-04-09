<div style="text-align: justify;">

# Orientações sobre estilo e boas práticas de codificação Java
### Este documento destina-se a estabelecer um conjunto de padrões de estilo e boas práticas de codificação em Java, visando promover a qualidade, a manutenção e a escalabilidade em projetos de engenharia de software. O cumprimento destas diretrizes ajudará a equipe a desenvolver um código consistente, legível e eficiente.
&nbsp;

# 1. Entendendo estilo e boas práticas
## 1.1 O que são?
São um conjunto de diretrizes e convenções que os programadores seguem para tornar seus códigos mais legíveis, manuteníveis e eficientes.

## 1.2 Para que servem?
Tais práticas não apenas ajudam a prevenir erros, mas também facilitam a colaboração entre desenvolvedores ao padronizar a maneira como o código é escrito.
&nbsp;
&nbsp;

# 2. Aspectos:
## 2.1 Legibilidade:
Consiste em ter nomes expressivos, que, por exemplo, mostram com clareza o que uma variável armazena. Ou métodos com nomes de fácil compreenção.

Nosso projeto, neste aspecto, utiliza o padrão Carmel Case que consiste em: 
- Inicia nomes de classes e interfaces com letra maiúscula;
- Inicia nomes de variáveis e métodos com letras minúsculas e, se for um nome composto, iniciar a segunda palavra com letra minúscula sem dar espaço;
- Escreve constantes com todas letras maiúsculas e palavras separadas po underline (_). 

## 2.2 Manutenibilidade:
É, basicamente, uma medida de quão fácil é manter e evoluir um sistema de software ao longo do tempo.

Nosso projeto:
- Está limpo e legível; 
- Contém documentação;
- Segue o padrão de design OO;
- Usa Git para versionamento;
- Utiliza testes (JUnit).

## 2.3 Eficiência
Trata-se de diretrizes e principios que otimizam o algoritmo.

Nosso projeto:
- Otimiza consultas do banco de dados;
- Evita a criação desnecessária de objetos;
- Evita loops desnecessários;
- Usa a arquitetura API REST.

## 2.4 Segurança
Envolve a aplicação de medidas de segurança em todas as fases do ciclo de vida do desenvolvimento de software, desde a concepção até a manutenção, para prevenir, detectar e corrigir falhas de segurança.

Nosso projeto:
- Realiza testes de penetração e análise de vulnerabilidades regularmente para identificar e corrigir potenciais falhas de segurança em sua API.
- Implementa um manejo de erros consistente que não revela detalhes internos da implementação ou informações sensíveis.
- Segue práticas recomendadas de codificação segura, como validação de entrada, sanitização de dados (remove ou neutraliza qualquer dado que possa ser perigoso ou malicioso) e uso de APIs seguras.

Identificar a presença de segurança em um código de projeto é um processo constante que necessita de vigilância e adaptação as novas ameaças. Integrar a segurança desde o início do desenvolvimento e mantê-la como uma preocupação constante ao longo do ciclo de vida do projeto para criar um código seguro.

## 2.5 Testabilidade
É a capacidade de um sistema ou componente de software ser facilmente testado. Isso significa que o design do software suporta a execução de testes para validar sua funcionalidade, ele suporta ser testado.

Nosso projeto:
- Faz testes unitários;
- Utiliza JUnit para aitomatizar testes

## 2.6 Consistência
Consistência de código: Refere-se à uniformidade na forma como o código é escrito e organizado.Como convenções de nomenclatura, padrões de codificação e estilos de formatação. Ferramentas como linters e formatadores de código podem ajudar a aplicar e manter essa consistência automaticamente.

Consistência de Dados: No desenvolvimento de software, especialmente em aplicações que interagem com bancos de dados ou outras fontes de dados, a consistência de dados é crucial. Isso significa garantir que os dados estejam corretos, atualizados e sincronizados em diferentes partes da aplicação e entre diferentes sistemas.

Consistência de Design: Refere-se à aplicação coerente de padrões de design de software em todo o projeto. Em Java, isso pode incluir a aplicação de padrões de projeto estruturais, comportamentais e criacionais.

Nosso projeto:
- Utiliza padrões de codificação é estilo;
- Possui documentação;
- Tem arquitetura e design;
- Realiza testes;
- Possui gerenciamento de versões.

</div>
