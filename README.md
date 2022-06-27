# 2_Axis_Inverted_Pendulum

Continuation of my senior capstone project. The original project ended in moderate success.

The original project: 

    Had a working chassis

    Had working power, motors, wiring

    Utilized LQR controls
  
    Had semi-working controls integration uploaded to an Arduino

The new project will:

    Have a working chassis
  
    Have working power, motors, wiring
  
    Utilize LQR controls with and without a Kalman Filter 
  
    Utilize ML to control the system
  
    Be able to switch between the two systems as well as configure the K values for the LQR controls with an RPi
  
    Integrate the controls with the motors/electronics using an Arduino
  
    Be able to interface the RPi with the Arduino

Preliminary design choices:

Chassis
    
    Corexy from kit

Power

    From capstone, need to fill in    

Motors

    From capstone, need to fill in

Wiring

    From capstone, need to fill in 

    Silicone wires, soldered togther

LQR

    From capstone

ML

    Need to learn

Code integration

    Option 1: 
    Inputs connected to RPi, outputs connected to Arduino. RPi runs code to calculate accelerations based on controls, those accelerations are pushed to Arduino which actuates the motors

    Option 2: 
    All inputs and outputs connected to RPi, no Arduino

    Option 3:
    All inputs and outputs connected to Arduino, RPi simply controls UI and selecting control method

RPi
    
    Pinout
    
    How to program code

    How to program gui

    Implement LQR

    Implement LQR + Kalman Filter

    Implement NN
    
    For option 1:

    How to send Accelerations to Arduino 

    Accelerations calculated by RPi and pushed to the Arduino are accurate to the LQR/ML models

    Latency b/t RPi and Arduino is fine
    
    For option 2:

    Latency/Update Frequency is fine

Arduino

    Pinout

    Option 1:

    Able to read accelerations from RPi and can actuate motors with low latency
    
    Option 3:
    
    Implement LQR

    Implement LQR + Kalman Filter

    Implement NN





    
    

