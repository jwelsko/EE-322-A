# EE 322 A README File - Design 6
## Engineering Design 6 at Stevens Institute of Technology

[Group Project](https://sites.google.com/stevens.edu/ee322-circuit-vanguard/home)

## About [Joseph Welsko](https://www.github.com/jwelsko)
> *Joseph Welsko is a junior Electrical Engineering Student with a concentration in Power Engineering graduating in spring 2026.*<br>
> *"The path to loving life starts with loving yourself." - Matthew Werner, 2025*
---

![Image of Joseph Welsko](https://media.licdn.com/dms/image/v2/D4E03AQHRzoTArei81g/profile-displayphoto-shrink_400_400/B4EZOrjK5mHkAk-/0/1733749944486?e=1743638400&v=beta&t=I_0jiHU8YCSkflioCin8hwWJSAyWgnHYfKmlxDwU-6Y)

## **Main Interests**
- **Microgrids:** Protecting power infrastructure.
- *Power Generation Systems:* Sustainable and affordable power.
- ***Critical Infrastructure Control Systems:*** Safeguarding infrastructure systems for the 21st century.

### Lists 
1. **Employment History** for sequential steps:
   1. Founder, CarbonDex
   2. Sales Engineer, Nodal Technologies
   3. Software Developer, Nodal Technologies
  
      
2. **Places I've Lived** for non-sequential items:
   - Maryland
   - New Jersey
   - Italy

## **Most Recent Code I Wrote**
```python
def _initialize_reservoir(self, pool_size, connection_probability):
   """Initialize the reservoir with sparse random connections"""
   weights = sparse.random(pool_size, pool_size, density=connection_probability)
   weights = weights.toarray()
   # Normalize weights to prevent explosion/vanishing
   spectral_radius = np.max(np.abs(np.linalg.eigvals(weights)))
   return weights / spectral_radius * 0.9
