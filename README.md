# 🛠️ **Desafio Power BI - Analisando dados de um Dashboard de Vendas no Power BI**

## 📖 **Descrição do Desafio**
Este repositório foi criado como parte do bootcamp da DIO para consolidar os aprendizados em Power BI.
O objetivo é replicar e melhorar um projeto prático com base nos conceitos explorados no curso, além de demonstrar habilidades em criação de visuais e layout em relatórios.

## 📋 **Objetivos**

1. Replicar as duas primeiras páginas do relatório fornecido durante o curso.
2. Criar uma **terceira página** personalizada contendo:
   - **Visual Mapa 1:** Soma de vendas (sales) e unidades vendidas por país.
   - **Visual Mapa 2:** Soma do lucro (profit) por país.
   - **Gráfico de Pizza:** Lucro por segmento. (Substituído por gráfico de barras)
     
3. Personalizar o layout:
   - Disposição clara e visualmente agradável dos gráficos.
   - Renomear os visuais para nomes intuitivos e relevantes.
   - Adicionar campos úteis como dicas de ferramentas.
     
4. Publicar o relatório e compartilhá-lo:
   - Como suplemento no PowerPoint, ou
   - Salvar o arquivo no Power BI caso o PowerPoint não esteja disponível.
   - Github
  
## 👩🏻‍💻Meus desenvolvimentos

No Power BI, percebi que a formatação de datas, números e textos segue as configurações regionais do sistema ou do arquivo.
Para garantir que os nomes dos meses e dias da semana aparecessem em inglês nos meus relatórios, usei a função Date.ToText com o parâmetro de cultura "en-US".
Assim, mesmo que alguém tenha configurações regionais diferentes, os nomes aparecem sempre em inglês.

Criei a tabela de calendário gerando datas sequenciais e adicionei colunas como ano, trimestre e dia.
Isso não só deixou o relatório mais padronizado, mas também facilitou o uso por equipes globais, garantindo que todos visualizem as informações de forma consistente.
<img width="953" alt="image" src="https://github.com/user-attachments/assets/18c656d4-ae08-4b57-88f0-8d897d2b5981">

Como a base "Financials" estava com nomenclatura em inglês, padronizei para o inglês a D_Calendário, a tabela de medidas com cálculos em DAX e os nomes dos visuais.
![image](https://github.com/user-attachments/assets/9b54f0ad-cf06-4630-a5b1-883bc9fce8ed)

O Background foi desenvolvido no **Figma**
<img width="959" alt="image" src="https://github.com/user-attachments/assets/dcab16b0-7c0f-4ddd-999f-33f9e3a26480">

## 🚀Resultado Final
**Página 1**

<img width="725" alt="image" src="https://github.com/user-attachments/assets/2c0be71e-ef8c-4474-a78d-c8a49412883c">

**Página 1 + Tooltip**

<img width="725" alt="image" src="https://github.com/user-attachments/assets/80022a58-8a89-4452-a52c-658c42a5b8d6">

**Página 2**

<img width="724" alt="image" src="https://github.com/user-attachments/assets/5d10bdc9-3f98-417a-bb9a-097309ff34b3">

**Página 3**

<img width="724" alt="image" src="https://github.com/user-attachments/assets/f75521ea-6a22-4c7f-bc06-762d38020df7">

------

### 🎯Desafio - Fase 2: Painel de Vendas

Este projeto tem como objetivo desenvolver um painel interativo para análise de vendas e lucratividade utilizando **Power BI**, com foco em apresentar os principais indicadores de desempenho, segmentações detalhadas e insights sobre os dados fornecidos.

## Estrutura do Relatório

### 1. Página Inicial do Relatório

<img width="723" alt="image" src="https://github.com/user-attachments/assets/dc00405e-32ff-4baf-b80e-eefb35de6095">

#### Descritivo:
- **Indicadores principais:**
  - Total de vendas (`$118,73 Mi`), unidades vendidas (`1.125.806`), descontos concedidos (`$9,21 Mi`), receita bruta (`$127,93 Mi`) e custo das mercadorias vendidas (COGS - `$101,83 Mi`).
- **Gráfico de Linhas:**
  - Total de vendas por mês e ano (ex.: maior receita em outubro com `$21,7 Mi`).
- **Gráfico de Barras (por segmento):**
  - Receita por segmento (Governo lidera com `$52,50 Mi`).
- **Gráfico de Barras Horizontal (por produto):**
  - Receita total por produto (ex.: "Paseo" é o mais lucrativo com `$33,01 Mi`).
- **Gráfico por País:**
  - Identificação dos países com maior participação nas vendas (ex.: Estados Unidos, Canadá e França).

#### Técnicas Aplicadas:
- Criação de **gráficos dinâmicos** (linhas, barras, horizontais) para destacar a sazonalidade e os principais contribuidores.
- Uso de **cartões** para consolidar KPIs importantes.
- Uso de Bookmarks com botões de ícones interativos para facilitar a transição entre visuais do relatório.

![image](https://github.com/user-attachments/assets/c45ff877-0f58-4e56-a53f-39d58e15f03c)

---

### 2. Página Secundária - Análises Detalhadas

#### Descritivo:
- **Gráfico de Hierarquia (Árvore):**
  - Lucratividade detalhada por ano e país.
- **Gráfico Radar:**
  - Comparação de lucratividade entre produtos.
- **Treemap (Mapa de Árvore):**
  - Participação de cada segmento no lucro total.
- **Gráfico de Cascata:**
  - Crescimento acumulado dos lucros por trimestre.

#### Técnicas Aplicadas:
- Utilização de **gráficos avançados** (radar, cascata e treemap) para destacar correlações e hierarquias.
- Construção de visuais intuitivos para facilitar insights detalhados.
  
<img width="722" alt="image" src="https://github.com/user-attachments/assets/3bc36b7f-25e0-4358-8d5f-cb33e4ddb8e1">

---

## 🔨🔧🪛Principais Técnicas e Recursos Utilizados

1. **Criação de Indicadores (KPIs):**
   - Implementação de cartões para consolidar os Big Numbers do relatório.

2. **Gráficos Visuais Avançados:**
   - Uso de gráficos de linha, radar, cascata, treemap e hierarquia para detalhamento.

3. **Filtros e Segmentadores:**
   - Implementação de filtros dinâmicos para personalizar as análises.

4. **Interatividade e Navegação:**
   - Botões interativos para facilitar transições

5. **Análise Geoespacial:**
   - Mapas que destacam as vendas por região.

---

## 📊 Link para o Dashboard
![image](https://github.com/user-attachments/assets/bdc77f4a-2e49-49b2-b21a-1f827aa6e800)

https://app.powerbi.com/view?r=eyJrIjoiMWM2MDUwOWUtODBiNy00M2NhLTliOTAtN2M5ZDFkYWQxMTFhIiwidCI6IjM3NWZkZjA4LTI0YTgtNDFjZC04ZWQyLThkZjE4YjZkNjg3NCJ9&pageName=c33c9c20511b95866562

---
## 📧 Contato
Em caso de dúvidas ou sugestões, sinta-se à vontade para entrar em contato:

- **Email:** jkaminovski@gmail.com
- **LinkedIn:** [(https://www.linkedin.com/in/joice-kaminovski-dias/)]

