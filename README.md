# LLM Evaluation Notebook

## Overview

This repository contains a Jupyter notebook (`llm_eval.ipynb`) that performs comprehensive performance benchmarking of large language models across different hardware configurations.

## What it does

The notebook compares the inference performance of DeepSeek-R1 models (70B and 32B variants) running on:
- **GPU**: A40 GPU (48GB VRAM)
- **CPU**: Contabo Server

### Key Features

- **Model Testing**: Evaluates deepseek-r1:70b and deepseek-r1:32b models
- **Performance Metrics**: Measures response time, words per second, tokens per second, and loading time
- **Hardware Comparison**: Direct GPU vs CPU performance analysis
- **Efficiency Analysis**: Performance per VRAM GB and memory utilization
- **Data Export**: Saves results to CSV files for further analysis

### Test Process

1. Loads models on each hardware configuration
2. Measures inference performance with standardized prompts
3. Collects detailed metrics including Ollama-specific performance data
4. Provides comprehensive analysis and recommendations

### Output

- Performance comparison tables
- Hardware efficiency rankings
- Use case recommendations (when to choose GPU vs CPU)
- Memory utilization analysis
- Exported CSV files with raw data and analysis summary

The notebook is designed for evaluating LLM deployment options and making informed decisions about hardware selection for different use cases.
