# Plano de Teste - Aplicativo "Lista de Tarefas"

## Introdução
Este plano de teste garante que o aplicativo **Lista de Tarefas** atenda aos padrões de qualidade esperados, funcionando conforme os requisitos estabelecidos. O objetivo é assegurar que as funcionalidades principais operem corretamente e que o aplicativo ofereça uma experiência de usuário eficiente, mesmo em condições de alta demanda.

## Objetivos do Teste
- Verificar a funcionalidade principal do app (adicionar, editar, excluir e concluir tarefas).
- Garantir uma interface amigável e responsiva.
- Testar a compatibilidade com diferentes navegadores e dispositivos.
- Avaliar o desempenho sob diferentes condições de carga, volume de dados armazenados e acessos simultâneos.
- Certificar uma experiência positiva, estável e sem falhas.
- Identificar e corrigir problemas antes do lançamento.

## Descrição do Aplicativo
O **Lista de Tarefas** é um aplicativo web que permite aos usuários gerenciar suas atividades diárias por meio de uma interface amigável e acessível em diversos dispositivos e navegadores.

## Escopo dos Testes

### Funcionalidades a Serem Testadas

#### Funcionalidade Principal:
- Adição, edição, exclusão e conclusão de tarefas.
- Validação das interações com a interface de usuário.

#### Usabilidade:
- Verificar se a navegação é intuitiva e o design é amigável.
- Testar a experiência do usuário em diferentes dispositivos e tamanhos de tela.

#### Compatibilidade:
- Testar o funcionamento em navegadores como Google Chrome, Firefox e Microsoft Edge.
- Verificar compatibilidade em dispositivos móveis com iOS e Android.

#### Desempenho:
- Avaliar o tempo de resposta e a estabilidade do sistema.
- Realizar testes de carga, volume e estresse.

#### Segurança:
- Verificar a proteção básica dos dados do usuário.

### Funcionalidades Fora do Escopo
- Integração completa com o banco de dados e testes do backend.
- Testes avançados de segurança e penetração.

## Metodologia de Teste
- **Testes Unitários**: Validação de cada componente individualmente.
- **Testes de Integração**: Verificação do funcionamento correto das funcionalidades em conjunto.
- **Testes de Sistema**: Avaliação do sistema completo em um ambiente que simule o uso real.
- **Testes de Aceitação pelo Usuário**: Avaliação feita do ponto de vista do usuário final.
- **Testes de Desempenho**: Testes de carga, volume e estresse para avaliar o comportamento do sistema sob diferentes condições.

## Testes de Desempenho

### Teste de Carga – Quantidade de Transações
- **Objetivo**: Avaliar o desempenho do aplicativo sob alta demanda.
- **Procedimento**: Simular operações crescentes (adição, edição, exclusão de tarefas) e medir o tempo de resposta.
- **Critério de Aprovação**: O sistema deve continuar funcionando com tempos de resposta aceitáveis para até X transações por segundo.

### Teste de Volume – Quantidade de Dados Armazenados
- **Objetivo**: Avaliar o comportamento do sistema com grandes volumes de dados.
- **Procedimento**: Inserir um número progressivamente maior de tarefas (ex. 1.000, 5.000, 10.000) e medir o desempenho.
- **Critério de Aprovação**: O sistema deve armazenar até X tarefas sem perda de dados ou degradação significativa de desempenho.

### Teste de Estresse – Quantidade de Acessos Simultâneos
- **Objetivo**: Avaliar o comportamento sob grande número de acessos simultâneos.
- **Procedimento**: Simular múltiplos usuários interagindo com o sistema ao mesmo tempo.
- **Critério de Aprovação**: O sistema deve permanecer estável e responsivo.

## Critérios de Aprovação e Reprovação

### Aprovação:
- O sistema será aprovado se todas as funcionalidades principais forem verificadas e funcionarem conforme esperado, sem problemas críticos, e se passar nos testes de desempenho.

### Reprovação:
- O sistema será reprovado se forem detectados problemas críticos, perda de dados, falhas de segurança ou não atender aos requisitos de desempenho, usabilidade e funcionalidade.

## Procedimentos

### Pausa dos Testes
Os testes poderão ser pausados se:
- Erros críticos comprometerem a execução dos testes.
- Ferramentas ou ambientes necessários não estiverem disponíveis.
- Houver necessidade de ajuste dos requisitos.

## Entregas
- **Casos de Teste**: Documentação dos cenários de teste.
- **Scripts de Teste**: Automatização de cenários repetitivos ou complexos.
- **Logs de Resultados**: Registro detalhado dos testes.
- **Relatórios de Bugs**: Detalhamento dos erros encontrados.
- **Relatório Final de Teste**: Resumo dos resultados e análise da qualidade.

## Responsabilidades
- **Líder de Teste**: Lucas – Coordenação geral do processo de teste.
- **Equipe de Teste (QA)**: Testadores encarregados da execução e documentação.
- **Desenvolvedores**: Responsáveis pela correção de bugs e implementação de melhorias.

## Cronograma
- Planejamento dos Testes: 2 dias.
- Criação dos Casos de Teste: 2 dias.
- Execução dos Testes: 3 dias.
- Correção de Bugs: 3 dias.
- Teste de Regressão: 2 dias.
- Revisão e Relatório Final: 1 dia.

## Riscos e Planos de Mitigação

### Possíveis Riscos:
- Atrasos na configuração do ambiente.
- Problemas de compatibilidade.
- Defeitos críticos descobertos tarde.
- Recursos limitados para testes em diferentes plataformas.

### Planos de Contingência:
- Utilizar navegadores/dispositivos alternativos.
- Ajustar cronograma conforme necessário.
- Priorizar a correção de problemas críticos.

## Aprovações
Este plano de teste foi revisado e aprovado pelos responsáveis:
- **Lucas**
- **Fellipe Zapelini**
- **Arthur Ivaza**
