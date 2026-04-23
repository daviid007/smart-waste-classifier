# Smart Waste Classifier

Building AI course project

## Summary

An AI-powered application that uses a camera to automatically recognize and classify waste into categories (plastic, paper, glass, metal, organic). The goal is to make waste sorting easier and more accurate for everyday users.

## Background

Incorrect waste sorting is a widespread problem that reduces recycling efficiency and increases environmental impact. Many people are unsure which bin to use for specific items. This problem occurs daily in millions of households worldwide.

* People often don't know how to sort specific items
* Incorrectly sorted waste ends up in landfills instead of being recycled
* Better sorting = less environmental pollution

My motivation is to make recycling simple and accessible for everyone, regardless of their knowledge of local sorting rules.

## How is it used?

The user points their smartphone camera at a piece of waste. The AI model analyzes the image and tells them which bin to use. The app can also show local sorting rules based on the user's location.

Users: households, schools, offices, public spaces.

![Waste sorting](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Waste_separation.jpg/640px-Waste_separation.jpg)

## Data sources and AI methods

| Component | Details |
| --------- | ------- |
| Data | TrashNet dataset (open source, ~2500 images) |
| AI method | Convolutional Neural Network (CNN) for image classification |
| Framework | TensorFlow / Keras |

[TrashNet Dataset](https://github.com/garythung/trashnet)

## Challenges

* The model may struggle with unusual or mixed-material items
* Sorting rules differ between cities and countries
* Requires good lighting for accurate recognition
* Does not solve the underlying issue of excessive waste production

## What next?

* Add support for local sorting rules by municipality
* Expand the dataset with more waste categories
* Develop a mobile app (iOS/Android)
* Partner with municipalities to promote sustainable behavior

## Acknowledgments

* [TrashNet by Gary Thung and Mindy Yang](https://github.com/garythung/trashnet) / MIT License
* Inspired by the potential of computer vision to solve everyday environmental problems
