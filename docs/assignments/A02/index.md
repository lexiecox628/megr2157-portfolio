A2 – Truss Stress Analysis

## Objective
The purpose of this projects is to design a truss that meets all of the constraints. 

## Analyze
I started with connecting all of the pins and forces to make a trapezoid. 

<img width="708" height="558" alt="image2" src="https://github.com/user-attachments/assets/ab2a541b-8c76-4aad-9ce6-7826ea0cbafc" />

 I decided to place a slanted bar in the middle and two bars vertically. This created 4 triangles that are all equal in area. 

<img width="682" height="607" alt="image0" src="https://github.com/user-attachments/assets/902f2fcb-904a-4635-b76c-210addb4d18b" />

To find the external forces I took out all of the internal supports. The roller B only has a reaction force in the Y-direction labeled as By in the free-body diagram. The pin A has both a reaction force in the X-direction and Y-direction labeled as Ay and Ax. I selected P to be a value of 25 kN. I started by finding the moment about A where I found By= 8.33 kN. I then moved on to fine the forces in the Y-direction. Ay=-8.33 kN. There is only one force in the X-direction which is Ax so it equals 0. I then went ahead and found the values of cos(theta) and sin(theta) to help with the later math I had to do. 

<img width="1419" height="1636" alt="image3" src="https://github.com/user-attachments/assets/3a27de69-972f-41b4-a02c-8177161f0ad3" />

Next I needed to find the internal forces. I decided to do the method of joints. I started with joint B. To start I drew the free body diagram for the point and drew all of the directions in tension away from the pin. I started out with the forces in the Y-direction to find the force acting on BC which is equal to -13.89 kN the negative means the force is in compression. I then did the forces acting in the X-direction. I found that BE is equal to 11.11 kN which is in tension with the pin. 

<img width="706" height="607" alt="image1" src="https://github.com/user-attachments/assets/f211a56e-5e7d-4b08-ae22-d838f333cd5c" />

This is the work for the rest of the joins to find all of the internal forces. 

<img width="1403" height="1737" alt="image4" src="https://github.com/user-attachments/assets/cef75717-a4af-4d6c-ae30-5d9d41e3ecc0" />

Then I found the cross-sectional area of the elements. First I needed to know what stress was allowed before it broke. Using the yield strength of the metal given and dividing it by a factor of safety of 98.57x10^6 Pa. This will allow me to find the area which is the largest force of the internal and external forces which was 27780 N divided by the allowed stress. The cross-sectional area is 281.8 mm^2.

<img width="826" height="503" alt="image5" src="https://github.com/user-attachments/assets/2a82753b-de39-40b7-ad3f-02acc102dd96" />

I also needed to find the shear yield of the pins. 

<img width="1068" height="816" alt="image6" src="https://github.com/user-attachments/assets/337d48cd-377b-419f-a82d-0fc06e08a24e" />

This is the start of the truss with all of the lengths

<img width="1040" height="493" alt="Screenshot 2026-09-03 001504" src="https://github.com/user-attachments/assets/233a1703-e7f2-4a9c-98e7-e037a47e6f5e" />

Here is the truss without pins

<img width="812" height="370" alt="Screenshot 2026-09-03 002901" src="https://github.com/user-attachments/assets/bafa53e8-45c4-42cb-a50e-3eb452c5c369" />

## Decide
Thinking about how bridges are made and how points C and D needed to be more supported. I felt that doing the math would also be easier. 

This is a picture reference picture to the type of truss I made. Picture website (https://www.britannica.com/technology/bridge-engineering/Truss)

<img width="738" height="354" alt="images" src="https://github.com/user-attachments/assets/95e50dbb-77b8-435e-bb55-34b444794767" />




## Communicate

This assignment took me around 12 hours to complete. I learned that there are many different truss designs. Some are more simple and some are harder to accomplish. One thing I need to work on is navigating solidworks. 
