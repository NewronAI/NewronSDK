<div align = "center"><img src = "https://www.newron.ai/newron-logo.svg" width=25% /></div>
<h1 align="center">
  NewronSDK - A Client for Newron.
</h1>
<br>

## Machine learning experiment tracking, model versioning, and model evaluation
Newron is a machine learning platform for individuals and teams, designed for simplicity, speed and collaboration, built to integrate with your favourite machine learning frameworks.
We provide a frictionless machine learning development experience to take care of the hard things: automatically track experiments, version models, reproduce models, visualize results and share findings within your the team or the broader ML community
It is easy to set up and enables ML engineers to develop, improve and deploy machine learning models with confidence and ease.

## Installation 

### From PyPi

```bash
pip install newron
```

### From Conda

```bash
conda install newron
```

### Development Version
```bash
pip install git+https://github.com/NewronAI/NewronSDK
```

## Usage 
```python
import newron
newron.init("experimentName", "projectName", "Description")
```