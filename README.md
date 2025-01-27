# ASCII Particle System for Coffee

This is a fun project that simulates a particle system for a hot cup of coffee. The particle effect can be toggled between two options: **steam** and **fire**.

The particle densities are generated as a normal distribution to create a realistic effect.

## Features:
- **Steam Effect**: Simulates steam rising from your hot coffee.
- **Fire Effect**: Simulates a more intense, fiery particle effect.

## Installation:
1. Clone or download the repository.
2. Make sure you have Go installed.

## Usage:
Run the project with the `--effect` flag to choose between the two effects. The default is "steam".

```bash
go run main.go --effect steam
```
To run the fire effect:
```bash
go run main.go --effect fire
```

Feel free to experiment with the particle system parameters in `main.go`.

### Enjoy your coffee! ☕
