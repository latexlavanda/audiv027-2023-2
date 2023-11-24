### Materiales
- Internet
- Aceptación
- Computador
- Cámara
- Dataset (kaggle) de retratos
- Google Collab
- Tensorflow
- Imgur

# Style Transfer

ejemplo https://www.youtube.com/watch?v=S_I0SGAO73A

The Coding Train

https://github.com/yining1023/styleTransfer_spell

https://yining1023.github.io/styleTransfer_spell/

https://spell.run/docs/core_concepts/#machine-learning-101

(no funciona)

https://github.com/lengstrom/fast-style-transfer

pasos:

- generar imagen random a partir de base de datos
- a partir de esa imagen, mediante la cámara, que pase el dtyle transfer

## Transferencia de Estilo Neural

### Un Algoritmo Neural de Estilo Artístico
![image](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/ef867db4-1020-4701-b106-a77f2506be4f)

En las bellas artes, especialmente en la pintura, los humanos han dominado la habilidad de crear **experiencias visuales únicas mediante la composición de una interacción compleja entre el contenido y el estilo de una imagen**. Hasta el momento se desconoce la base algorítmica de este proceso y no existe ningún sistema artificial con capacidades similares. Sin embargo, en otras áreas clave de la percepción visual, como el reconocimiento de objetos y rostros, el desempeño casi humano fue demostrado recientemente por una clase de modelos de visión de inspiración biológica llamados Redes Neurales Profundas. Aquí presentamos un sistema artificial basado en una red neuronal profunda que crea imágenes artísticas de alta calidad perceptiva. El sistema utiliza representaciones neuronales para separar y recombinar contenido y estilo de imágenes arbitrarias, proporcionando un algoritmo neuronal para la creación de imágenes artísticas. Además, a la luz de las sorprendentes similitudes entre las redes neuronales artificiales de rendimiento optimizado y la visión biológica, nuestro trabajo ofrece un camino hacia una **comprensión algorítmica de cómo los humanos crean y perciben imágenes artísticas**.

![image](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/b6597e95-834e-431b-aa92-be4d9ae0c453) https://www.youtube.com/watch?v=bFeltWvzZpQ

https://learn.ml5js.org/#/reference/style-transfer

https://github.com/ml5js/training-styletransfer/blob/master/README.md

https://colab.research.google.com/drive/1TZNdhoUEBoxQqY5EFloZcuyYUs9oNQ-g?usp=sharing


base de datos:
https://www.kaggle.com/datasets/karnikakapoor/art-portraits/

# Objetivo: Lograr que funcione Style Transfer
### Proceso
![image](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/5290e52d-eb1f-4a74-a032-226762fd9f80)

- Código va al Google Collab
- Se comprueban los pasos, uno por uno
- Una vez probadas la imágenes de ejemplo, se prueban los formatos de las aplicadas
- Subir el dataset a una carpeta en imgur para obtener url por imagen
- Jugar

https://colab.research.google.com/drive/1vgZSMThTciHcasiIZBirbMvxXrQNrJeJ?usp=sharing

### Resultados Hegemónicos

![image](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/8721ec25-d3df-4808-bfac-6a514083deba)
![2c336d00-c585-4364-b7da-2e910bf6cf86](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/279eeb12-61d4-459b-b76d-0b52d8cda5e7)
![60924b72-ed89-46d3-8188-c2b7a896bf72](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/543a9341-04c8-4242-bc44-73719bf6cc5d)
![8888fab5-0c53-4375-82d2-5c47a4b448df](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/99cf3e70-8bcc-4f3c-8b2a-f4d6b5dd5ac7)

### Resultados "Fallo"

![01967086-9fc5-452f-a4e4-7c00a42f1775](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/b4d9ee88-f2d9-4a03-8d62-c00322911c8d)
![533a66c8-4cd2-4e04-a9fc-9890a3fdc279](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/d0cd7b57-c25c-40e3-9716-36373f69dc01)
![9684bf14-547f-4fe8-9989-93bfb6889978](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/ec6f6d52-cc83-4d08-93c5-331226735b0c)
![beb7ab8c-272b-4fdb-86a2-b1bf24fdc3c6](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/f507e8f7-9e0e-4742-8947-ad226ec74c94)
![image](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/585a900a-7c93-4d99-9781-0649afe028f9)
![7124fcb0-5bb4-49b6-a457-30044617ce96](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/4af37a0e-f1a1-4349-b2a2-43f5f6a27ff1)
![23b9026c-8a20-43c2-b969-ea71ea7e75e3](https://github.com/latexlavanda/audiv027-2023-2/assets/142627713/ab98b0cd-c383-48d3-9405-faa955f9171c)


### Conclusión:

La características humanas son hasta cierto punto, imitables; pero de la misma forma que quedó casi obsoleta la posibilidad e interés por style transfer; hay que aprovechar la desviación de las soluciones para explotarlarlas considerando que el objetivo no tiene por qué ser estéticamente hegemónico.
Pero no de generar imágenes con órdenes, sino desde el "fallo".
