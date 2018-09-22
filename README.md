# sketchEngine2Neo
This repository contains scripts for extraction of the WordSketches from the SketchEngine using the SketchEngine API. The node and collocation properties are stored into a Neo4j graph database as Lemma Nodes and Relationships.

Available WordSketch Corpus Scripts:
1. CROATIAN WEB (HRWAC 2.2, RELDI) 
2. ENGLISH WEB 2013 (ENTENTEN13)
3. ITALIAN WEB 2016 (ITTENTEN16)

#Requirements
1. Neo4j graph database
2. Python 3x
3. Python package py2neo v=4 

#Instalation
1. Download sketchEngine2Neo repository
2. Register at the https://www.sketchengine.eu/
3. Obtain the Sketch Engine API key and User details at the My Account https://app.sketchengine.eu/#dashboard 
4. Edit sketchAuthentication.txt and modify authentification keys (In the sketchEngine2Neo Repository)
5. Install and start Neo4j graph database
6. Edit neo4jAuthentication.txt and modify authentification keys  (In the sketchEngine2Neo Repository)
7. Install python 3x
8. Install py2neo (python package for programatic communication with the database: pip install py2neo)

#Getting the WordSketches Usage
1. start dedicated Neo4j graph database
2. start  the WordSketchMining_hrWac.py, or any other script
3. set the word and POS
4. query the database for results


