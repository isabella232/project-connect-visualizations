---
title: Home
date: 2012-08-20
layout: post.html
permalink: /
---

Project Connect is a mission under UNICEF Innovation Office. We're applying deep learning and computer vision to assist the mission to put every school in the world on the map.

# Mapping schools in Africa, Asia and South America

We applied AI-assisted school mapping workflow to search map schools in Kenya, Rwanda, Sierra Leone, Niger, Ghana, Kazakhstan, Uzbekisthan and Honduras. 

# Schools maps visualization

The schools map visualizations presented shown the comparison between the schools validated for training data and the results from ML outputs validation.

In the maps for each country We can see:

- Color green: Known schools are the validated schools from sources OSM and (or) UNICEF.
- Color yellow: Unmapped schools that predicted by ML models and confirmed by expert mappers that have clear school features/patterns, but currently are not on the map yet.
- Color bright blue: Reconfirmed schools are schools that correctly detected by ML models and overlapped with known schools.
- Color red: School training data were the schools used to train regional, country and global ML models.

###  School Maps from Object Detection v.s. Classification in Kenya

This visualization is for comparing the results from the Object Detection model and the Classification model in Kenya.

In this map for Kenya We can see:

- Color orange: Unmapped schools that predicted the Object Detection ML model and confirmed by expert mappers that have clear school features/patterns, but currently are not on the map yet.
- Color dark blue: Reconfirmed schools are schools that correctly detected by Object Detection ML model and overlapped with known schools.
- Color yellow: Unmapped schools that predicted by Classification ML model and confirmed by expert mappers that have clear school features/patterns, but currently are not on the map yet.
- Color bright blue: Reconfirmed schools are schools that correctly detected by Classification ML model and overlapped with known schools.
- Color red: School training data were the schools used to train regional, country and global ML models.
