# 🌕 Red Moon Eclipse Simulation

An interactive 3D visualization of lunar eclipse phenomena with comprehensive physics equations and real-time calculations.

## 🎓 Academic Project

**Authors:** Brian Mwai (1050555) & Elizabeth Magara (1050037)
**Course:** PHY 401 - Quantum Physics II
**Institution:** Catholic University of Eastern Africa
**Lecturer:** Dr. James Sifuna

## ✨ Features

### 3D Visualization
- Interactive shadow cones (umbra and penumbra)
- Light ray trajectories demonstrating geometric optics
- Real-time eclipse phase calculations
- Orbital mechanics with 5.14° inclination
- Moon trail showing orbital path

### Physics Implementation
- **Shadow Formation:** Accurate umbra convergence and penumbra divergence
- **Rayleigh Scattering:** Wavelength-dependent scattering for Blood Moon effect
- **Kepler's Laws:** Circular orbit with inclination
- **Eclipse Phases:** P1, U1, U2, Greatest, U3, U4, P4 detection
- **Color Model:** RGB transitions based on shadow depth

### Educational Features
- Physics Equations Panel with all formulas and detailed explanations
- 3D Equation Labels displayed in viewport
- Real-time Calculations showing live updates of distances and radii
- Interactive Controls to toggle visibility of all elements

## 🔬 Key Equations

### Umbra Radius
The radius of the complete shadow decreases as distance increases, converging to an apex.

### Penumbra Radius
The radius of the partial shadow increases as distance increases, diverging outward.

### Rayleigh Scattering
Scattering cross-section is inversely proportional to the fourth power of wavelength. Blue light (450nm) scatters 4.2× more than red light (650nm), creating the Blood Moon effect.

## 🚀 Technology Stack

- **Three.js (r128)** - 3D rendering engine
- **WebGL** - GPU-accelerated graphics
- **HTML5 Canvas** - Graphics rendering
- **Vanilla JavaScript** - Physics calculations
- **Lucide Icons** - UI elements

## 🎮 Controls

### Playback
- Play/Pause simulation
- Step forward/backward
- Adjustable speed (0.1× to 10×)
- Reset to initial state

### Camera Views
- **Orbital** - Free rotation around the scene
- **Side View** - Eclipse cross-section view
- **Top View** - View from above the orbital plane
- **Moon View** - Perspective from the Moon

### Visualization Toggles
- Shadow Cones
- Light Rays
- Labels
- Equation Labels
- Moon Trail

## 📊 Physics Data Display

Real-time monitoring of:
- Eclipse phase (Total, Partial, Penumbral, None)
- Shadow percentage
- Moon-Earth distance
- Orbital angle
- Perpendicular distance from shadow axis
- Umbra radius at Moon's position
- Penumbra radius at Moon's position

## 🎯 Educational Value

This simulation demonstrates:
1. **Geometric Optics** - Light ray propagation and shadow formation
2. **Celestial Mechanics** - Orbital dynamics and Kepler's laws
3. **Wave Optics** - Wavelength-dependent scattering
4. **Computational Physics** - Real-time numerical calculations

## 📝 Validation

Shadow geometry validated through:
- Cross-sectional markers at multiple distances
- Umbral apex position matching theoretical predictions
- Penumbra divergence following equations
- Eclipse phase classification accuracy

## 🎨 Blood Moon Physics

During totality, the Moon displays a characteristic copper-red color due to Rayleigh scattering in Earth's atmosphere:
- **Red channel:** 85% (dominant)
- **Green channel:** 8%
- **Blue channel:** 3% (suppressed)
- **Red to Blue Ratio:** 28:1

This creates the characteristic copper-red glow observed during total lunar eclipses.

## 📚 References

Based on established astronomy and physics principles including:
- Meeus, J. (1998). Astronomical Algorithms
- NASA Eclipse Publications
- Rayleigh Scattering Theory
- Geometric Optics Principles

## 🔗 Links

- **GitHub Repository:** [brn-mwai/Red-Moon-Project](https://github.com/brn-mwai/Red-Moon-Project)
- **Live Demo:** Deployed on Vercel
- **Research Paper:** See research_paper.tex

## 📄 License

Academic project for educational purposes.

## 🙏 Acknowledgments

- Catholic University of Eastern Africa Physics Department
- Dr. James Sifuna (Course Lecturer)
- Three.js Development Team
- NASA Eclipse Resources

---

🤖 Simulation developed with Claude Code
