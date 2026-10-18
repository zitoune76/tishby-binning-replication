# tishby-binning-replication
# tishby-binning-replication

Réplication de l'estimation de l'information mutuelle par binning
(Shwartz-Ziv & Tishby) sur les activations d'un réseau de neurones
12 → 10 → 7 → 5 → 4 → 3 → 2.

![binning_animation](https://github.com/user-attachments/assets/...)  



- Activations : tanh sur les couches cachées, logits sur la dernière couche
- 30 bins entre le min et le max des activations de chaque couche
- SGD, lr = 0.01, 9998 epochs, moyenne sur 50 initialisations
