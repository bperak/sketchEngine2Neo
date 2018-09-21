# sketchEngine2Neo
This repository contains scripts for extraction of the WordSketches form the SketchEngine using the SketchEngine API and store data about word behavior into a Neo4j graph database as Lemma Nodes with frequency and similarity properties.

Available WordSketch Corpus Scripts:
CROATIAN WEB (HRWAC 2.2, RELDI),ENGLISH WEB 2013 (ENTENTEN13), ITALIAN WEB 2016 (ITTENTEN16)

#Requirements
Neo4j graph database
Python package py2neo v=4 

#Instalation
1) Register at the https://www.sketchengine.eu/
2) Obtain the Sketch Engine API key and User details at the My Account https://app.sketchengine.eu/#dashboard 
3) Edit sketchAuthentication.txt
4) Install and start Neo4j graph database
5) Edit neo4jAuthentication.txt
6) Install py2neo (pip install py2neo)

#Getting the WordSketches Usage
1) start dedicated Neo4j graph database
2) start any of the WordSketchMining scripts
3) set word and POS 


