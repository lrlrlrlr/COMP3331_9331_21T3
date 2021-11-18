# COMP3331_9331_21T3
For T18A and W17A students

## Useful links:
 - [Course home page](https://webcms3.cse.unsw.edu.au/COMP3331/21T3/)
 - [Lab timetable and recordings](https://webcms3.cse.unsw.edu.au/COMP3331/21T3/resources/65958)
 - Forumn: https://edstem.org/au/courses/7054/discussion/ 
 - Tuesday 18:00 (T18A) lab link: https://unsw.zoom.us/j/82232078296 
 - Wednesday 17:00 (W17A) lab link: https://unsw.zoom.us/j/85837612940

--------------------------------
## Tut02 / Finalexam
 -  Recording: https://youtu.be/BoPMGeGf4LE 
 -  review slides: https://github.com/lrlrlrlr/COMP3331_9331_21T3/blob/main/9331review/slides_final_rev.pdf   
 -  Useful material: https://github.com/lrlrlrlr/COMP3331_9331_21T3/tree/main/9331review/final

-----------------------------
## Assignment demo structure
 -  based on the demo code
 -  server will have a main thread to handle incomming connection from client
 -  Once a client connected to the server, server will create a subthread/subprocess to handle the TCP connection.
 -  The Client will also have 3 different thread/process:
    -   main process - **sending** message: this process will handle all the user input, and send it to the server/another client.
    -   subprocess 1 - **receiving** message: this process will handle all the incoming messages (basically print them)
    -   subprocess 2 - **listening**: this process is for P2P connection, it is highly similar to the main thread of server.py. Once a client is connected to it, it will create a subthread/subprocess to handle the TCP connection.
 -  More detail about P2P - **How** doessubprocess 2 - listening work?
      -   it will find an available port and listen to it.
      -   it will upload the IPAddress/port to the server: to allow other clients to get its address and connect to it.
      -   it will start to listen (in a while loop), once another client is connected to it, it will create a subthread/subprocess to handle the TCP connection.
 ![image](https://user-images.githubusercontent.com/27357380/142300671-b2ffa789-c33d-4755-b01d-3c781bcc42a9.png)

--------------------------------



## Lab1：  
 - Lab 1 submission deadline: 10:00 Tue 28 Sept  
 - Recording: https://youtu.be/MLiYH3dYjKs 
 - Slides: https://github.com/lrlrlrlr/COMP3331_9331_21T3/blob/main/COMP3331_w2%E2%80%94%E2%80%94demo.pdf 
-----------------------------


## Lab2
 - Lab recording: https://youtu.be/A-fddDFtZL0
 - Recording clip(Short video): 
   - q3 https://youtu.be/eBnyq6_IQqE  
   - q4 https://youtu.be/Yg5IwiD2Ync   
   - q5 https://youtu.be/9ARKigLwJfM  

--------------------------------

## Lab3
 -  Lab recording: https://unsw.zoom.us/rec/share/dHzy7PBQipEmKzXRYq-_Rew7059SwLrP6oD5geD8o-Vpj5sbs0Qvy2a_SoqxWoUd.uSIrVeyY_UMTtjSh
 -  Passcode: M@5kQWVa 



--------------------------------
## Tut01 / Midterm
 -  [Midterm Useful info](https://github.com/lrlrlrlr/COMP3331_9331_21T3/tree/main/9331review)
 -  w1~w5 review recording: https://youtu.be/1wc6fVItUuE 
 -  review slides: https://github.com/lrlrlrlr/COMP3331_9331_21T3/blob/main/9331review/slides_midterm_rev.pdf   

--------------------------------

## Lab4
 -  Lab recording: https://youtu.be/uCRe-hEd_WI 
 

--------------------------------

## Lab5
 -  Lab recording: https://youtu.be/b3lHD9xLBlM 
 

--------------------------------

## Lab6
 -  Lab recording: https://youtu.be/Yrr3pI7H9NY 
 
