# A3 – Parametric and FEA

## Objective

The objective of this assignment is to design a beam using the force and deflection. This also allows us to practice using CAD and simulations and different analysis. 

## Analyze

I decided to use a force (F) of 400 lbf, a young's modulus (E) of 10x10^6 psi, and a diameter (d) of 0.5 in. 

First I found the area of the cross section.

<img width="540" height="95" alt="Screenshot 2026-09-10 061814" src="https://github.com/user-attachments/assets/179c556b-1297-4ac3-9115-6b6f6ed1e9f6" />


After finding the area I can use the direct tension elongation equation to find the minimum length of the beam. 

<img width="548" height="263" alt="Screenshot 2026-09-10 061820" src="https://github.com/user-attachments/assets/537189b5-0c0a-4606-98db-34c2bfa35ef0" />


Starting on the CAD of the beam I started with writing the equations and what each global value was equal to to be the base of the beam. These equations generated from my previous calculations and choice of parameter. The solutions of the equations I made in solid works match my previous calculations, specifically the total length. 

<img width="927" height="422" alt="Screenshot 2026-09-08 150704" src="https://github.com/user-attachments/assets/faaf18fe-0fed-4b60-8503-1422b8245500" />

Then I created the cross-section which is a circle with a diameter of 0.5. I made the equations connect to my beam by connecting the global variables to the dimensions as seen in the second picture. 

<img width="393" height="340" alt="Screenshot 2026-09-08 150918" src="https://github.com/user-attachments/assets/774669d3-b7f8-4caf-93c7-918a0b7d11ec" />

<img width="222" height="166" alt="Screenshot 2026-09-08 150942" src="https://github.com/user-attachments/assets/e20b51a7-f3c6-4a7c-8507-b2b411be908c" />

I then extruded the cross-section into the beam and connecting the equations and dimensions as previously stated. 

<img width="940" height="717" alt="Screenshot 2026-09-08 151050" src="https://github.com/user-attachments/assets/e55035ee-c245-4f35-a4b1-bc6c91126fae" />

<img width="318" height="608" alt="Screenshot 2026-09-08 151257" src="https://github.com/user-attachments/assets/c630a55b-68fc-4892-b1bd-3cadeecc4bbd" />

<img width="435" height="337" alt="Screenshot 2026-09-08 151417" src="https://github.com/user-attachments/assets/ee705698-93fe-418b-b694-938c3403842d" />

After the beam was made I started a simulation in solid works to allow me to add the outside forces. I added the fixtures to have the beam supported.

<img width="860" height="872" alt="Screenshot 2026-09-09 152745" src="https://github.com/user-attachments/assets/c0f0509d-b041-4006-80cc-f30dfe192e83" />

<img width="692" height="435" alt="Screenshot 2026-09-09 152816" src="https://github.com/user-attachments/assets/3fd25dfe-28a0-40fc-99fa-efad3c8f9eb0" />

I then added the forces that is acting on the end of the beam in the opposite direction of the fixture. 

<img width="702" height="640" alt="Screenshot 2026-09-09 153317" src="https://github.com/user-attachments/assets/2dd1f8e1-4e3f-4507-ae6c-3583f1cfbc28" />

Then I changed the material of the beam to match the young's modulus and the aluminum required. I did this by going through the materials and looking at the properties to find the one that matches. The material that matched was the 1060 alloy. 

<img width="945" height="780" alt="Screenshot 2026-09-09 154030" src="https://github.com/user-attachments/assets/da3f888c-6e92-49ee-b8ca-e0a185d99968" />

This is all of the simulations settings. 

<img width="302" height="452" alt="Screenshot 2026-09-09 154153" src="https://github.com/user-attachments/assets/2b1a71f5-4c01-4a87-947d-68b5ff557042" />

Final beam design:

<img width="1110" height="230" alt="Screenshot 2026-09-09 154508" src="https://github.com/user-attachments/assets/c3c5fe6f-0163-4385-97b8-a541a482c9eb" />

These are the results of the displacement deformation scale:

<img width="882" height="633" alt="Screenshot 2026-09-10 002851" src="https://github.com/user-attachments/assets/dd8ef7c0-c67f-4bab-bae4-c1c53d4f3645" />

Finally these are the results of the Von Mis stress diagram:

<img width="886" height="695" alt="Screenshot 2026-09-10 002909" src="https://github.com/user-attachments/assets/59d1e902-64a6-477c-81ea-5f6e63fec310" />


## Decide

The remote stress of a beam with a pin hole and a diameter of 0.5 inches is 4.25 with a net stress area of 2.13 according to the Peterson's chart. To find the theoretical peak stress it is the stress from the FEA(the remote stress). My work is in the image below.

<img width="613" height="432" alt="Screenshot 2026-09-10 061825" src="https://github.com/user-attachments/assets/637193c6-5fa3-443c-8fd0-a1dbee56b302" />


## Communicate

In this assignment I learned what a finite element analysis (FEA) is and how to obtain the information from CAD. I also expanded my knowledge of simulations and how they can help me in the future in solid works.

This assignment took approximately 10 hours to complete. 

 Here is a link to my CAD model: [Assignment3.pdf](https://github.com/user-attachments/files/32054101/Assignment3.pdf)

