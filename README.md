# Traffic Light Controller with Pedestrian Mode (Verilog HDL)

A Traffic Light Controller system developed using **Verilog HDL**. The project controls traffic signals for two roads and also includes a pedestrian crossing mode using a Finite State Machine (FSM).

##  Features

* Controls traffic lights for Road A and Road B.
* Includes pedestrian crossing support.
* Uses FSM (Finite State Machine) for state control.
* Prevents both roads from getting green signals at the same time.
* Stores pedestrian button requests to avoid missing signals.
* Uses timer-based signal switching for safe traffic flow.

---

# 🚦 Traffic Signal States

The system works using 5 states:

1. **A_G**

   * Road A = Green
   * Road B = Red

2. **A_Y**

   * Road A = Yellow
   * Road B = Red

3. **B_G**

   * Road B = Green
   * Road A = Red

4. **B_Y**

   * Road B = Yellow
   * Road A = Red

5. **PED**

   * Both roads = Red
   * Pedestrian signal = Green

---

# 🛠️ Technologies Used

* Verilog HDL
* Finite State Machine (FSM)
* Digital Logic Design

---

# 📂 Project Structure

```text id="m4t7xq"
ComputerArchitectureCodeFiles/
├── traffic_light_controller.v
├── testbench.v

```

---

# ▶️ Project Purpose

This project demonstrates how digital systems and FSM logic can be used to control real-world traffic intersections safely and efficiently.
