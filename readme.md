Aquí tens la fusió dels dos fitxers README en un de sol:

# LAB Optimització - Problema del Viatjant de Comerç (TSP) i Exercicis d'Optimització Heurística

## 📝 Descripció
Aquest repositori conté la implementació i comparació de diverses tècniques d'optimització per resoldre el problema del viatjant de comerç (TSP) i altres exercicis d'optimització heurística del curs IAAE de la UPC. Les tècniques utilitzades inclouen:

1. **Simulated Annealing** (SA)
2. **Algorismes Genètics** (GA)
3. **Gradient Descent**

## 📋 Contingut
- `Laboratori_Optimitzacio.ipynb`: Notebook principal amb implementacions dels algorismes, anàlisis comparatius i visualitzacions gràfiques.
- `data/`: Dades utilitzades en els exercicis.
  - `ciutats_15.csv`: Coordenades de les 15 ciutats per al TSP.
  - `distancias.csv`: Matriu de distàncies per al TSP.
  - `signal2.csv`: Dataset per a l'aproximació de senyal.
- `utils/`: Funcions auxiliars i eines per a gràfics.
  - `helpers.py`: Funcions auxiliars.
  - `visualization.py`: Eines per a gràfics.
- `/ex1_local_global/`: Solucions per a l'exercici 1.
- `/ex2-3_signal/`: Aproximació de senyal.
- `/ex4_parashooting/`: Optimització de llançament.
- `/ex5_giftcard/`: Problema de la targeta regal.
- `/ex6_containers/`: Optimització de contenidors.
- `/ex7_taxis/`: Assignació de taxis.
- `/ex8_custom_problem/`: Proposta de problema original.

## ⚙️ Configuració
```bash
# Requisits
Python 3.8+
Jupyter Lab

# Instal·lació de dependències
pip install numpy==1.21.5 matplotlib==3.5.1 jupyterlab==3.4.0 pandas==1.4.2 deap scipy tqdm==4.64.0
```

## 🚀 Execució
1. Obrir el notebook amb Jupyter Lab:
```bash
jupyter lab Laboratori_Optimitzacio.ipynb
```
2. Executar les cel·les seqüencialment.

## 📊 Resultats
Es compara el rendiment dels algorismes en:
- **Temps d'execució**
- **Qualitat de la solució**
- **Dificultat d'implementació**

Inclou gràfics interactius per a diferents mides del problema (5-100 ciutats).

## 🧪 Treball Addicional
- Implementació d'algorisme híbrid SA+GA.
- Anàlisi de sensibilitat als paràmetres.
- Proves amb fins a 100 ciutats.

## 👥 Autors
- Arnau Gonzalez Almirall
- German Bueno Lozano


