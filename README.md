# Plataforma Web para Automação da Análise Sensorial de Alimentos

   [![Área](https://img.shields.io/badge/Análise%20de%20Dados-2F80ED?style=for-the-badge)](https://github.com/jcesarmph-ui/DataAnalytics)
    [![Aplicação](https://img.shields.io/badge/Plataforma%20Web-6C63FF?style=for-the-badge)](https://github.com/jcesarmph-ui/DataAnalytics)
   [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000)](https://developer.mozilla.org/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=FFFFFF)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=FFFFFF)](https://developer.mozilla.org/docs/Web/CSS)
[![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=FFFFFF)](https://supabase.com/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=FFFFFF)](https://vercel.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=FFFFFF)](https://github.com/)

## Visão geral

Trabalho de Conclusão de Curso avaliado com nota máxima que documenta o desenvolvimento de uma plataforma web para automatizar processos de análise sensorial de produtos alimentícios.

A proposta consiste em reunir, em um único ambiente digital, etapas que tradicionalmente podem exigir formulários, planilhas, cálculos estatísticos e tratamento manual de resultados. A plataforma foi concebida para organizar os experimentos, padronizar procedimentos, facilitar a coleta de respostas e automatizar o processamento dos dados.

O trabalho relaciona desenvolvimento web, automação de processos, estatística aplicada e análise de dados, demonstrando como ferramentas digitais podem contribuir para a eficiência de atividades experimentais.

**Documento principal:** [Acessar o artigo completo em PDF](plataforma-web-analise-sensorial-alimentos.pdf)

## Objetivos

O objetivo principal foi desenvolver uma plataforma web capaz de automatizar e centralizar as etapas de realização de análises sensoriais de alimentos.

Entre os objetivos específicos, destacam-se:

- Digitalizar e organizar a criação de análises sensoriais.
- Facilitar a configuração dos métodos de teste.
- Automatizar o balanceamento e a identificação das amostras.
- Disponibilizar formulários digitais para os participantes.
- Coletar e armazenar as respostas de maneira estruturada.
- Processar os dados obtidos nos experimentos.
- Gerar resultados e relatórios automaticamente.
- Reduzir tarefas manuais e o tempo necessário para executar os procedimentos.
- Comparar os resultados da plataforma com métodos convencionais.
- Avaliar a usabilidade e a viabilidade econômica da solução.

## Problema abordado

A análise sensorial é utilizada para avaliar características de produtos por meio das percepções humanas. Em alimentos, pode auxiliar na comparação de formulações, na identificação de diferenças entre amostras e na avaliação de características sensoriais.

Entretanto, a execução dessas análises pode envolver diversas atividades manuais, como organização dos testes, balanceamento das amostras, aplicação de questionários, tabulação das respostas, realização de cálculos e elaboração de relatórios.

Quando essas etapas são executadas com ferramentas desconectadas, o processo pode se tornar mais demorado e sujeito a erros de transcrição, inconsistências e retrabalho.

A plataforma apresentada no artigo busca solucionar esse problema por meio da integração das principais etapas em um sistema web.

## Solução proposta

A solução consiste em uma aplicação web que centraliza o fluxo de trabalho da análise sensorial, desde a configuração do experimento até a apresentação dos resultados.

### Fluxo geral de funcionamento

1. **Criação da análise:** configuração do experimento e dos parâmetros necessários.
2. **Definição do teste:** seleção e configuração do método de análise sensorial.
3. **Organização das amostras:** realização do balanceamento e preparação das identificações.
4. **Coleta de respostas:** disponibilização da interface digital para os participantes.
5. **Armazenamento:** organização das respostas coletadas.
6. **Processamento dos dados:** execução dos procedimentos de análise previstos no sistema.
7. **Apresentação dos resultados:** disponibilização dos resultados processados.
8. **Geração de relatórios:** consolidação das informações obtidas no experimento.

Esse fluxo reduz a necessidade de transferir manualmente informações entre diferentes ferramentas e favorece a padronização das atividades.

## Funcionalidades abordadas

Com base na descrição do artigo, a plataforma contempla funcionalidades relacionadas a:

- Criação e configuração de análises sensoriais.
- Organização e balanceamento de amostras.
- Identificação das amostras utilizadas nos testes.
- Coleta digital de respostas dos participantes.
- Armazenamento estruturado das informações.
- Processamento automatizado dos dados.
- Aplicação de procedimentos estatísticos associados aos testes.
- Apresentação dos resultados.
- Geração de relatórios.
- Comparação dos resultados com métodos convencionais.

O artigo também descreve testes envolvendo diferentes modalidades de análise sensorial. Para conhecer os detalhes de cada método e das respectivas telas, consulte o PDF disponibilizado nesta pasta.

## Tecnologias utilizadas

O artigo descreve uma aplicação web organizada em componentes de frontend, backend e banco de dados, com utilização de ferramentas como GitHub, Vercel e Supabase.

### Frontend

**HTML5, CSS3 e JavaScript**

Tecnologias associadas à construção de interfaces web, à organização visual das páginas e à implementação de interações no navegador.

- **HTML5:** estruturação do conteúdo das páginas.
- **CSS3:** apresentação visual e estilização da interface.
- **JavaScript:** implementação de comportamentos e interações da aplicação.

### Backend e banco de dados

**Supabase**

Plataforma utilizada no desenvolvimento da solução para dar suporte aos recursos de backend e banco de dados. Sua função específica na arquitetura deve ser compreendida em conjunto com a implementação descrita no artigo.

### Hospedagem e publicação

**Vercel**

Plataforma de publicação e hospedagem de aplicações web, utilizada no contexto do desenvolvimento apresentado.

### Versionamento e documentação

**GitHub**

Serviço utilizado para hospedar repositórios, organizar arquivos do projeto e apoiar o controle de versões e a colaboração no desenvolvimento de software.

> Os badges identificam as tecnologias e ferramentas mencionadas no trabalho. A descrição detalhada de sua implementação deve ser consultada no artigo original.

## Arquitetura geral

De forma conceitual, a aplicação pode ser compreendida por meio dos seguintes componentes:

```text
Usuário
   |
   v
Interface Web
HTML + CSS + JavaScript
   |
   v
Recursos da Aplicação
Configuração dos testes
Organização das amostras
Coleta de respostas
Processamento dos dados
Geração de relatórios
   |
   v
Backend e Banco de Dados
Supabase
   |
   v
Armazenamento e consulta das informações
```

A publicação da aplicação está associada à utilização da Vercel, enquanto o GitHub oferece suporte à organização e ao versionamento dos arquivos.

O esquema representa uma visão conceitual do sistema, e não um diagrama técnico completo de todos os componentes internos.

## Validação e resultados

Foram realizados testes práticos para verificar o funcionamento da plataforma e comparar os resultados com métodos convencionais utilizados em ambiente acadêmico.

Os resultados apresentados indicaram que:

- A plataforma reproduziu corretamente os resultados obtidos pelos métodos de comparação utilizados nos testes descritos.
- A criação de uma análise por um usuário sem experiência prévia ocorreu em aproximadamente dois minutos no cenário apresentado.
- Foram realizados testes de usabilidade com a participação de 26 voluntários.
- Os participantes demonstraram aceitação da ferramenta e indicaram interesse em utilizá-la em atividades práticas de análise sensorial.
- Houve redução do tempo necessário para executar etapas como balanceamento, tabulação e geração de relatórios.

### Redução do tempo de execução

No cenário comparativo apresentado no artigo, o tempo total passou de 3 horas e 50 minutos para 2 horas e 5 minutos.

| Indicador | Resultado |
|---|---:|
| Tempo pelo método de comparação | 3 h 50 min |
| Tempo com a plataforma | 2 h 05 min |
| Tempo economizado | 1 h 45 min |
| Redução percentual reportada | 45,65% |

Esses valores correspondem ao cenário experimental descrito pelos autores e não representam uma garantia de desempenho em qualquer contexto de utilização.

## Viabilidade econômica

O trabalho também contempla uma análise de viabilidade econômica, considerando estimativas de mão de obra, despesas operacionais, investimento inicial e projeções financeiras.

Essa análise busca avaliar o potencial de aplicação da plataforma em contextos acadêmicos e profissionais.

Os valores e indicadores econômicos devem ser interpretados conforme as premissas utilizadas no estudo. Para consultar as tabelas e os cálculos completos, utilize o artigo original em PDF.

## Relação com Engenharia de Controle e Automação

O projeto apresenta relação com a Engenharia de Controle e Automação por meio da análise e melhoria de processos, da padronização de procedimentos e da automação de tarefas repetitivas.

Embora a solução seja baseada em software e não dependa de equipamentos físicos para representar seu fluxo principal, seus conceitos estão associados a competências importantes da engenharia, como:

- Mapeamento e organização de processos.
- Identificação de atividades manuais e oportunidades de melhoria.
- Automação de etapas operacionais.
- Padronização de procedimentos.
- Redução de retrabalho.
- Avaliação de desempenho e eficiência.
- Validação de uma solução por meio de testes.

A plataforma demonstra como princípios de automação podem ser aplicados a processos experimentais e administrativos por meio de tecnologias digitais.

## Relação com Ciência de Dados

A solução também se relaciona com Ciência de Dados, principalmente nas etapas de coleta, armazenamento, organização e processamento das respostas obtidas nos experimentos.

O fluxo de trabalho envolve:

- Entrada de dados por meio de formulários.
- Estruturação e armazenamento das informações.
- Processamento dos dados coletados.
- Aplicação de métodos estatísticos relacionados aos testes.
- Consolidação e apresentação dos resultados.
- Geração de relatórios para apoiar a interpretação das informações.

Essas atividades demonstram a importância da qualidade dos dados, da padronização dos procedimentos e da automação do processamento para a obtenção de resultados consistentes.

## Aplicações potenciais

A proposta possui potencial de utilização em diferentes contextos, conforme as necessidades de cada organização:

- Instituições de ensino e laboratórios acadêmicos.
- Atividades práticas de análise sensorial.
- Estudos comparativos de produtos alimentícios.
- Pesquisas relacionadas ao desenvolvimento de produtos.
- Ambientes profissionais que realizam avaliações sensoriais.
- Processos experimentais que necessitam de coleta estruturada e processamento de respostas.

A adequação a cada contexto depende dos requisitos técnicos, dos métodos de análise utilizados e das condições de implantação.

**Categoria:** Engenharia de Controle e Automação · Desenvolvimento Web · Automação de Processos · Análise de Dados · Análise Sensorial
