Color-Based Automated Sorting System
<br>

A vision-based object classifier that sorts using color detection and a single actuator.<br>
--> Introduction <br>

-This project is a real-time object classifier that uses a conveyor belt and computer vision to sort objects based on color (Red, Blue, or Trash) and display a counter for each. Built using OpenCV, Arduino Uno, and a custom servo-controlled arm.<br><br>

-The object is moved by a conveyor, captured via webcam, classified using HSV filtering, and sorted into bins via a 3D-printed servo-controlled arm.<br>
--> User Instructions<br>

1) Place an object on the conveyor belt.<br>
2) The color of the object is detected using OpenCV python.<br>
3) Arduino receives signals ('R', 'B', 'T') via serial and actuates the sorting arm.<br>
4) Object is sorted into the appropriate bin (Green, Blue, or Trash).<br>

-->Dev Instructions<br> 
1)To classify a custom colour, update its color range in the given python code.<br>
2)Adjust the servo motor angle accoeding to your project need.<br>
--> Hardware Required:<br>

-Arduino Uno<br>
-Servo Motor (for sorting arm)<br>
-Gear Motor (for conveyor belt)<br>
-Webcam<br>
-Ultrasonic Sensor (for object detection trigger)<br>
-3D-printed Sorting Arm<br>
-Conveyor Belt Setup.....

