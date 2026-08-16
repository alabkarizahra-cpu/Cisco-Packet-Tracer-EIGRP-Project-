# EIGRP Routing & Network Redundancy in Cisco Packet Tracer

Overview
This project demonstrates the implementation of Enhanced Interior Gateway Routing Protocol (EIGRP) using Cisco Packet Tracer.
The project focuses on dynamic routing, network connectivity, and redundancy by configuring EIGRP across multiple routers and simulating a link failure to verify that traffic can continue through an alternate path.



Project Objectives
 • Configure EIGRP on the network routers.
 • Establish and verify EIGRP routing.
 • Examine EIGRP-related routing information.
 • Test connectivity between end devices.
 • Simulate a network link failure.
 • Verify continued connectivity through an alternate path.



Technologies & Tools
 • Cisco Packet Tracer
 • Cisco IOS CLI
 • EIGRP
 • IPv4
 • Dynamic Routing
 • Network Redundancy & Failover



Network Topology
The network consists of multiple routers connected through different paths, with end devices used to test connectivity.
The topology was designed to provide an alternate path so that communication can continue when one link becomes unavailable.



Router Configuration
EIGRP was configured on the routers using the Cisco IOS command-line interface.
The configuration included the EIGRP routing process and the required network statements.



EIGRP Verification
EIGRP operation was verified using Cisco IOS show commands to examine routing and EIGRP information.
The verification process was used to confirm that the routers were learning routes dynamically through EIGRP.



Connectivity Test
Connectivity between the end devices was successfully tested before and after the network failure simulation.
The test confirmed that traffic could reach its destination through the configured routing paths.



Failover Test
To test network redundancy, one of the serial interfaces was shut down to simulate a link failure.
After the primary path became unavailable, EIGRP selected the alternate available path, allowing communication between the end devices to continue.
This demonstrated the role of dynamic routing in maintaining connectivity and improving network resilience.



Key Learning Outcomes
Through this project, I gained practical experience with:
 • EIGRP configuration and verification.
 • Dynamic route learning.
 • Routing table analysis.
 • Network connectivity testing.
 • Link failure simulation.
 • Failover and network redundancy.
 • Cisco IOS command-line configuration.



Demonstration
A short video demonstration of the project is available in my LinkedIn post.
The demonstration shows:
 1. Successful packet delivery across the network.
 2.  Failure of one network path.
 3. Continued packet delivery through the alternate path.

 3. Failure of one network path.
 4. Continued packet delivery through the alternate path.
