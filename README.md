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

## 🚀Resultado Final
**Página 1**

<img width="725" alt="image" src="https://github.com/user-attachments/assets/2c0be71e-ef8c-4474-a78d-c8a49412883c">

**Página 1 + Tooltip**

<img width="725" alt="image" src="https://github.com/user-attachments/assets/80022a58-8a89-4452-a52c-658c42a5b8d6">

**Página 2**

<img width="724" alt="image" src="https://github.com/user-attachments/assets/5d10bdc9-3f98-417a-bb9a-097309ff34b3">

**Página 3**

<img width="724" alt="image" src="https://github.com/user-attachments/assets/f75521ea-6a22-4c7f-bc06-762d38020df7">

O Background foi desenvolvido no **Figma**
