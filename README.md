Linky

Simulateur de compteur électronique type Linky

Ce programme Arduino permet de générer des trames de téléinfo type TIC sur des pins émulant une sortie série à 1200bauds.

Le programme permet d'avoir le choix entre un contrat BASE ou heures creuses/heures pleines HCHP ainsi que de la puissance souscrite. En cas de contrat HCHP le programme permet de simuler le basculement HP vers HC à un instant défini par une variable.

Une entrée analogique reçoit un signal entre 0 et 5V qui simule l'intensité instantanée appelée, cette intensité fait évoluer le ou les index et, en cas de dépassement de puissance souscrite, fait basculer l'indicateur ADPS
