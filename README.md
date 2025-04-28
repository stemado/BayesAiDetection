# Base Rate Impact on AI Detection Tool Performance

## Overview

This interactive visualization demonstrates the crucial impact of base rate (prevalence) on the reliability of AI detection tools in academic settings. It provides a statistical foundation for the "Academic Integrity in the Loop" framework, showing why human judgment remains essential when implementing AI detection technologies.

## Purpose

Many institutions are deploying AI detection tools to identify AI-generated content in student submissions, but often without accounting for the statistical impacts of base rate. This visualization makes these complex Bayesian statistics accessible and immediately understandable through interactive exploration.

## Key Concepts Demonstrated

- **Base Rate Effect**: How the prevalence of AI use in a specific context dramatically affects the reliability of detection results
- **Positive Predictive Value (PPV)**: The probability that content flagged as AI-generated is actually AI-generated
- **Negative Predictive Value (NPV)**: The probability that content flagged as human-written is actually human-written
- **False Positives**: The number of innocent students incorrectly flagged as using AI
- **Confidence Threshold**: The 95% reliability threshold needed for automated detection systems

## Features

- **Interactive Controls**: Adjust base rate, sensitivity, specificity, and student population size
- **Dynamic Visualization**: See immediate updates to the reliability metrics and impact assessment
- **Visual Impact Display**: Intuitive representation of false positive proportions
- **Key Metrics**: Clear display of essential statistical measures
- **Contextual Insights**: Automatic generation of recommendations based on current settings

## How to Use

1. Use the sliders to adjust:
   - **Base Rate**: The percentage of students in your context using AI
   - **Sensitivity**: The tool's ability to detect AI-generated content
   - **Specificity**: The tool's ability to correctly identify human-written content
   - **Number of Students**: The total population size

2. Observe how changes affect:
   - The curve showing PPV across different base rates
   - The metrics showing reliability values
   - The impact visualization showing false positive proportions
   - The recommendations for human involvement

## Key Insights

- Even with 99% sensitivity and specificity, AI detection tools become unreliable at low base rates
- When the base rate is below 10%, human judgment becomes essential in the review process
- NPV remains consistently high regardless of base rate, while PPV varies dramatically
- In contexts where few students use AI, automated accusations will contain a high proportion of false positives

## Technical Implementation

This visualization is built using:
- HTML, CSS, and JavaScript
- Chart.js for data visualization
- Bayesian statistical analysis for calculations

## Usage in Educational Settings

This tool is ideal for:
- Faculty development sessions on academic integrity
- Institutional policy discussions about AI detection tools
- Student education about AI detection and academic integrity
- Administrative decision-making about AI use policies

## Installation

Simply open the `bayes_ai_detection.html` file in any modern web browser. No server or installation required.

## Credits

Developed as part of the "Academic Integrity in the Loop" framework for creating fair and statistically sound approaches to AI detection in educational settings.
