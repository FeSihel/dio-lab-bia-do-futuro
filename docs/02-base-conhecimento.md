# Base de Conhecimento

## Dados Utilizados

Descreva se usou os arquivos da pasta `data`, por exemplo:

| Arquivo | Formato | Utilização no Agente |
|---------|---------|---------------------|
| `perfis_investidores.csv` | CSV | Exemplos de perfis e desejos. |
| `prompt_file` | MD | Padronizar prompts e comportamentos. |

---

## Adaptações nos Dados

> Você modificou ou expandiu os dados mockados? Descreva aqui.

Remoção de arquivos de exemplo e adição de arquvio autoral. [Gerado por IA e modificado]

---

## Estratégia de Integração

### Como os dados são carregados?
> Descreva como seu agente acessa a base de conhecimento.

Serão incluídos como base de treinamento do Agente.

### Como os dados são usados no prompt?
> Os dados vão no system prompt? São consultados dinamicamente?

Ambos agente e usuário possuiram acesso do arquivo para referências.

---

## Exemplo de Contexto Montado

> Mostre um exemplo de como os dados são formatados para o agente.

```
Perfil 1: Conservador
Cliente Exemplo: Maria, 45 anos
Desejo / Objetivo: Guardar dinheiro para uma emergência / Preservação de capital.
Perfil de Risco: Tolerância baixa (não quer risco de perdas).
Horizonte: Curto prazo (1 a 3 anos).
Aplicação Prática: Tesouro Selic ou CDBs de liquidez diária.
Significado: O dinheiro rende diariamente com a taxa básica de juros, permitindo resgate a qualquer momento sem surpresas.

Perfil 2: Moderado
Cliente Exemplo: Carlos, 32 anos
Desejo / Objetivo: Comprar um carro daqui a 4 anos / Crescimento gradual do patrimônio.
Perfil de Risco: Tolerância média (aceita pequenas variações).
Horizonte: Médio prazo (3 a 5 anos).
Aplicação Prática: Fundos Multimercado, Tesouro IPCA+ ou LCI/LCA.
Significado: Mistura segurança com um toque de risco para superar a inflação ao longo dos anos.

Perfil 3: Arrojado
Cliente Exemplo: Ana, 24 anos
Desejo / Objetivo: Construir independência financeira / Maximizar rentabilidade.
Perfil de Risco: Tolerância alta (não se importa com oscilações no curto prazo).
Horizonte: Longo prazo (mais de 5 anos).
Aplicação Prática: Fundos de Ações, ETFs globais e FIIs (Fundos Imobiliários).
Significado: Envolve ser sócio de grandes empresas ou imóveis, buscando ótimos retornos de longo prazo apesar da volatilidade.
```
