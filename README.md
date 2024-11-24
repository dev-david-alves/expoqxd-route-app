# Roteamento Sustentável de Caminhões 🚛🌱 - Expoqxd

Este projeto implementa uma plataforma interativa que realiza o roteamento inteligente de caminhões entre cidades, priorizando rotas mais sustentáveis. Utilizando uma combinação de algoritmos de busca, análise de dados e inteligência artificial, o sistema sugere as melhores rotas com base em critérios como:

- **Distância** entre as cidades.
- **Tipo de via** utilizada.
- **Consumo de combustível** estimado.
- **Emissão média de CO2**, priorizando rotas de menor impacto ambiental.

## Funcionalidades Principais

1. **Cálculo de emissões de CO2:** Integração com uma API para estimar as emissões médias de cada rota.
2. **Visualização das rotas:** Geração de gráficos para ilustrar as rotas com base nos critérios analisados.
3. **Ranqueamento de rotas:** Algoritmo de busca que considera pesos para métricas de **distância** e **sustentabilidade**, com ênfase em rotas mais sustentáveis.
4. **Insights baseados em IA:** As 10 melhores rotas são analisadas por um modelo de IA (Llama) para extrair insights e justificar a escolha de rotas sustentáveis ao usuário.
5. **Interface amigável:** Uma interface interativa permite que o usuário insira a cidade de origem e a cidade de destino para obter as melhores rotas.

## Tecnologias

- **Bibliotecas necessárias**:
  - `dash`
  - `networkx`
  - `requests`
  - `langchain_ollama`
  - `tkinter`

- **APIs utilizadas**:
  - API para cálculo de emissões de CO2 - [CarbonSutra](https://www.carbonsutra.com).

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/dev-david-alves/expoqxd-route-app.git
