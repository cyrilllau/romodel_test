# Facility Location Optimization

This project implements a facility location optimization model using Pyomo and Romodel.

## Setup Instructions

1. Create a new Python virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- On macOS/Linux:
```bash
source venv/bin/activate
```
- On Windows:
```bash
.\venv\Scripts\activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Model

To run the facility location model:
```bash
python romodel/examples/facility.py
```

## Model Description

The model solves a facility location problem with:
- N facilities
- M demand points
- Uncertain demand parameters
- Facility opening costs
- Transportation costs
- Capacity constraints
