# Industrial Control System Project

This repository contains the final project for the Industrial Control Systems course. The project involves modeling, analyzing, and designing control systems, with a focus on PID controllers. Below, you'll find an overview of the tasks performed and the methodologies used.

## Project Overview

### 1. System Identification
- **Three-Component Model**: Identified using close points to approximate the slope and derive the equation of the line.
- **Four-Component Model**: Identified similarly by calculating parameters from the step response.

### 2. Step Response Comparison
- Compared the step responses of the identified models with the original system to evaluate accuracy.

### 3. Feedback Relay Method
- Obtained endpoint information of the system using the feedback relay method.
- Simultaneously plotted the input-output response of the system and analyzed the results.

### 4. PID Controller Design
Designed a closed-loop PID controller based on the following methodologies and compared the results:

#### a. Ziegler-Nichols Method in Time Domain
- Designed a PID controller using the Ziegler-Nichols method in the time domain.
- Tuned the controller parameters for an appropriate response through trial and error.

#### b. Ziegler-Nichols Method in Frequency Domain
- Designed a PID controller using the Ziegler-Nichols method in the frequency domain.
- Tuned the controller parameters for an appropriate response through trial and error.

#### c. Generalized Ziegler-Nichols Method
- Designed a PID controller using the generalized Ziegler-Nichols method.
- Tuned the controller parameters for an appropriate response through trial and error.

#### d. Lambda Tuning Method
- Designed a PID controller using the Lambda tuning method.
- Tuned the controller parameters for an appropriate response through trial and error.

### 5. Smith Predictor with PID Controller
- Implemented a Smith Predictor along with the PID controller designed in step 4.
- Evaluated the system response in two scenarios:
  - a. Complete system dynamics are known.
  - b. Using the model from step 4.

## Requirements

- MATLAB R2020a or later
- Control System Toolbox
- Simulink

