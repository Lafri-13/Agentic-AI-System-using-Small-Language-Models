# Agentic-AI-System-using-Small-Language-Models

Agentic AI system using Small Language Models (LLaMA 3B) with LoRA, quantization, and knowledge distillation for business process automation tasks.
Individual Research Project 

## Overview

This project presents an efficient agentic AI system built using Small Language Models (SLMs) for business process automation.

The system supports:

- Invoice Extraction  
- Form Understanding  
- Email Analysis  
- Meeting Summarization  

## Key Technologies

- LLaMA 3.2 3B  
- 4-bit Quantization  
- LoRA (Parameter-Efficient Fine-Tuning)  
- Knowledge Distillation  
- Hybrid Task Routing  

## Architecture

Input → Routing → Task-Specific Adapter → Structured Output (JSON)

## Results

- Overall BERTScore: 90.15%  
- Email: 92.14%  
- FUNSD: 85.41%  
- SROIE: 85.67%  
- AMI: 83.73%  

## Repository Structure

- `preprocessing/` → Data preparation and distillation  
- `training/` → Training, testing, and orchestration  

## Data and Models

Datasets and trained model weights are not included due to:

- Size limitations  
- Licensing restrictions  

Datasets used:
- AMI  
- Enron  
- FUNSD  
- SROIE  

## Future Improvements

- Add more task adapters  
- Improve routing with machine learning-based classifiers  
- Optimize for edge and mobile deployment  
- Support multimodal inputs  

## Author

Lafri Larsheeth  
Final Year Undergraduate – BSc (Hons) Artificial Intelligence and Data Science  

- GitHub: https://github.com/Lafri-13 
- LinkedIn: www.linkedin.com/in/lafri-larsheeth-077414252

## License

This project is licensed under the MIT License.
