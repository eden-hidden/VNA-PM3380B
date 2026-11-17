[google108d09d2532f51ce.html](https://github.com/user-attachments/files/34771479/google108d09d2532f51ce.html)
# VNA-PM3380B
Analyseur de réseau vectoriel (VNA) - EDEN JOHEIR


<img width="962" height="585" alt="Capture d’écran 2026-11-12 à 22 10 40" src="https://github.com/user-attachments/assets/8fef75e2-3fd9-4c0b-b445-e3b50029053b" />



## 1. Définition et principe de base

Un **analyseur de réseau vectoriel** (VNA, pour *Vector Network Analyzer*) est un instrument de mesure électronique utilisé principalement dans le domaine des hautes fréquences (RF, micro-ondes, télécommunications).

Contrairement à un appareil de mesure passif, le VNA **génère son propre signal de test** (un balayage en fréquence) qu'il injecte dans le composant à tester (que l'on appelle le *DUT* pour *Device Under Test*, par exemple un câble, un filtre ou une antenne). Il mesure ensuite la réponse du composant en amplitude et en phase.

---

## 2. Que mesure-t-on exactement ?

Le VNA quantifie la façon dont l'énergie se propage à travers le composant. On utilise pour cela les **paramètres S** (*Scattering parameters* ou paramètres de répartition) :

* **Le S11 (Réflexion) :** Mesure l'énergie qui est renvoyée (réfléchie) vers la source à cause d'une mauvaise adaptation d'impédance. Plus le S11 est bas (en négatif, par exemple $-20\text{ dB}$), meilleur est le composant, car cela signifie qu'il absorbe ou transmet l'énergie au lieu de la renvoyer.
* **Le S21 (Transmission) :** Mesure l'énergie qui traverse le composant d'un port à l'autre. C'est l'indicateur utilisé pour mesurer le gain d'un amplificateur ou l'atténuation d'un filtre.

---

## 3. L'affichage : l'abaque de Smith

Sur l'écran d'un VNA, les résultats ne s'affichent pas toujours sous forme de courbes classiques (fréquence en abscisse, amplitude en ordonnée). On utilise très fréquemment un **abaque de Smith** :

* Il s'agit d'un graphique circulaire complexe qui permet de représenter l'impédance électrique d'un circuit.
* Le centre de ce cercle représente l'adaptation parfaite (généralement $50\ \Omega$). L'objectif lors de la conception ou du réglage d'un circuit RF est de faire converger la courbe vers ce point central.

---

## 4. L'étape indispensable : la calibration

Avant de réaliser toute mesure précise, le VNA doit obligatoirement être calibré au bout des câbles de raccordement. Cette étape permet d'éliminer les erreurs dues aux câbles eux-mêmes (atténuation, déphasage). 

On utilise un kit de calibration composé de quatre éléments standards :

1. **Short** (court-circuit)
2. **Open** (circuit ouvert)
3. **Load** (charge adaptée, résistance de $50\ \Omega$)
4. **Thru** (connexion directe entre les ports)


google-site-verification: google108d09d2532f51ce.html
