# MobileNet SSD - annotations pregenerator

## Objectif du script
L'objectif est de pr�g�n�rer les annotations sur un dataset dont on veut affiner des sous-classes de classes d�j� reconnues.

## Usage
Placez vos images dans le r�pertoire d'entr�e.
Le script ne prend que des .jpeg pour le moment mais vous pouvez l'adapter facilement.
Cr�ez le r�pertoire de sortie.
Pr�cisez le label de sortie pour les annotations.
Indiquez le label de sortie souhait� pour les annotations.

**python mobilenetssd_images.py [r�pertoire d'entr�e] [r�pertoire de sortie] [label de sortie]**

## Exemple
**python mobilenetssd_images.py images annotations chat_norvegien**
