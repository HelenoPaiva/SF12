# Calculadora Clínica SF-12

Aplicação estática em um único arquivo (`index.html`) para cálculo imediato dos escores do SF-12.

## O que esta versão faz
- Coleta as 12 respostas do questionário
- Converte os itens para escala 0–100
- Calcula os 8 domínios do SF-12
- Calcula os dois resumos finais:
  - `PHYS_SUM_0100`
  - `MENT_SUM_0100`
- Exibe um resumo interpretativo
- Permite imprimir em PDF

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Opcionalmente envie este `README.md`.
4. Em **Settings > Pages**, selecione:
   - **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
5. Salve. O GitHub Pages publicará a página em alguns segundos.

## Observação metodológica
Esta versão usa o método transparente adotado no seu conjunto de dados:
- itens em escala 0–100
- 8 domínios
- média dos domínios físicos e mentais para os resumos finais

Ela não usa, nesta primeira etapa, os pesos proprietários clássicos de PCS/MCS.
