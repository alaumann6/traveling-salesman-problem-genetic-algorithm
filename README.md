# Traveling Salesman Problem Lösung mit Genetischem Algorithmus

Dieses Projekt implementiert einen **Genetischen Algorithmus (GA)** zur Lösung des **Traveling Salesman Problem (TSP)**. Das TSP fragt: Gegeben eine Menge von Städten, wie findet man die **kürzeste Route**, die jede Stadt **genau einmal besucht** und zum Startpunkt zurückkehrt? Dieses Projekt zeigt, wie **evolutionäre Algorithmen** nahe optimale Lösungen für kombinatorische Optimierungsprobleme finden können, bei denen exakte Methoden zu rechenintensiv werden.

## Funktionen
- Lösung des TSP für beliebige 2D-Koordinaten  
- Verwendet **Turnier-Selektion**, **Ordered Crossover** und **Swap-Mutation**  
- Verfolgt die **beste Lösung pro Generation**  
- Konfigurierbare GA-Parameter: Populationsgröße, Mutationsrate, Anzahl der Generationen  
- Erweiterbar zur **Visualisierung der Route** mit `matplotlib`  

## Installation
Python 3.x erforderlich. Optional für Visualisierung:
```bash
pip install matplotlib
```
