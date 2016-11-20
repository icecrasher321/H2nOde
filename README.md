# H2nOde
Code Compilation for our Junior Academy Project - H2nOde

Problem 
----------------

According to estimates, polluted water in Africa and India causes 1.4 million deaths each year. Real-time monitoring of a water source has always been a major problem for authorities, organisations and scientists. With high levels of pollution pointing at severe consequences ranging from starting epidemics to eliminating entire species, never has solving this problem been more significant than the present.

Approach
-----------
    *   Static data points - Small (extremely low-powered simple) structures present under (but near the surface) of the          
        water. They serve the simple purpose of collecting certain types of data and then transferring the data to a “parent”-
        mechanism.
        
    *    Mobile “parents” - Drone/Quadcopter that keeps track and serves the needs of its “children" - static nodes. The
         static nodes can come to the surface to transmit the data to their respective parent drone (who can then send it to
         the cloud for analysis). Each parent drone can have up to 50 static-nodes (number liable to change). This would
         completely eliminate the need for underwater communication and drastically reduce the cost.

    *   There can be many such networks (depending on the size of the water source), forming a larger network thereby
        harnessing the efficiency of swarm robotics.


Sources
-----
    *   https://forum.arduino.cc/index.php?topic=333319.0  - Static Node Data Collection
    *   http://blog.owenson.me/build-your-own-quadcopter-flight-controller/ - Drone Control (ArduPilot)

