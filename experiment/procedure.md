### General Instructions  

1. The aim is to introduce the students to the working of the Selective Repeat ARQ and how it behaves under the situations such as frame lost or Acknowledgement Lost.  
2. Once redirected to simulation page (default for window size 3), then they are required to choose the window size for which the simulation is desired.  
3. For the respective window size, the simulation begins with an array (labeled as Frames) representing the frames on the left side of the page and the instructions prompted on the right side of the page.  
4. The user needs to make the right selections in the array for the simulation to run further.  
5. If the user fails to select the correct frames at any point of simulation, the “Wrong Frame Selected” is alerted on the screen and until the user successfully selects the correct frames, the simulation does not proceed and the user is given as many retries as needed.  
6. An index is provided to the left of the screen to allow the user to understand which color signifies what behaviour.  


### For a window size of 3, follow these steps:  

1. Firstly, send the first three frames to the receiver, i.e., 1, 2, 3 and now the sender is expected to receive the acknowledgment of the 1st frame.  
2. After ACK 1 received, select the next frame to be sent i.e., 4th frame.  
3. ACK 2 not received because the acknowledgment is lost, retransmit the frame i.e., 2.  
4. After ACK 3 received, select the next frame to be sent i.e., 5.  
5. NACK received, retransmit the frame i.e., 4.  
6. After ACK 2 received, select the next frame to be sent i.e., 6th frame.  
7. After ACK 5 received, select the next frame to be sent i.e., 7th frame.  
8. After ACK 4 received, select the next frame to be sent i.e., 8th frame.  
9. After ACK 6 received, select the next frame to be sent i.e., 9th frame.  
10. After ACK 7 received, select the next frame to be sent i.e., 10th frame.  
11. After NACK received, retransmit the frame i.e., 8.  
12. ACK received, **ALL FRAMES SENT!**  
13. Input the correct total number of frames transmitted and click the **Submit** button.  


### For a window size of 4, follow these steps:  

1. Firstly, send the first four frames to the receiver, i.e., 1, 2, 3, 4 and now the sender is expected to receive the acknowledgment of the 1st frame.  
2. After ACK 1 received, select the next frame to be sent i.e., 5th and the window slides containing four frames, i.e., 2, 3, 4, 5.  
3. NAK received, retransmit the frame 2.  
4. After ACK 3 lost, retransmit the frame 3.  
5. After ACK 4 received, select the next frame to be sent.  
6. ACK 5, 2, 3, 6 received, select the next four frames to be sent.  
7. ACK 7, 8, 9, 10 received, **ALL FRAMES SENT!**  
8. Input the correct total number of frames transmitted and click the **Submit** button.  


### For a window size of 5, follow these steps:  

1. Firstly, send the first five frames to the receiver, i.e., 1, 2, 3, 4, 5 and now the sender is expected to receive the acknowledgment of the 1st frame.  
2. After ACK 1 received, select the next frame to be sent i.e., 6th and the window slides containing five frames, i.e., 2, 3, 4, 5, 6.  
3. NACK2 received, retransmit the frame 2.  
4. After ACK 3 received, select the next frame to be sent i.e., 7.  
5. NACK 4 received, retransmit the frame 4.  
6. After ACK 5 received, select the next frame to be sent i.e, 8.  
7. ACK 6 lost, retransmit the frame 6.  
8. After ACK 2, 7, 4 received, select the next frames to be sent i.e., 9, 10.  
9. NACK 8 received, retransmit the frame 8.  
10. All ACK received, **ALL FRAMES SENT!**  
11. Input the correct total number of frames transmitted and click the **Submit** button.  
