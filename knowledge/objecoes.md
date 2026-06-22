Para estruturar o seu projeto final da DIO de forma direta, analítica e focada em um contexto real de mercado, a melhor recomendação única é focar no pilar de **Tratamento de Objeções e Argumentação de Vendas para o Pequeno Varejo (B2B)** utilizando a marca **FYS (Heineken)**.

O principal desafio comercial da FYS no mercado B2B (bares, mercantis e restaurantes) é competir com marcas líderes consolidadas, enfrentando a resistência dos comerciantes quanto ao giro de estoque e aceitação do público.

Abaixo está o escopo pronto da solução e a estrutura do seu `README.md` para entrega no GitHub.

---

## Estrutura de Arquivos do Projeto (`knowledge/`)

Crie uma pasta chamada `knowledge/` no seu repositório com os seguintes arquivos em Markdown (`.md`):

### 1. `knowledge/contexto-do-negocio.md`

```markdown
# Contexto do Negócio - FYS (Grupo HEINEKEN)
* **Origem:** Primeira marca de refrigerantes criada e desenvolvida exclusivamente no Brasil pelo Grupo HEINEKEN.
* **Diferencial Competitivo:** Até 50% menos açúcar comparado à média do mercado e menos calorias. Foco em ingredientes selecionados e sabor natural.
* **Portfólio:** Guaraná da Amazônia, Limão Siciliano, Laranja-Pera, Tônica com Toque de Limão Siciliano (Regular e Zero).
* **Embalagem Principal:** Latas de 350ml (foco em consumo individual e margem para o PDV).

```

### 2. `knowledge/objecoes.md`

```markdown
# Matriz de Objeções e Contra-argumentos (B2B)

1. Objeção: "Meus clientes só pedem as marcas tradicionais/líderes."
   * Contra-argumento: O consumidor atual busca saudabilidade. FYS entrega 50% menos açúcar sem perder o sabor, atraindo um público premium que busca custo-benefício e inovação.

2. Objeção: "Tenho medo do produto ficar parado no estoque."
   * Contra-argumento: Sendo do Grupo HEINEKEN, a FYS conta com forte suporte de distribuição, campanhas de marketing agressivas e embalagens em lata de 350ml, que possuem alto giro e ocupam menos espaço refrigerado.

3. Objeção: "O preço da lata não é o mais barato do mercado."
   * Contra-argumento: O valor agregado e o selo de qualidade HEINEKEN permitem uma margem de lucro superior por unidade vendida para o comerciante, aumentando o ticket médio do estabelecimento.

```

---

## Prompt do Copiloto (System Prompt)

Para simular ou executar a IA, utilize este prompt de sistema estruturado:

```text
Você é o "FYS Sales Copilot", um assistente de IA focado em apoiar o time de vendas B2B da Heineken. Seu objetivo é ajudar o vendedor a responder objeções de donos de pontos de venda (PDVs) que estão relutantes em abastecer seus estoques com FYS. Baseie-se estritamente no fato de que FYS possui 50% menos açúcar, é do portfólio Heineken e oferece alta margem de lucro. Seja direto, profissional e focado em fechar a venda.

```

---

## Estrutura Pronta do `README.md` (Para Entrega no GitHub)

Copie e cole o texto abaixo no arquivo `README.md` principal do seu repositório, ajustando os links conforme necessário:

```markdown
# FYS Sales Copilot - Copiloto de Vendas com IA para Atendimento ao Cliente

## 1. Tema Escolhido
Desenvolvimento de um copiloto de inteligência artificial voltado para o mercado B2B da marca **FYS (Grupo HEINEKEN)**, focado em capacitação de vendas e superação de objeções comerciais no pequeno varejo.

## 2. Usuário Principal
A força de vendas de campo (vendedores e representantes comerciais) que atende pontos de venda (PDVs) como bares, restaurantes, conveniências e minimercados.

## 3. Problema Resolvido
O desafio da inserção de uma marca nova e disruptiva em um mercado de refrigerantes altamente concentrado por marcas tradicionais. O copiloto resolve a fricção no momento da venda, fornecendo argumentos rápidos e técnicos contra as principais objeções dos comerciantes (giro de estoque, preferência de marca e preço).

## 4. Abordagem Utilizada
**Copiloto de Vendas Baseado em Conhecimento (RAG / Context-Aware)**. A IA atua como um assistente de bolso para o vendedor consultar antes ou durante uma negociação comercial.

## 5. Base de Conhecimento (`knowledge/`)
A IA foi alimentada com documentos estruturados extraídos dos dados oficiais da marca FYS:
* `knowledge/contexto-do-negocio.md`: Posicionamento de mercado e chancela do Grupo HEINEKEN.
* `knowledge/objecoes.md`: Mapeamento de dores do comerciante e respectivas contra-argumentações focadas em saudabilidade (50% menos açúcar) e rentabilidade.

## 6. Exemplo de Uso (Simulação)

> **Vendedor (Input):** "O dono do bar me disse que não vai comprar FYS porque o cliente dele só toma a Coca tradicional. Como respondo rápido?"
>
> **FYS Sales Copilot (Output):** 
> "Entendido. Use este argumento direto: 
> *'Seu João, a preferência existe, mas o consumidor mudou. FYS é o único refrigerante do mercado com a qualidade HEINEKEN que entrega 50% menos açúcar de verdade, sem deixar aquele gosto artificial. O senhor vai atrair o público que hoje deixa de consumir refrigerante por saúde, e com uma margem de lucro por lata que a marca líder não te entrega. Vamos fechar uma caixa de Guaraná e uma de Limão Siciliano para teste?'*"

## 7. Melhorias Futuras
* Integração com APIs de CRM para sugerir volume ideal de compra com base no histórico do cliente.
* Módulo de treinamento interativo via áudio para simulação de vendas por comandos de voz.

```
