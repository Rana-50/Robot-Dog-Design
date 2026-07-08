# Robot-Dog-Design

## 🏗️ Mechanical Design

### Frame

- Rectangular lightweight frame.
- Battery placed at the center.
- ESP32 or Arduino mounted inside the body.
- Even weight distribution for better stability.

### Legs

- Four identical legs.
- Each leg consists of:
  - Upper Leg
  - Lower Leg

### Degrees of Freedom (DOF)

Each leg includes:
- 1 Hip Joint
- 1 Knee Joint

Total:
- 2 DOF per leg
- 8 DOF for the robot

## ⚙️ Motor Selection

Servo Motors were selected because they provide:
- Accurate angle control
- Smooth walking motion
- Easy programming and control

## 📐 Torque Calculation

Assumptions:
- Leg mass = 0.5 kg
- Leg length = 0.2 m
- Gravity = 9.81 m/s²

Force:
F = m × g
= 0.5 × 9.81
= 4.905 N

Torque:
T = F × d
= 4.905 × 0.2
= 0.981 N·m

Required torque ~1 N·m

## ⚖️ Stability

- Center of gravity located near the middle of the robot.
- Battery placed at the bottom.
- Proper leg spacing improves balance during walking.

## 🚶 Walking Gait

Diagonal Walking Gait
Sequence:
1. Front Right + Rear Left
2. Front Left + Rear Right
This gait provides good balance and stability.

## ⚠️ Expected Challenges

- Uneven weight distribution
- Insufficient motor torque
- Joint friction
- Frame deformation under heavy loads
- Leg slippage
- High power consumption

## 🛠️ Future Improvements

- Add 3D CAD model.
- Perform dynamic simulation.
- Add sensors for autonomous navigation.
- Develop a real prototype using 3D printing.
