# Desafio: Classificador de Nível de Herói

Entendendo o Desafio

Este repositório contém um exercício prático para aplicar variáveis, operadores, laços de repetição e estruturas de decisão em JavaScript.

Descrição do desafio

Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói. Use uma estrutura de decisão para apresentar uma mensagem informando o nível do herói segundo a tabela abaixo:

- XP < 1.000: Ferro
- 1.001 — 2.000: Bronze
- 2.001 — 5.000: Prata
- 5.001 — 7.000: Ouro
- 7.001 — 8.000: Platina
- 8.001 — 9.000: Ascendente
- 9.001 — 10.000: Imortal
- >= 10.001: Radiante

Saída esperada

Ao final, deve ser exibida a mensagem:

"O Herói de nome **{nome}** está no nível de **{nivel}**"

Estrutura do repositório

- `index.js` — arquivo principal com a lógica do desafio.

Como executar

Requisitos:

- Ter o Node.js instalado (versão 12+ recomendada).

No terminal (use o diretório `desafio-logica-js`):

```bash
# instalar dependências (se houver)
# npm install

# executar o script
node index.js
```

Exemplo de uso

Se `index.js` definir:

```js
const nome = 'Artemis'
const xp = 3500
// ... lógica que determina o nível
```

A saída esperada será algo como:

```
O Herói de nome Artemis está no nível de Prata
```

Sugestões para evoluções

- Permitir leitura de entrada via `prompt`/`readline` para tornar o script interativo.
- Ler uma lista de heróis a partir de um arquivo JSON e classificar todos.
- Adicionar testes automatizados (por exemplo, com `jest`) para validar a classificação.
- Criar uma pequena interface web/React ou um template no Figma com o layout da ficha do herói.

Entrega e boas práticas

- Crie um repositório no GitHub para versionar seu projeto (pode dar fork se houver repositório base do expert).
- Inclua todos os arquivos necessários (ex.: banco de dados em JSON, imagens, links para protótipos).
- Comente e organize seu código para facilitar a leitura durante entrevistas técnicas.

Licença

Este repositório está disponível para fins de estudo e portfólio. Sinta-se à vontade para adaptar e melhorar.

Boa sorte — mostre seu melhor trabalho! 😎
