# 2026 Project 08 — Vision AI Lab

## Purpose

This project is part of the `AI-Engineering-Lab` learning roadmap.

It introduces computer vision foundations for AI engineering. The goal is to understand how images become tensors, how visual models make predictions, and how to evaluate visual errors.

This project should remain focused on fundamentals before moving to multimodal assistants.

## Why this project exists

Many AI systems do not work only with text. They also need to process images from cameras, screenshots, documents, interfaces, or sensors.

The basic vision pipeline is:

```text
image
  ↓
loading
  ↓
preprocessing
  ↓
tensor
  ↓
model
  ↓
prediction
  ↓
metric
  ↓
error analysis
```

This project builds the visual foundation needed for multimodal and robotics projects.

## Learning focus

This project focuses on:

- image loading;
- image tensors;
- preprocessing;
- classification;
- object detection foundations;
- metrics;
- dataset quality;
- error analysis;
- visual failure modes.

## Minimal milestone

Load a small image dataset, inspect image shapes, and run a baseline classification experiment.

## Final deliverable

A small vision experiment with:

- image loading;
- preprocessing;
- a simple classification or detection baseline;
- metrics;
- visual inspection of errors;
- notes on dataset quality.

## Repository structure

Recommended structure:

```text
data/             sample images or dataset notes
notebooks/        exploratory vision notebooks
notes/            image tensor and metric concepts
src/loading/      image loading utilities
src/models/       baseline model code
src/evaluation/   metrics and error analysis
experiments/      result summaries
MENTORING.md      guided exercises and validation checklist
learning_log.md   session-by-session observations
```

## Success criteria

By the end of this project, I should be able to explain:

- how an image is represented as a tensor;
- what preprocessing changes;
- what classification predicts;
- what object detection adds;
- which metrics are useful;
- how to inspect visual errors instead of trusting aggregate scores only.

## Relation to the next project

This project prepares `2026_project_09--multimodal_assistant`.

Once images are understood as model inputs, they can be combined with text and audio in an assistant workflow.
