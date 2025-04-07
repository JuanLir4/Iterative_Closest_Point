
# ICP com KITTI Dataset – Registro de Nuvens de Pontos

Este repositório contém uma implementação do algoritmo **ICP (Iterative Closest Point)** para alinhamento de nuvens de pontos 3D extraídas do [KITTI Dataset](http://www.cvlibs.net/datasets/kitti/). O objetivo é estimar a trajetória de um veículo a partir de dados de nuvem de pontos, comparando a trajetória estimada com a **ground truth** fornecida.

---

## 🧠 Principais Conceitos

- **ICP (Iterative Closest Point)**: algoritmo iterativo usado para alinhar duas nuvens de pontos 3D, minimizando a distância entre elas.
- **SVD (Singular Value Decomposition)**: utilizado para calcular a matriz de rotação ótima.
- **cKDTree**: estrutura eficiente para encontrar os vizinhos mais próximos entre dois conjuntos de pontos.
- **KITTI dataset**: base de dados popular na área de visão computacional e robótica para tarefas como odometria visual, detecção e segmentação.

---


## 🛠️ Dependências

- `numpy`
- `trimesh`
- `matplotlib`
- `scipy`
- `google.colab` (apenas no Colab)

