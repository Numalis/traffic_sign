# traffic_sign

- jeu de donné gtsrb téléchargeable ici: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

- modèles de cnn au format h5, créés pour le usecase, disponibles dans l'archive cnn_traffic_sign.tar

détails de l'archive:

contient les modèles générés durant divers tests et experimentations (appelés exp_nom-modele), avec quelques précisions dans le nommage : 
**keras_2-8-0** -> version de keras utilisé 
**e30** -> 30 epochs 
**50px** -> image de 50x50 pixels 

(exemple: dataflair_e30_50px_gpu.h5).
Note : lorsque la version de keras n'est pas précisé, il s'agit de la version par défaut dans l'environnement conda (2.2.4), lorsque le modèle comporte la mention _gpu à la fin c'est qu'il a été entrainé via une version gpu de tensorflow

Les modèles avec les meilleurs resultats sont **dataflair_balanced_normalized_e50_50px.h5** et **dataflair_augmented_e50_50px.h5**
