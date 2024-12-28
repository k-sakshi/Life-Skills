# OSI Model #

## Summury ##

- When discussing networking, it's important to understand how different connections work together for smooth data transfer.
- The Open Systems Interconnection (OSI) model provides a structured framework with seven layers, each handling a specific aspect of networking.
- This model helps troubleshoot issues, ensure device compatibility, and simplify protocol development. 

Following sections explores how each layer contributes to effective communication between devices.

#### 1. Physical Layer ####

- This includes the cable and wireless connections among devices, as well as hardware specifications like jacks, plugs, and voltages.

#### 2. Data Link Layer ####

- This layer provides the direct protocol connection between two nodes on a network and handles error connection from the physical layer.

#### 3. Network Layer ####

- This is the routing layer at which packets are forwarded from their source to their destination. 

#### 4. Transport Layer ####

- This layer coordinates the transfer of data between systems and hosts by specifying such things as how much data to send and at what rate.

#### 5. Session Layer ####

- For two devices to transact specific functions between each other, a session is required, and this layer handles :
1. setting up sessions
2. coordinating the rules for communication.

#### 6. Presentation Layer ####

- At this layer, data is prepared for presentation between layers. 
- For example, data that is encrypted across the network would be decrypted at this layer for presentation to an application at the destination device.

#### 7. Application Layer ####

- This is the layer at which applications are displayed to the end user.

## References ##

- Cisco OSI Model : https://learningnetwork.cisco.com/s/article/osi-model-reference-chart
- Cisco CCNA course notes : https://www.certificationkits.com/cisco-certification/cisco-ccna-640-802-exam-certification-guide/cisco-ccna-the-osi-model/
- YouTube Video : https://youtu.be/vv4y_uOneC0?si=fS5jJOJFL7pJFwZP
- Video : https://youtu.be/_FmDKQ3hlYs?si=-lkXkKN9EACIozZC  