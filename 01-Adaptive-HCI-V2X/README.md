# Reinforcement Learning-Based Adaptive Human–Computer Interaction for V2X-Assisted Autonomous Vehicle Obstacle Avoidance

## Publication Information

**Author:** Yisong Zhao<br>
**Journal:** *Tehnički vjesnik – Technical Gazette* (SCI-indexed)<br>
**Status:** Revised after peer review · Review finished · Post-review processing

**Research Areas:** `Adaptive HCI` · `Reinforcement Learning` · `Multimodal Interaction` · `Autonomous Vehicles` · `V2X`

## Research Overview

This study examines adaptive human–computer interaction for V2X-assisted autonomous driving. It proposes a decision framework in which an interface responds to estimated driver state, vehicle dynamics, traffic risk and the reliability of V2V/V2X communication rather than delivering the same warning in every situation.

## Research Problem

Fixed warning policies cannot account for variation in driving context, estimated driver condition or communication reliability. The research therefore considers how an adaptive policy can select an appropriate warning intensity while supporting obstacle avoidance and managing simulated reaction-time and workload outputs.

## Methodology / System Design

The system represents the combined driving context as a 12-dimensional state. A Proximal Policy Optimisation (PPO) actor–critic agent uses this representation to select one of three interface actions: no alert, weak alert or strong alert. Alerts are delivered through visual, auditory and haptic modalities.

The study is a simulation-based proof of concept. Its driver-related outputs are simulated or model-estimated; they are not measurements collected from human participants.

## Research Framework

```text
Driver State + Vehicle State + Traffic Risk + V2X Reliability
                              ↓
              12-dimensional State Representation
                              ↓
                   PPO Actor–Critic Agent
                              ↓
                     Adaptive HCI Policy
                              ↓
             No Alert / Weak Alert / Strong Alert
                              ↓
             Visual + Auditory + Haptic Feedback
```

## Evaluation

The adaptive policy is evaluated within the simulation framework against a fixed reference policy under the tested V2X conditions. The comparison considers obstacle-avoidance performance together with simulated reaction-time outputs and model-estimated workload values.

## Key Findings

Within the tested simulation, the adaptive interface produced lower simulated reaction-time outputs and model-estimated workload values than the fixed reference policy while maintaining stronger obstacle-avoidance performance.

> These findings are simulation-based proof-of-concept results and should not be interpreted as validated effects in real drivers.

## Technologies / Methods

- Proximal Policy Optimisation (PPO)
- Actor–critic reinforcement learning
- Adaptive multimodal warning policies
- V2V/V2X communication conditions
- Simulation-based evaluation

## Citation

Final bibliographic information and a public paper link will be added after publication details are confirmed. The manuscript must not be cited as published or accepted at its current stage.

[Back to Research & Publications](../README.md)
