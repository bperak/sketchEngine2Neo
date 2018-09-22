# sketchEngine2Neo
This repository contains scripts for extraction of the WordSketches form the SketchEngine using the SketchEngine API and store data about word behavior into a Neo4j graph database as Lemma Nodes with frequency and similarity properties.

Available WordSketch Corpus Scripts:
CROATIAN WEB (HRWAC 2.2, RELDI),ENGLISH WEB 2013 (ENTENTEN13), ITALIAN WEB 2016 (ITTENTEN16)

#Requirements
Neo4j graph database
Python package py2neo v=4 

#Instalation
0) Download sketchEngine2Neo repository
1) Register at the https://www.sketchengine.eu/
2) Obtain the Sketch Engine API key and User details at the My Account https://app.sketchengine.eu/#dashboard 
3) Edit sketchAuthentication.txt and modify authentification keys (In the sketchEngine2Neo Repository)
4) Install and start Neo4j graph database
5) Edit neo4jAuthentication.txt and modify authentification keys  (In the sketchEngine2Neo Repository)
6) Install python 3x
7) Install py2neo (python package for programatic communication with the database: pip install py2neo)

#Getting the WordSketches Usage
1) start dedicated Neo4j graph database
2) start  the WordSketchMining_hrWac.py, or any other script
3) set the word and POS
4) query the database for results


