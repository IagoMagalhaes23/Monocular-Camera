# Monocular Camera

## Introdução
A estimativa de profundidade monocular é a tarefa de estimar o valor de profundidade (distância relativa à câmera) de cada pixel dada uma única imagem RGB (monocular). Essa tarefa desafiadora é um pré-requisito fundamental para determinar a compreensão da cena para aplicativos como reconstrução de cena 3D, direção autônoma e AR. Os métodos de última geração geralmente se enquadram em uma de duas categorias: projetar uma rede complexa que seja poderosa o suficiente para regredir diretamente o mapa de profundidade ou dividir a entrada em compartimentos ou janelas para reduzir a complexidade computacional.

## Projetos
- Estimativa de distância de faces com camera monocular
Este projeto visa detectar faces com a biblioteca MediaPipe e através do modelo MiDaS v2.1 small que irá gerar uma imagem em profundidade será possível estimar a distância da face até a camera. No momento apenas o ponto central da face é utilizado para calcular a distância entre face e camera, porém, ao longo do desenvolvimento dos algoritmos pretende-se utilizar mais pontos.

- Robô com Raspberry Pi 3

## Links úteis
- [overleaf do artigo](https://www.overleaf.com/9527958838cjhphftnzmgs#7e222a)

## Referências
- https://levelup.gitconnected.com/real-time-distance-estimation-to-faces-with-a-monocular-web-cam-4f621821ca17
- 
