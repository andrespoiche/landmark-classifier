# Landmark Classifier — Proyecto CNN

## Descripción
Modelos de clasificación de imágenes de landmarks usando PyTorch.
Se implementaron dos enfoques: CNN desde cero y Transfer Learning con ResNet18.

## Dataset
Subconjunto del Google Landmarks Dataset v2 con 50 clases.

## Resultados
| Modelo | Test Accuracy |
|--------|--------------|
| CNN desde cero | 43.12% |
| ResNet18 Transfer Learning | 71.36% |

## Estructura
landmark-classifier/
├── cnn_from_scratch.ipynb
├── transfer_learning.ipynb
├── app.ipynb
└── README.md

## Cómo ejecutar
1. Abrir el notebook en Google Colab
2. Activar GPU: Entorno de ejecución → GPU T4
3. Montar Google Drive con el dataset
4. Ejecutar todas las celdas en orden

## Tecnologías
- Python 3.10
- PyTorch
- torchvision
  
## Video de presentación
[Ver video en YouTube](https://youtu.be/F7zKuALfTy8)
- Google Colab GPU T4
