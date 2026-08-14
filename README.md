# Projeto Horizonte

> **Nome provisório.** Rede pública de descoberta profissional e conexão com oportunidades, inicialmente desenhada como piloto no Estado de São Paulo.

## Site da documentação

Este repositório pode ser publicado como um site estático navegável com [MkDocs Material](https://squidfunk.github.io/mkdocs-material/). O site inclui menu por trilhas, busca, links entre páginas e temas claro e escuro.

Para visualizar localmente:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements-docs.txt
mkdocs serve
```

Depois, acesse `http://127.0.0.1:8000`. O workflow [`.github/workflows/docs.yml`](.github/workflows/docs.yml) gera e publica o site automaticamente no GitHub Pages a cada alteração na branch principal. No GitHub, configure **Settings → Pages → Build and deployment → Source** como **GitHub Actions** uma única vez.

## Em cinco minutos

### Problema

O Projeto Horizonte parte de uma **hipótese a validar**: estudantes não têm as mesmas oportunidades de conhecer profissões, ambientes técnicos e caminhos de formação. Essa desigualdade de exposição pode restringir escolhas antes mesmo de elas serem formuladas.

> Um jovem só pode desejar aquilo que consegue imaginar.

O programa não presume qual carreira é melhor nem promete emprego. Pretende ampliar o repertório e reduzir a distância informacional entre estudantes e oportunidades existentes.

### Hipótese

Se estudantes de escolas públicas, sobretudo em territórios vulneráveis, tiverem experiências profissionais curtas, práticas e seguras, seguidas de orientação e acesso continuado a oportunidades verificadas, então poderão conhecer mais alternativas e tomar decisões mais informadas. A eventual melhora em inscrições, matrículas, aprendizagem ou trabalho é um resultado a testar, não uma promessa.

### Solução proposta

Uma rede que combina:

1. **descoberta:** contato com diferentes profissões;
2. **experimentação:** atividades práticas breves, sem pretensão de qualificação;
3. **orientação:** explicação clara sobre cada caminho;
4. **Central de Oportunidades:** ligação com formação, bolsas, aprendizagem e processos públicos ou privados elegíveis;
5. **continuidade:** acompanhamento digital, com proteção reforçada de dados de crianças e adolescentes;
6. **avaliação:** comparação de resultados e custos para decidir se, onde e como expandir.

Fluxo conceitual:

**DESCOBRIR → EXPERIMENTAR → INTERESSAR-SE → ORIENTAR-SE → ENCONTRAR FORMAÇÃO → ACESSAR OPORTUNIDADES**

### Como funciona

Escolas ou polos receberiam unidades móveis, módulos transportáveis ou equipes ligadas a estruturas fixas existentes. Estudantes circulariam por estações práticas, registrariam interesses de forma proporcional e receberiam próximos passos concretos. A duração da visita, o número de estações e a forma de deslocamento serão definidos por capacidade, densidade escolar, distâncias, segurança, rotina pedagógica e custo — não por uma regra fixa de “uma semana por escola”.

### Quem atende

Prioridade inicial proposta:

- estudantes do 9º ano do ensino fundamental e do ensino médio da rede pública;
- territórios selecionados por critérios transparentes de vulnerabilidade, acesso à educação profissional, ruralidade e condições de mobilidade;
- outras faixas somente mediante justificativa pedagógica e operacional.

Os critérios e pesos do futuro **Índice de Prioridade de Descoberta Profissional (IPDP)** ainda serão validados. Violência não será critério absoluto.

### Por que considerar infraestrutura móvel?

Porque compartilhar equipamentos pode ampliar cobertura sem instalar um laboratório completo em cada escola. Isso é apenas uma hipótese econômica. O caminhão é ferramenta, não objetivo. O estudo comparará:

- **móvel:** laboratórios itinerantes;
- **fixo:** centros regionais permanentes;
- **híbrido:** estruturas existentes complementadas por mobilidade.

O piloto deve utilizar primeiro ativos de SENAI, SENAC, Centro Paula Souza, Institutos Federais, universidades e governos quando houver disponibilidade, adequação e instrumento jurídico. Frota própria só será proposta após inventário, análise de utilização e comparação de custo total.

### Central de Oportunidades

Após a experiência, o estudante deve encontrar informações verificadas sobre cursos, requisitos, gratuidade ou preço, bolsas, distância, inscrições e oportunidades de aprendizagem ou estágio legalmente cabíveis. A Central não garante vaga e não favorece patrocinadores. Empresas não recebem dados pessoais de estudantes nem acesso exclusivo a recrutamento.

### Piloto em São Paulo

Serão especificados três cenários — mínimo, recomendado e ampliado — sem preencher custos desconhecidos. Cada cenário terá desenho operacional, grupos de comparação, critérios territoriais e regras de parada. Quantidades de unidades, escolas, estudantes, dias, profissionais, CAPEX e OPEX permanecem **TBD / premissas a validar** até inventário, desenho amostral e cotações documentadas.

### Financiamento

O estudo mapeará recursos públicos, cooperação institucional e contribuições privadas. Cada fonte será classificada como **confirmada**, **provável**, **possível** ou **requer parecer jurídico**. Nenhuma fonte será vinculada a uma despesa sem base normativa e análise de elegibilidade. A governança deve impedir publicidade dirigida, captura de dados, exclusividade e favorecimento.

### Avaliação

Alcance não será confundido com impacto. O indicador econômico central proposto é:

```text
custo_por_encaminhamento_efetivo =
    custo_total_do_programa
    -----------------------------------------------
    jovens_que_ingressaram_em_formacao_ou_oportunidade
```

“Encaminhamento efetivo” terá definição, janela temporal e evidência auditável antes do piloto. A avaliação poderá usar randomização quando ética e operacionalmente possível, ou alternativas como implantação faseada, diferenças-em-diferenças e coortes longitudinais. Se o modelo móvel perder para alternativas, a recomendação deve mudar.

## Princípios do projeto

1. O jovem não pode escolher aquilo que desconhece.
2. Descobrir vem antes de escolher.
3. A experiência deve ser prática.
4. O caminhão é ferramenta, não objetivo.
5. A infraestrutura deve ser compartilhada.
6. Utilizar primeiro o que já existe.
7. Não duplicar infraestrutura sem necessidade.
8. Empresas podem participar, mas não capturar a política.
9. Não capturar dados de menores para fins comerciais.
10. Medir resultado, não marketing.
11. Começar pequeno.
12. Testar.
13. Avaliar.
14. Abandonar componentes que não funcionem.
15. Expandir somente com evidência.

## Status

**Fase 0 — estruturação.** Este repositório contém a arquitetura documental, as hipóteses iniciais, as lacunas de pesquisa e o plano de construção. Ainda não contém uma proposta pronta para contratação ou execução. Valores financeiros são `TBD` até haver fontes, memória de cálculo e cotações comparáveis.

## Documentos

| Trilha | Entrada | Finalidade |
|---|---|---|
| Projeto técnico | [`docs/00-visao-geral.md`](docs/00-visao-geral.md) | índice dos capítulos e estado de elaboração |
| Hipóteses | [`financial/assumptions.md`](financial/assumptions.md) | registro testável, sem números inventados |
| Pesquisa | [`research/lacunas-de-pesquisa.md`](research/lacunas-de-pesquisa.md) | perguntas, evidências e critérios de conclusão |
| Fontes | [`research/fontes.md`](research/fontes.md) | protocolo de fontes e rastreabilidade |
| Plano | [`docs/21-roadmap.md`](docs/21-roadmap.md) | sequência, entregáveis e gates de decisão |
| Decisões | [`decisions/README.md`](decisions/README.md) | registro de decisões arquiteturais |
| Produtos executivos | [`proposal/`](proposal/) | brief, proposta política, pitch e perguntas difíceis |
| Modelo econômico | [`financial/`](financial/) | CAPEX, OPEX, cenários e comparação |

## Próximos passos

1. aprovar definições operacionais e protocolo de evidências;
2. inventariar infraestrutura existente e sua disponibilidade real;
3. consolidar dados educacionais e territoriais com ano-base e fonte;
4. conduzir escuta com estudantes, escolas e instituições formadoras;
5. desenhar experiências, salvaguardas e Central de Oportunidades;
6. obter cotações comparáveis e construir os três cenários;
7. pré-registrar avaliação e regras de decisão;
8. realizar crítica adversarial antes de recomendar o piloto.
