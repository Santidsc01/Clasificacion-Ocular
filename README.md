# Clasificacion-Ocular
![Banner](Banner/ojito.jpg)
Santiago Gelvez, Santiago Chain

# Objetivo
Desarrollar y evaluar un modelo de red neuronal convolucional (CNN) capaz de clasificar imágenes oculares en diferentes categorías de enfermedades.

# Dataset
Este es el link del dataset utilizado: https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k <br>
El dataset Ocular Disease Intelligent Recognition (ODIR) es una base de datos oftálmica estructurada que contiene información de 5,000 pacientes, incluyendo edad, fotografías de fondo de ojo a color de ambos ojos y palabras clave de diagnóstico de médicos.<br>
Este conjunto de datos representa información de pacientes recopilada por Shanggong Medical Technology Co., Ltd. de diferentes hospitales en China, usando cámaras de marcas como Canon, Zeiss y Kowa, lo que resulta en resoluciones de imagen variables. Las anotaciones fueron realizadas por lectores capacitados con control de calidad y clasifican a los pacientes en ocho categorías:<br>
Normal (N)<br>
Diabetes (D)<br>
Glaucoma (G)<br>
Cataratas (C)<br>
Degeneración Macular Relacionada con la Edad (A)<br>
Hipertensión (H)<br>
Miopía Patológica (M)<br>
Otras enfermedades/anomalías (O)<br>

# Modelos
Para la Densenet:<br>
•	Red Preentrenada: DenseNet (Weights de ImageNet).<br>
•	Capa de Adaptación: Pooling global (Global Average Pooling).<br>
•	Clasificación: Capa totalmente conectada (Fully Connected Layer).<br>
•	Optimización: Adam con tasa de aprendizaje ajustable.<br>
•	Técnicas de Mejora: Transfer learning, balanceo de clases, aumento de datos.<br>
•	Precisión Numérica: FP16 para optimización en GPU.<br>

# Enlaces
