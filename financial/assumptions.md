# Hipóteses a validar

Este é o registro inicial de hipóteses do Projeto Horizonte. Nenhum item abaixo é fato ou compromisso. Cada hipótese deverá receber identificador, responsável, evidência, data, resultado e decisão no ciclo de modelagem.

## Hipóteses de problema e público

| ID | Hipótese | Como testar | Critério de decisão ainda necessário |
|---|---|---|---|
| H-P01 | Há desigualdade relevante de exposição profissional entre estudantes | revisão de evidências, pesquisa amostral prévia e entrevistas | instrumento, amostra e diferença material |
| H-P02 | A restrição de repertório influencia decisões educacionais | literatura e análise longitudinal | resultado primário e janela |
| H-P03 | 9º ano e ensino médio são os momentos prioritários | escuta, literatura e dados de transição | segmentação por idade/série |
| H-P04 | O IPDP melhora a focalização sem estigmatizar territórios | validação técnica, consulta pública e análise de sensibilidade | variáveis, pesos e salvaguardas |

## Hipóteses pedagógicas e de experiência

| ID | Hipótese | Situação | Evidência necessária |
|---|---|---|---|
| H-E01 | Experiências práticas breves despertam curiosidade mensurável | Premissa a validar | teste de protótipo e medida antes/depois |
| H-E02 | A experiência tem duração suficiente para ser significativa | duração `TBD` | teste com jovens e educadores |
| H-E03 | O número ideal de estações permite variedade sem superficialidade | quantidade `TBD` | simulação de fluxo e piloto |
| H-E04 | Conteúdo regional aumenta relevância sem limitar aspirações | Premissa a validar | comparação de módulos e escuta local |
| H-E05 | Instrutores conseguem operar com segurança e linguagem apropriada | Premissa a validar | matriz de competências e ensaio operacional |

## Hipóteses operacionais

| ID | Variável | Valor atual | Método de validação |
|---|---|---|---|
| H-O01 | estudantes por estação | `TBD` | protótipo e limites de segurança |
| H-O02 | rotações por dia | `TBD` | estudo de tempos e rotina escolar |
| H-O03 | estudantes únicos por dia | `TBD` | derivar de estações, grupos e rotações |
| H-O04 | dias operacionais por ano | `TBD` | calendário, manutenção e logística |
| H-O05 | permanência por escola/polo | `TBD` | otimização territorial e demanda |
| H-O06 | necessidade de transporte estudantil | Premissa a validar por território | georreferenciamento e plano de segurança |
| H-O07 | disponibilidade de energia, internet e acessibilidade | Premissa a validar por local | vistoria padronizada |
| H-O08 | equipe e proporção instrutor/estudante | `TBD` | análise de risco e teste operacional |

## Hipóteses de continuidade e conversão

| ID | Hipótese | Valor atual | Validação |
|---|---|---|---|
| H-C01 | estudantes solicitarão informação posterior | taxa `TBD` | telemetria consentida e pesquisa |
| H-C02 | recomendações aumentarão inscrições elegíveis | efeito `TBD` | grupo de comparação |
| H-C03 | haverá oferta acessível compatível com interesses | cobertura `TBD` | inventário geográfico e calendário |
| H-C04 | uma fração ingressará em formação, aprendizagem ou oportunidade | taxa `TBD` | vínculo verificável e acompanhamento |
| H-C05 | acompanhamento em 6 e 12 meses será viável e não invasivo | Premissa a validar | AIPD, teste de contato e perdas amostrais |

## Hipóteses econômicas

| ID | Variável | Valor atual | Regra |
|---|---|---|---|
| H-F01 | aquisição/adaptação das unidades | `TBD` | cotação comparável e especificação neutra |
| H-F02 | equipamentos por módulo | `TBD` | lista técnica, ciclo de vida e cotações |
| H-F03 | salários, encargos e diárias | `TBD` | regime operacional e referências oficiais |
| H-F04 | combustível, pedágio, seguro, guarda e manutenção | `TBD` | rotas simuladas e pesquisa de mercado |
| H-F05 | vida útil e valor residual | `TBD` | engenharia, contabilidade e análise de sensibilidade |
| H-F06 | contribuição privada | `TBD`, não garantida | instrumentos formais e teste de adicionalidade |
| H-F07 | ativos existentes reduzem custo total | Premissa a validar | inventário de disponibilidade e custo de oportunidade |
| H-F08 | híbrido domina móvel ou fixo em parte dos territórios | Premissa a testar, não conclusão | custo total e cobertura por arquétipo territorial |

## Fórmulas conceituais

```text
students_per_day =
    stations
    × students_per_station
    × rotations_per_day

students_per_year =
    students_per_day
    × operating_days

annualized_capex =
    função(capex, vida_útil, valor_residual, taxa_de_desconto)

cost_per_student =
    annualized_capex + annual_opex
    --------------------------------
    unique_students_served

cost_per_experience =
    total_program_cost
    -----------------------
    completed_experiences

cost_per_conversion =
    total_program_cost
    ---------------------------------------------
    students_who_entered_training_or_opportunity
```

Deverão ser evitadas contagens duplicadas de estudantes e conversões. Custos compartilhados serão alocados por regra pública e testados em cenários por unidade, comboio, região e Estado.

## Regras de atualização

- não substituir `TBD` por um número sem fonte, ano-base, unidade e memória de cálculo;
- distinguir cotação, estimativa, dado observado e meta;
- registrar intervalos e sensibilidade, não apenas um ponto;
- documentar hipóteses rejeitadas em `decisions/`;
- não tratar doação como custo zero: registrar manutenção, integração, treinamento e custo de oportunidade.
