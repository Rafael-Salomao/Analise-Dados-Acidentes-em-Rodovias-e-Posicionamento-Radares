# Análise dos Acidentes em Rodovias e Posicionamento de Radares

Este é o repositório do projeto "Análise dos Acidentes em Rodovias e Posicionamento de Radares". Este projeto tem como objetivo investigar a eficácia e impacto dos radares de trânsito nas estradas, analisando dados de acidentes para oferecer insights sobre a segurança viária e fazer recomendações para melhorias.

## Motivação

A motivação por trás deste projeto é contribuir para a segurança e eficiência do tráfego nas estradas do país. Através da análise de dados, buscamos responder perguntas críticas sobre a eficácia dos radares, identificação de pontos críticos e avaliação do impacto econômico dos acidentes.

## Conjunto de Dados

### Dados Acidentes Rodovias PRF

Os dados de acidentes de trânsito foram coletados da base pública da Polícia Rodoviária Federal (PRF), abrangendo o período de janeiro a julho de 2023. Essa fonte oficial proporciona uma compreensão aprofundada da segurança nas estradas, sendo crucial para tomadas de decisões informadas.

### Dados Radares Rodovias Federais

Os dados sobre radares de trânsito nas rodovias federais estão disponíveis no portal "Dados.gov.br" do governo federal. Essas informações, fornecidas pela Agência Nacional de Transportes Terrestres (ANTT), permitem acesso público aos detalhes sobre localização e operação dos radares, contribuindo para decisões embasadas em dados.

## Principais Técnicas/Algoritmos Utilizados

No projeto, foram empregadas diversas bibliotecas e técnicas para análise de dados. Abaixo estão as principais bibliotecas utilizadas:

- **NumPy**
  
- **Pandas**

- **Seaborn**

- **Matplotlib**
  
- **Folium**

- **SciPy.stats**

- **cKDTree**

- **IPython.display**

Certifique-se de instalar essas bibliotecas antes de executar o projeto. Você pode instalá-las usando o arquivo `requirements.txt` fornecido neste repositório.

## Pré-requisitos

```bash
pip install -r requirements.txt
```

## Instruções para Execução

Para executar o código, abra o arquivo .ipynb do projeto em um ambiente Jupyter Notebook. O projeto pode ser visualizado [aqui](https://github.com/Rafael-Salomao/Analise-dos-Acidentes-em-Rodovias-e-Posicionamento-de-Radares/blob/main/An%C3%A1lise_dos_Acidentes_em_Rodovias_e_Posicionamento_de_Radares.ipynb).

## Estrutura do Projeto

1. **Entendimento do Problema de Negócio**
2. **Entendimento dos Dados**
   - Dados Acidentes Rodovias PRF
   - Dados Radares Rodovias Federais
3. **Preparação dos Dados**
4. **Análise Exploratória**
   - Visualizar a distribuição dos acidentes e radares em um mapa.
   - Analisar a frequência de acidentes por rodovia.
   - Avaliar a gravidade dos acidentes (fatais, com feridos, sem vítimas).
5. **Identificação de Zonas de Alto Risco**
   - Determinar áreas com alta frequência de acidentes graves.
   - Comparar com a localização atual dos radares.
6. **Análise de Proximidade**
   - Calcular a distância média dos acidentes até o radar mais próximo.
   - Identificar acidentes que ocorreram distantes de radares.
7. **Recomendações**
8. **Análise de Impacto**
9. **Considerações Adicionais**
10. **Visualizações**
11. **Conclusão**

## Resultados e Principais Insights

- **Eficiência dos Radares:**
  - A presença de radares impacta significativamente na redução de acidentes com mortos e feridos graves, com uma correlação estatística significativa. No entanto, a presença de radares parece não influenciar a ocorrência de acidentes com pessoas ilesas.

- **Pontos Críticos:**
  - A análise identificou áreas de alto risco, como a "BR-116, km-229", que demandam uma melhor cobertura de radares. Além disso, certas rodovias, como "BR-116" e "BR-101", frequentemente registram acidentes graves, sugerindo a necessidade de instalação de radares em trechos específicos.

- **Economia e Justificação de Investimentos:**
  - Além dos aspectos de segurança, é importante considerar o impacto econômico dos acidentes ao avaliar o investimento em radares, pois acidentes rodoviários têm custos substanciais, incluindo custos médicos em regiões onde ocorrem os acidentes.

## Recomendações de Melhorias nas Rodovias Federais

- **Instalação de Radares em Trechos Críticos:**
  - Priorizar a instalação de radares em trechos com alta incidência de acidentes graves, como a "BR-116, km-229", para prevenir acidentes com vítimas fatais.

- **Direcionamento de Recursos em Rodovias Frequentes:**
  - Considerar a instalação de radares em trechos específicos de rodovias, como "BR-116" e "BR-101", que frequentemente registram acidentes graves, para reduzir a gravidade desses acidentes.

- **Avaliação Contínua:**
  - Realizar análises contínuas dos dados de acidentes e radares para ajustar as medidas de segurança conforme necessário e garantir que os radares estejam nos lugares certos.

## Contato

- **LinkedIn:** https://www.linkedin.com/in/rafaelsdomingos/

- **Medium:** https://medium.com/@rafael.salomaod

- **E-mail:** rafael.salomaod96@gmail.com.
