# MDS7203-BFN-Texto
Una implementación "simple" de BFN para la generación de texto sobre un dataset de frases propio.
Se utiliza como red neuronal base una MLP con activación Silu.


Para una implementación más completa, consultar el github oficial de BFN : https://github.com/nnaisense/bayesian-flow-networks
como también una implementación simple de BFN(en construcción) : https://github.com/Algomancer/Bayesian-Flow-Networks

COMO USAR 
Para utilizar esta repo, es necesario tener disponible las librerias de numpy, matplotlib, torch y DataLoader junto a TensorDataset
Al principio del código se especifican las funcionas necesarias para implementar BFN como también la creación del dataset XOR.
Este último puede ser modificado en la cantidad de datos cambiando "batch size" en la función xor_dataset.

Con respecto a la generación de texto, se puede modificar la variable "words" para poder agregar o quitar palabras y así tener
más resultados con la misma arquitectura.
