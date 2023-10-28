# Vehicle Detection Project

![Project Demo](demo.png)

This project aims to perform real-time vehicle and pedestrian detection using computer vision techniques. It uses Haar cascades for vehicle and pedestrian detection. The goal is to detect and count the number of vehicles and pedestrians in a video stream. This README provides an overview of the project and instructions for running it.

## Table of Contents

- [Demo](#demo)
- [Description](#description)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## Demo

Watch the project in action on YouTube: [Project Demo](https://youtu.be/bTIKY2NYBUg)

![Demo](demo.png)

## Description

The project uses Haar cascades for vehicle and pedestrian detection. It processes video input, identifies vehicles and pedestrians, and draws bounding boxes around them. The counts of vehicles and pedestrians are displayed in real-time. The project is designed to work with different video sources and can be used for various applications, such as traffic monitoring or surveillance.

## Features

- Real-time vehicle and pedestrian detection.
- Vehicle and pedestrian count tracking.
- Adjustable detection parameters.
- Compatibility with various video sources.
- Easy-to-use Python script.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python: You should have Python installed on your system.

## Installation

To install the required libraries, run the following command:

```bash
pip install opencv-python numpy
