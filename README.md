# AI-Powered Fashion & Fabric Matcher
Final project for the Building AI course

## Summary
An AI system designed for local fashion brands and e-commerce stores that automatically recommends the best clothing designs, fabric types, and patterns based on seasonal weather data and regional consumer preferences.

## Background
* **Problem:** Small clothing brands often struggle to predict which fabric types (like breathable cotton for summer) and clothing sets will trend in specific regions, leading to unsold inventory.
* **Frequency:** This is a highly frequent challenge for emerging e-commerce and local apparel start-ups.
* **Motivation:** My personal motivation stems from an interest in fashion design, brand development, and online retail optimization, aiming to reduce fashion waste and boost local businesses.

## How is it used?
The solution is integrated directly into the backend of an e-commerce platform (like Shopify). When a designer wants to launch a new summer clothing line or product set, the AI analyzes regional demand and suggests optimal fabric choices and design sets.
* **Users:** Independent fashion designers and e-commerce store owners.
* **Environment:** Used during the product design and inventory planning phases before production begins.

## Data sources and AI methods
* **Data Sources:** Open-source fashion trend datasets, regional weather history datasets, and public social media trend hashtags.
* **AI Methods:** K-nearest neighbors (KNN) for finding similar historic successful clothing trends, and Logistic Regression to predict the probability of a specific clothing design becoming popular.

## Challenges
* The project does not manufacture clothes or design them from scratch; it only provides style, fabric, and inventory recommendations.
* It requires continuous data updates to stay aligned with fast-moving fashion cycles.

## What next?
The project could grow to include an AI computer vision tool that automatically scans fabrics through a smartphone camera and identifies their quality and composition, making it a complete assistant for clothing manufacturers.

## Acknowledgments
* Inspired by the Elements of AI / Building AI course curriculum.
* Built using open data concepts from the University of Helsinki.
