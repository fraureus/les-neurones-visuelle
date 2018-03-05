## Neural Network Visualization using ThreeJS

- Supervised Neural Network with BP
- Supervised Neural Network with Random Weights & Moore-Penrose Inverse

## Components
### Modelling
- Nodes (neurons)
- Vertices (synaptic connections)
- Weights ('LTM traces' or parameters)

### Camera
- Perspective projection (PerspectiveCamera)

### Lighting
- Ambient lighting

### Animation
- Forward propagation (light up layer being computed)
- Back propagation (light up layer being computed)
- Neural network prediction
- Weight updates
- Addition of nodes

### Shader
- PhongShader

### Interactivity
- Neural network configuration 
	- Number of hidden layers
	- Number of nodes
	- Learning parameter
	- Type of hidden nodes
	- Number of iterations
- Simulation controls
	- Start/pause/stop/reset training
	- Simulation speed
- Camera controls
	- Free movement