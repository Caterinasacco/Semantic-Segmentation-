Questo repository contiene notebook dedicati alla segmentazione semantica delle pareti degli edifici, utilizzando modelli avanzati di deep learning.

Contenuto dei Notebook

1. Segmentaz_pareti_modello_Ci.ipynb
Modello Utilizzato: U-Net
Descrizione:
Utilizza una rete U-Net per eseguire la segmentazione semantica delle immagini.
Addestrato su un dataset specifico disponibile su Kaggle.
Adatto per immagini con risoluzione standard e maschere con classi multiple.
Tecniche Usate:
Data Augmentation (flip orizzontale e verticale, rotazione, zoom casuale).
Dropout Layers per migliorare la generalizzazione.
2. Semantic_Segmentation_Encoder_Decoder.ipynb
Modello Utilizzato: ResNet-50 Dilated + PPM (Pyramid Pooling Module)
Descrizione:
Utilizza ResNet-50 dilated come encoder per estrarre feature ricche dalle immagini.
PPM (Pyramid Pooling Module) come decoder per ottenere previsioni di segmentazione precise.
Progettato per segmentare immagini locali ad alta risoluzione.
Tecniche Usate:
Feature Extraction tramite encoder preaddestrati.
Pooling Piramidale per catturare il contesto globale dell'immagine.
