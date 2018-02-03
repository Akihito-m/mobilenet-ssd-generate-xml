# MobileNet SSD - annotations pregenerator

## Objectif du script
L'objectif est de prégénérer les annotations sur un dataset dont on veut affiner des sous-classes de classes déjà reconnues.

## Usage
Placez vos images dans le répertoire d'entrée.
Le script ne prend que des .jpeg pour le moment mais vous pouvez l'adapter facilement.
Créez le répertoire de sortie.
Précisez le label de sortie pour les annotations.
Indiquez le label de sortie souhaité pour les annotations.

**python mobilenetssd_images.py [répertoire d'entrée] [répertoire de sortie] [label de sortie]**

## Exemple
**python mobilenetssd_images.py images annotations chat_norvegien**
