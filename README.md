# MDS7203-BFN-Texto
Una implementación "simple" de BFN para la generación de texto sobre un dataset de frases propio.
Se utiliza como red neuronal base una MLP con activación Silu.


Para una implementación más completa, consultar el github oficial de BFN : https://github.com/nnaisense/bayesian-flow-networks
como también una implementación simple de BFN(en construcción) : https://github.com/Algomancer/Bayesian-Flow-Networks

COMO USAR 
Para utilizar esta repo, es necesario tener disponible las librerias de numpy, matplotlib, torch y DataLoader junto a TensorDataset
Al principio del código del archivo MDS7203_proyecto.ipynb se especifican las funcionas necesarias para implementar BFN como también la creación del dataset XOR.
Este último puede ser modificado en la cantidad de datos cambiando "batch size" en la función xor_dataset.

![imagen](https://github.com/JJJakkimoto/MDS7203-BFN-Texto/assets/73626318/fd35a0c2-5eed-4d40-8a2b-77d2333b1b42)



Con respecto a la generación de texto, se puede modificar la variable "words" para poder agregar o quitar palabras y así tener
más resultados con la misma arquitectura.

![imagen](https://github.com/JJJakkimoto/MDS7203-BFN-Texto/assets/73626318/af4820a4-357d-46c3-940c-72c882e0f690)


Algunos resultados : 

Dataset XOR
![imagen](https://github.com/JJJakkimoto/MDS7203-BFN-Texto/assets/73626318/e5786afd-1e31-42fa-97b9-e54995acaeb4)

Palabras generadas(batch=100):
['discrete', 'network', 'model', 'network', 'network', 'fliw', 'leibler', 'kullback', 'flcw', 'continous', 'kullback', 'update', 'kullback', 'update', 'flsw', 'leibler', 'leibler', 'update', 'network', 'flkw', 'fluw', 'loss', 'leibler', 'model', 'network', 'model', 'network', 'loss', 'leibler', 'loss', 'discrete', 'fltw', 'kullback', 'continous', 'kullback', 'leibler', 'model', 'flsw', 'kullback', 'kullback', 'networks', 'flmw', 'update', 'update', 'leibler', 'flgw', 'flgw', 'loss', 'leibler', 'discrete', 'flmw', 'flcw', 'leibler', 'flgw', 'networks', 'loss', 'loss', 'leibler', 'flsw', 'llss', 'loss', 'fliw', 'discrete', 'flaw', 'leibler', 'bayesian', 'leibler', 'distribution', 'update', 'flsw', 'model', 'network', 'leibler', 'fluw', 'loss', 'networks', 'network', 'fldw', 'model', 'network', 'flsw', 'probability', 'network', 'kullback', 'kullback', 'model', 'flgw', 'kullback', 'flsw', 'networks', 'flsw', 'continous', 'leibler', 'model', 'distribution', 'loss', 'networks', 'fluw', 'fltw', 'fliw']


