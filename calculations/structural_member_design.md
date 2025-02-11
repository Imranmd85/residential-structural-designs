# Structural Member Design Calculations

## 1. Beam Design Example

### Design Parameters
- Span: 20 feet
- Tributary width: 10 feet
- Total factored load: 2000 plf

### Moment Calculation
Maximum moment (M) = wL²/8
M = (2000 × 20²)/8 = 100,000 ft-lbs

### Required Beam Size
Using A36 steel (Fy = 36 ksi):
Required Section Modulus = M/(0.9 × Fy)
S = (100,000 × 12)/(0.9 × 36,000) = 37.0 in³
Select W16×40 (S = 39.0 in³)

## 2. Column Design

### Loading
- Dead load from roof: 15 psf × 200 sf = 3,000 lbs
- Live load from roof: 20 psf × 200 sf = 4,000 lbs
- Dead load from floor: 60 psf × 200 sf = 12,000 lbs
- Live load from floor: 40 psf × 200 sf = 8,000 lbs

### Load Combinations
1.2D + 1.6L = 1.2(15,000) + 1.6(12,000) = 37,200 lbs

### Column Selection
For 10 ft height:
Required area = P/(φFc)
A = 37,200/(0.9 × 36,000) = 1.15 in²
Select HSS 4×4×1/4

## 3. Foundation Design

### Footing Size Calculation
- Column load: 37,200 lbs
- Soil bearing capacity: 2,000 psf
- Required area = 37,200/2,000 = 18.6 sf
- Use 4.5' × 4.5' square footing

### Footing Thickness
- Based on one-way shear
- Minimum thickness = 12 inches
- Provide #5 bars @ 8" o.c. both ways