# Avaliação e Métricas

## Como Avaliar seu Agente

A avaliação pode ser feita de duas formas complementares:

1. **Testes estruturados:** Você define perguntas e respostas esperadas;
2. **Feedback real:** Pessoas testam o agente e dão notas.

---

## Métricas de Qualidade

| Métrica | O que avalia | Exemplo de teste |
|---------|--------------|------------------|
| **Assertividade** | O agente respondeu o que foi perguntado? | Sugerir investimentos de baixo risco |
| **Segurança** | O agente evitou inventar informações? | Realizar uma pergunta complexa. <br> Agente afirmar não ter conhecimento e sugerir alternativas. |
| **Coerência** | A resposta faz sentido para o perfil do cliente? | Sugerir investimento conservador para cliente conservador |

> [!TIP]
> Peça para 3-5 pessoas (amigos, família, colegas) testarem seu agente e avaliarem cada métrica com notas de 1 a 5. Isso torna suas métricas mais confiáveis! Caso use os arquivos da pasta `data`, lembre-se de contextualizar os participantes sobre o **cliente fictício** representado nesses dados.

---

## Exemplos de Cenários de Teste

Crie testes simples para validar seu agente:

### Teste 1: Iniciante com tolerência de baixo risco
- **Pergunta:** "Boa tarde, eu tenho interesse em investir meu dinheiro pra aumentar minha renda, porém eu queria evitar perder meu dinheiro."
- **Resposta esperada:** Sugestão de uma atividade de investimento de baixo risco
- **Resultado:** [ ] Correto  [ ] Incorreto

### Teste 2: Usuário mais experiente
- **Pergunta:** Olá, eu queria comprar ações da VALE3. Sou um estudante de economia e queria saber como que funciona e como prosseguir... (Eu tenho dinheiro guardado para isso)
- **Resposta esperada:** Sugestão de procedimentos ao realizar investimentos de alto risco. 
- **Resultado:** [ ] Correto  [ ] Incorreto

### Teste 3: Pergunta fora do escopo
- **Pergunta:** Incêntivos economicos de um toroide.
- **Resposta esperada:** Olha, aqui é um espaço para dúvidas relacionadas a investimentos. Você teria esse interesse?
- **Resultado:** [ ] Correto  [ ] Incorreto

### Teste 4: Informação inexistente
- **Pergunta:** Como fazer aquele gráfico de ações subir?
- **Resposta esperada:** É uma boa pergunta. Porém eu ainda não tenho conhecimento nisso. Podemos começar com algo mais simplificado, tipo como você quer investir? Te ajudo em maneira simplificada! :)
- **Resultado:** [ ] Correto  [ ] Incorreto

---

## Resultados

Após os testes, registre suas conclusões:

**O que funcionou bem:**
- [Liste aqui]

**O que pode melhorar:**
- [Liste aqui]

---

## Métricas Avançadas (Opcional)

Para quem quer explorar mais, algumas métricas técnicas de observabilidade também podem fazer parte da sua solução, como:

- Latência e tempo de resposta;
- Consumo de tokens e custos;
- Logs e taxa de erros.
