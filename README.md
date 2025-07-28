# Bloch Sphere Quantum Gate Simulator

An interactive 3D visualization tool for quantum computing education, featuring real-time simulation of quantum gates on the Bloch sphere.

## 🌐 Live Demo

[**Try the simulator here**](https://123hi123.github.io/bloch-sphere-simulator/bloch_sphere_orbit_controls.html)

## 🎯 Features

- **3D Visualization**: Interactive Bloch sphere with orbit controls
- **Quantum Gates**: Implementation of common single-qubit quantum gates
  - Pauli Gates: X, Y, Z
  - Hadamard Gate: H
  - Phase Gates: S, T
  - Rotation Gates: Rx(θ), Ry(θ), Rz(θ)
- **Real-time Animation**: Smooth transitions between quantum states
- **Interactive Controls**: 
  - Orbit controls for 3D navigation
  - Camera presets for quick views
  - Gate parameter adjustments
- **Educational Interface**: Clear labeling and coordinate system visualization

## 🛠️ Technologies

- **Three.js**: 3D graphics and rendering
- **OrbitControls**: Camera manipulation
- **Tween.js**: Smooth animations
- **Pure JavaScript**: No framework dependencies

## 📚 Quantum Gates Reference

| Gate | Matrix | Effect |
|------|--------|--------|
| X (NOT) | [[0,1],[1,0]] | 180° rotation around X-axis |
| Y | [[0,-i],[i,0]] | 180° rotation around Y-axis |
| Z | [[1,0],[0,-1]] | 180° rotation around Z-axis |
| H (Hadamard) | [[1,1],[1,-1]]/√2 | Creates superposition |
| S (Phase) | [[1,0],[0,i]] | 90° rotation around Z-axis |
| T | [[1,0],[0,e^(iπ/4)]] | 45° rotation around Z-axis |
| Rx(θ) | [[cos(θ/2),-i·sin(θ/2)],[-i·sin(θ/2),cos(θ/2)]] | Rotation around X-axis by angle θ |
| Ry(θ) | [[cos(θ/2),-sin(θ/2)],[sin(θ/2),cos(θ/2)]] | Rotation around Y-axis by angle θ |
| Rz(θ) | [[e^(-iθ/2),0],[0,e^(iθ/2)]] | Rotation around Z-axis by angle θ |

## 🎮 Usage

1. **Navigate the 3D view**: 
   - Left click + drag to rotate
   - Right click + drag to pan
   - Scroll to zoom
   
2. **Apply quantum gates**: Click on gate buttons to see their effect on the quantum state

3. **Adjust rotation angles**: Use the slider to set the rotation angle for Rx, Ry, Rz gates

4. **Camera presets**: Quick access to standard viewing angles

## 🚀 Local Development

```bash
# Clone the repository
git clone https://github.com/123hi123/bloch-sphere-simulator.git

# Navigate to project directory
cd bloch-sphere-simulator

# Open in browser (no build step required)
# Simply open bloch_sphere_orbit_controls.html in your web browser
```

## 📄 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👥 Author

- GitHub: [@123hi123](https://github.com/123hi123)