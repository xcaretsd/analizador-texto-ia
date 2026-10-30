# Analizador de Sentimientos con IA (Python)

## Descripción
Script en Python que utiliza la librería `TextBlob` (Procesamiento de Lenguaje Natural) para analizar la polaridad y subjetividad de una frase, determinando si el sentimiento es positivo, negativo o neutral.

## Tecnologías Utilizadas
* Python 3
* TextBlob (NLP)

## ¿Cómo ejecutarlo localmente?
1. Clona este repositorio.
2. Crea un entorno virtual: `python3 -m venv .venv`
3. Actívalo: `source .venv/bin/activate` (en Mac/Linux) o `.venv\Scripts\activate` (en Windows).
4. Instala las dependencias: `pip install textblob`
5. Ejecuta el script: `python main.py`

## ¿Cómo funciona?
El algoritmo analiza las palabras de la oración asignándoles un valor numérico. La suma de estos valores determina la polaridad (de -1 a 1) y la subjetividad (de 0 a 1).
