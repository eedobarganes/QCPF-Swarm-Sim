# QCPF-Swarm-Sim
QCPF Swarm Simulator - A visually engaging Python simulation inspired by gamete (sperm-like) agents navigating a dynamic environment filled with food sources and moving hazards.

This project models basic concepts from the Quantum Consciousness Projection Framework (QCPF, where agents can transition between "zombie" (unconscious, random) behavior and "conscious" (intentional, focused) states based on a computed Φ (phi) value—representing integrated information quality.

Agents sense their surroundings, integrate sensory data with noise, and act accordingly: conscious agents pursue food aggressively, avoid hazards with urgency, and exhibit focused movement, while unconscious ones wander aimlessly. The simulation includes realistic tail physics for a gamete aesthetic, energy metabolism, boundary wrapping, and respawning mechanics to maintain population.
Features

Agent Behavior:
Sensory detection of food and hazards within a configurable range.
Φ calculation based on input strength, integration quality, and noise.
Consciousness threshold: Agents turn gold and gain intentional focus when Φ exceeds the threshold; otherwise, they remain blue "zombies."

Environment Dynamics:
Moving hazards that bounce off walls and kill agents on contact.
Food pellets that respawn randomly and restore agent energy.
Agent energy depletion over time, influenced by consciousness (higher focus burns more energy).

GUI Controls:
Sliders to adjust Φ threshold, intentional focus, and environmental noise in real-time.
Live histograms: Distribution of current Φ values (with consciousness indicator) and historical ages at death.
Legend for visual elements (food, hazards, conscious agents).

Visuals:
Tkinter canvas for rendering the simulation.
Tapered tails on agents for a organic, swimming gamete effect.
Pulsing hazards and energy bars on agents.
