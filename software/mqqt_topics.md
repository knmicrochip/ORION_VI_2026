Topic names:


Publishers ESP:  
 - Suspension_Left_enc  
 - Suspension_Right_enc  
 - Robotic_arm_enc  
 - Power_control_enc  
 - Vacuum_enc  
 - Science_enc  

Subcribers ESP:  
 - Propulsion_cmd  
 - Robotic_arm_cmd  
 - Power_control_cmd  
 - Vacuum_cmd  
 - Science_cmd  
 - Light_cmd  

IP adresses:
- Suspension_left: 192.168.1.51
- Suspension_Right: 192.168.1.52
- Robotic_Arm: 192.168.1.53
- Vacuum : 192.168.1.54
- Science: 192.168.1.55
- Power: 192.168.1.56



{
 "eventType": "Propulsion_cmd",        // chassis telemetry unique firmware identifier
 "payload": {
    "fl_rad": "<<float32>>",    // front-left angular position in rad 
    "fr_rad": "<<float32>>",    // front-right angular position in rad 
    "rl_rad": "<<float32>>",    // rear-left angular position in rad 
    "rr_rad": "<<float32>>",    // rear-right  angular position in rad 
    "fl_speed": "<<float32>>",      // front-left wheel speed in range [0, 40]
    "fr_speed": "<<float32>>",      // front-right wheel speed in range [0, 40]
    "rl_speed": "<<float32>>",      // rear-left wheel speed in range [0, 40]
    "rr_speed": "<<float32>>",      // rear-right wheel speed in range [0, 40]
 }
 "":
}






  
