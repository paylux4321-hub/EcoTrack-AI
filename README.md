# EcoTrack-AI
AI project to monitor and reduce environmental footprint

```python
def calculate_footprint(electricity_kwh, water_liters, waste_kg):
    # Sample function to calculate environmental impact
    footprint = electricity_kwh*0.233 + water_liters*0.001 + waste_kg*2.0
    return footprint

score = calculate_footprint(350, 1200, 15)
print(f"Your environmental footprint score: {score:.2f}")
