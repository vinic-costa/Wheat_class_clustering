# Wheat Class Clustering

## Objetivo

O dataset "seeds" da [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/seeds) é um dataset pequeno que contém medidas das propriedades geométricas de grãos de três variedades diferentes de trigo.

Considere a situação hipotética que não temos rótulos para este dataset, foi criado um modelo de clustering que separa os dados em grupos.  Foi feita uma API para o modelo com FlaskAPI para que novos dados sejam classificados conforme os grupos previamente identificados. 

Foi utilzado K-Means como etapa de modelagem.

## Dicionário dos dados

| Área                         | A área da semente em centímetros quadrados                                              |
|------------------------------|-----------------------------------------------------------------------------------------|
| Perímetro                    | O perímetro da semente em centímetros                                                   |
| Compactação                  | Compactação = (4 * pi * área) / perímetro^2                                             |
| Comprimento do grão          | O comprimento da semente em centímetros                                                 |
| Largura do grão              | A largura da semente em centímetros                                                     |
| Coeficiente de assimetria    | Assimetria = (largura (semente à esquerda) - largura (semente à direita)) / comprimento |
| Comprimento do sulco do grão | Comprimento do sulco da semente em centímetros                                          |

---

<div align="center">
<i>Contato</i><br> 
<br>
<a href="https://www.linkedin.com/in/vinic-costa/" target="_blank"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</div>
