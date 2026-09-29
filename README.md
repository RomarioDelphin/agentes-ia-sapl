# Agentes de IA + SAPL

Estudo de caso e arquitetura de referência para uso responsável de agentes de Inteligência Artificial em fluxos relacionados ao **Sistema de Apoio ao Processo Legislativo (SAPL)**. Este repositório reúne documentação; não contém uma integração executável, código dos agentes ou dados de avaliação.

## Objetivo

Transformar Diários Oficiais, empenhos, contratos e proposições em evidências rastreáveis para análise técnica, fiscalização orçamentária e apoio à tomada de decisão.

## Limite da comparação de tempo

Materiais anteriores mencionaram **48 horas de análise humana intermitente** e **45 segundos de processamento preliminar** em um cenário específico. São etapas diferentes, e não há protocolo de medição, amostra ou registros públicos que permitam reproduzir a comparação. Esses números não devem ser interpretados como redução comprovada do tempo do processo completo.

A arquitetura não representa decisão automatizada. A análise técnica e a responsabilidade permanecem humanas.

## Arquitetura de referência

```mermaid
flowchart LR
    A[Fontes oficiais] --> B[Ingestão e OCR]
    B --> C[Metadados e índice semântico]
    C --> D[Agente auditor]
    D --> E[Revisão técnica humana]
```

### Fontes consideradas

- Diários Oficiais;
- empenhos;
- contratos;
- proposições legislativas;
- documentos em PDF, imagem e XML;
- dados do Portal da Transparência e sistemas institucionais.

### Capacidades previstas para a arquitetura

- organizar e processar documentos;
- relacionar termos pelo contexto, não apenas por palavras;
- cruzar valores e referências;
- sinalizar pontos que merecem revisão;
- registrar fontes e evidências utilizadas.

## Controles essenciais

| Controle | Finalidade |
| :--- | :--- |
| Rastreabilidade | Preservar a origem das evidências e o caminho da análise |
| Governança de dados | Definir fontes, responsáveis, qualidade e limites de uso |
| Segurança da informação | Proteger dados pessoais, sensíveis e institucionais |
| Segurança jurídica | Manter revisão técnica e responsabilidade humana |
| Monitoramento | Registrar erros, contestação, correção e melhoria contínua |

## Princípio de atuação

> A IA apoia o processo. A decisão e a responsabilidade continuam humanas.

## Escopo e evidências

O diagrama e os controles descrevem uma proposta de arquitetura. Para comprovar uma implementação, seriam necessários exemplos de entrada e saída anonimizados, código ou especificação da integração, métricas com método de medição e testes de rastreabilidade e revisão humana. Nenhum desses artefatos é publicado aqui.

## Materiais

- [Carrossel completo do case no LinkedIn](https://www.linkedin.com/posts/romariodelphin_agentes-de-ia-sapl-fiscaliza%C3%A7%C3%A3o-com-controle-activity-7494380024087781377-FfT-/?utm_source=share&utm_medium=member_desktop&rcm=ACoAADgL59gBCYDr_Q-0OPqtg6RLdAhO7Xkj3lk)
- [Artigo: O fim da burocracia invisível](https://www.linkedin.com/pulse/o-fim-da-burocracia-invis%C3%ADvel-rom%C3%A1rio-delphin-nlg5e)
- [Portfólio de Romário Delphin](https://romariodelphin.github.io/)

---

**Romário Delphin**  
Consultor em Inteligência Artificial para o Setor Público  
Agentes de IA · SAPL · GovTech · Transformação Digital
