# Stack-Farm

Early plant-disease detection from a single leaf photo, made simple for farmers.

**Live demo:** https://irfansirkar.github.io/stack-farm/

Built by **Mohammad Irfan Sirkar** for **a 2024 hackathon**.

## What the project does

A farmer or field agent photographs one leaf. Stack-Farm cleans up the image, runs a CNN to name the disease and its confidence, and shows three plain next steps. The interface uses large buttons and few words so it works for first-time smartphone users.

## Original stack

- TensorFlow (CNN classifier)
- Image processing for crop, lighting and resize
- Streamlit

## About this repository

This repository holds an interactive demo of the project. The demo runs entirely in the browser on GitHub Pages and uses built-in sample data, so it never needs a server, a GPU or an API key.

The demo has 4 drawn sample leaves: tomato early blight, potato late blight, maize common rust and a healthy leaf. The results are pre-computed. The interface switches between English, Hindi and Telugu.

The original project code is not included here.

## Run the demo locally

Open `index.html` in any browser. There is no build step.

## More projects

See the full portfolio at https://irfansirkar.github.io/PERSONAL-PORFOLIO-WEBSITE/
