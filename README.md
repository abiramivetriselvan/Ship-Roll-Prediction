I developed a hybrid PINN-LSTM framework for ship roll motion prediction using MATLAB-generated datasets derived from four nonlinear ship-roll equations representing different sea conditions.

1. θ¨ + b1θ˙ + k1θ + k3θ³ + k5θ⁵ = 0
   (calm sea / natural roll decay)

2. θ¨ + b1θ˙ + k1θ + k3θ³ + k5θ⁵ = Fcos(ωt)
   (wave-excited sea condition)

3. θ¨ + (2b1 + b2θ²)θ˙ + ω0²θ + k3θ³ = 0
   (nonlinear viscous damping)

4. θ¨ + (2b1 + b2θ²)θ˙ + ω0²θ + k3θ³ = Fcos(ωt)
   (severe nonlinear wave-induced motion)

These datasets represent progressively complex ship-roll behaviors ranging from calm-water decay to highly nonlinear wave-induced dynamics.
