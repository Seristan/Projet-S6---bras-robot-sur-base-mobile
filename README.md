# Contrôleur de Stepper pour Bras Robot

Ce projet consiste en un contrôleur de stepper pour un bras robotisé, utilisant un TMC-2225 pour contrôler le moteur, un AS5600 pour mesurer la rotation du stepper, et un STM32 pour contrôler l'ensemble du système. De plus, il intègre deux LDO pour convertir la tension de la batterie en 5V et 3.3V. La carte est divisée en deux sections reliées par des pins.

## Structure du Répertoire

Le répertoire du projet est organisé comme suit :

- `KICAD/`: Ce dossier contient tous les fichiers de projets KiCad.
- `KICAD/footprints/`: Ce sous-dossier contient toutes les empreintes personnalisées utilisées dans les projets KiCad.
- `Datasheets/`: Ce dossier contient les fiches techniques de tous les composants utilisés dans ce projet.
- `STM32/`: Ce dossier contient tous les fichiers de code relatifs aux capteurs, écrits pour la plate-forme STM32.

## Prérequis

Pour utiliser ce projet, vous devez avoir installé les outils suivants :

- KiCad (pour ouvrir et modifier les fichiers de projet et d'empreinte)
- Un environnement de développement STM32 (pour le code du capteur)

## Installation

1. Clonez ce dépôt sur votre machine locale.
2. Ouvrez les fichiers de projet KiCad dans `KICAD/`.
3. Consultez les fiches techniques dans `Datasheets/` pour comprendre le fonctionnement des composants.
4. Ouvrez et modifiez les fichiers de code du capteur dans `STM32/` selon vos besoins.

## Contribution

Les contributions à ce projet sont les bienvenues. 
