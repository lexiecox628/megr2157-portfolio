# A10 – Lead Screw Translating System

## Objective

The objective of this project was to conceptually design a mechanically driven tensile testing machine capable of applying up to 2 kN of axial tensile force to a test specimen. The system uses a leadscrew-driven crosshead to provide controlled, repeatable movement at speeds ranging from 1 to 50 mm/min. The design focuses on maintaining structural strength, minimizing crosshead deflection and misalignment, and providing reliable specimen gripping. Additional design considerations include selecting appropriate leadscrews, ensuring a factor of safety of 4, and developing a compact, safe, and ergonomic bench-top system. The final design must operate entirely through mechanical components, without electronics or software. In the group we have Lexie Cox, Morgan Gregory, and Ethan Cornett. 

## Design

### Leadscrew diameter (Ethan Cornett)

#### Minimum Leadscrew Diameter

The first step in selecting the leadscrews was determining the minimum diameter required to safely support the tensile tester's maximum load of 2 kN. Since the design uses two identical leadscrews, the total load is distributed equally between them, resulting in an axial load of 1 kN per screw.

304 stainless steel was initially selected as the material for the leadscrews, with a yield strength of 205 MPa. A factor of safety of 4 was applied to determine the minimum required diameter.

The diameter was calculated using the axial stress relationship: O=F/A

The allowable stress was determined using the material yield strength and required factor of safety. The resulting theoretical minimum diameter was approximately 4.99 mm. I decided to use a diameter of 12.7mm or 1/2 inch.

This calculation established the minimum structural requirement before selecting a commercially available leadscrew.

<img width="4284" height="5712" alt="79b9d623-2dfb-4c2f-89f1-5216699750c0" src="https://github.com/user-attachments/assets/54977db4-62de-4ecf-b2a3-5dc57babc4b8" />


#### Rotational Speed Range

After establishing the minimum diameter, the next step was determining the rotational speed required to achieve the specified crosshead speed.

The tensile tester must operate between 1 mm/min and 50 mm/min. The relationship between linear crosshead speed and leadscrew rotational speed is:

V=nL

Where:

(V) = Linear crosshead speed (mm/min)

(n) = Leadscrew rotational speed (RPM)

(L) = Leadscrew lead (mm/rev)

The selected 1/2-10 Acme leadscrew has a lead of 0.100 inches per revolution, equivalent to 2.54 mm/rev, assuming a single-start thread.

Using this lead, the required rotational speed range is:

Minimum speed: 0.394 RPM

Maximum speed: 19.69 RPM

Both leadscrews will rotate at the same speed to maintain synchronized crosshead movement.

<img width="4284" height="5712" alt="9d68d5f8-824b-4c5c-bd6a-8606b45c5a86" src="https://github.com/user-attachments/assets/b965af57-eca7-4828-843b-caed07263ab4" />

#### Maximum Leadscrew Torque
   
The next calculation determined the torque required to drive both leadscrews while maintaining the required 2 kN tensile load.

Because the system uses two leadscrews, each screw carries approximately 1 kN of the applied load. The torque calculation accounts for the screw lead and the torque coefficient used in the preliminary design.

The calculated torque requirement was approximately:

T_i = FL/2pi(n)

T_T = 2FL/2pi(n)

T_S =FR_T(2)(N)

Torque per leadscrew: 11.47 in·lbf

Combined torque: 22.94 in·lbf (2.59 N·m)

A factor of safety of 4 was then applied to determine the design torque requirement.

The resulting combined design torque was approximately 10.36 N·m.

This value provides the preliminary torque requirement for selecting the mechanical drive system. Actual operating torque will also depend on the selected nut, lubrication, alignment, and friction.

#### Commercial Leadscrew Selection

After determining the minimum diameter, rotational speed range, and torque requirements, the team moved toward selecting a commercially available leadscrew.

The selected design uses two identical Roton 1/2-10 Acme leadscrews. The 1/2-inch nominal diameter exceeds the calculated minimum diameter of approximately 4.99 mm, while the 0.100-inch lead provides the required crosshead speed range at approximately 0.394–19.69 RPM.

Using identical leadscrews also allows both sides of the crosshead to move together, helping maintain alignment during tensile testing.

Supporting images:

<img width="1900" height="168" alt="a942e818-a7cf-4b56-96bc-ac5d5b328644" src="https://github.com/user-attachments/assets/a0636adc-1907-4dd6-a70a-277ba047d505" />

Design Outcome:

The calculations established the initial requirements for the tensile tester's leadscrew system. The team determined the minimum required screw diameter, the rotational speed range needed to achieve the specified crosshead speeds, and the preliminary torque requirement for the drive system.

These calculations provided the foundation for selecting the commercial leadscrews and developing the remaining mechanical design. 

<img width="882" height="1166" alt="e33f2c2e-001a-4fc4-b7aa-2ddf71d9b302" src="https://github.com/user-attachments/assets/aabcc630-c924-4a3c-b613-b26e41046fda" />

### Nut and Flange (Lexie Cox)

For the Nut and Flange I started out by listing all of the knowns and unknowns needed for the calculations. 

<img width="697" height="345" alt="Screenshot 2026-11-12 003447" src="https://github.com/user-attachments/assets/4a832da1-0892-4d9e-a440-5398652ac18c" />


I then found the bending stress that would be on the chosen nut.

<img width="700" height="222" alt="Screenshot 2026-11-12 003451" src="https://github.com/user-attachments/assets/c9bc8312-bea9-434d-9666-82fec6b7badd" />


It is important to make sure that this is the correct chosen nut and that it would not fail in the machine. To do this I found the maximum bending stress. The calculated bending stress was less than the maximum bending stress meaning that this is the correct nut. 

<img width="748" height="310" alt="Screenshot 2026-11-12 003458" src="https://github.com/user-attachments/assets/07703c38-6977-4a17-b591-14f3dd4fe79e" />


### Crosshead (Morgan Gregory)

Designing the Crosshead: Morgan Gregory To begin, I needed to find both the length, from research, and the base, from the nut flange. The length was chosen to be 300 mm and the base was chosen from the flange nut diameter to be 31.75 mm. The rest of the knowns and unknowns are shown below.

<img width="455" height="330" alt="affecb33-bd4d-495b-88d7-5d79ea54f774" src="https://github.com/user-attachments/assets/77bff04e-afe8-4d44-a80d-ce2c32083ff5" />

I then found the maximum shear and yield stresses using the safety factor of 4.

<img width="394" height="189" alt="ad332f8c-b85c-43c0-af11-6b56cccf9642" src="https://github.com/user-attachments/assets/2dec755e-f655-489a-bc93-803501cfd926" />

Now it is important to calculate minimum values such as thickness of the beam. I began by doing the stress analysis. I analyzed shear stress first and bending stress second. The math is shown below, with minimum h values. 6061 aluminum was the chosen material for its lighter weight and cost effectiveness.

<img width="850" height="290" alt="91fb4e90-9a9d-486b-8968-abe6377aa40b" src="https://github.com/user-attachments/assets/61f54369-29ad-4397-b8c6-da0e2302a1db" />

The minimum value of h for came from the bending stress so far at 11.33 mm.

Now it was important to find the h with the max deflection of .1 mm.

<img width="818" height="217" alt="69f41f7a-5b58-4519-ae4a-055d9a017e5b" src="https://github.com/user-attachments/assets/8cd6b6b5-199a-48c9-a512-334eca5099d6" />

The deflection gave the final value of h as 21.3 mm.

Next is the drawing for the crosshead. Sketches are shown below. Holes are measured as 1 inch.

<img width="815" height="560" alt="03f1a3b3-7e4f-4407-8260-a6f860a1f382" src="https://github.com/user-attachments/assets/4ee90d87-009f-4fa7-a13a-cded9b8b3556" />

## Assembly (Morgan Gregory)

 I began by parametrically designing the crosshead in SolidWorks as shown below.

<img width="921" height="80" alt="ab815211-cd49-4fa7-b102-59fcbceadf5b" src="https://github.com/user-attachments/assets/4b5f33d5-346e-45c8-b043-51787579108d" />

<img width="1286" height="485" alt="f810fa4c-db25-46b7-8840-884ac4db123d" src="https://github.com/user-attachments/assets/7e85be1d-cf55-4727-88a2-29bcbb805732" />

<img width="1916" height="840" alt="dc14b5f8-606c-4c22-bf80-6cc5d6924a63" src="https://github.com/user-attachments/assets/aae2f53f-2705-4f69-afba-a759c41057cd" />

<img width="1004" height="401" alt="7dd0f926-0e76-409e-91ee-aeddceaf0ab1" src="https://github.com/user-attachments/assets/53fa64c8-8b1e-4bc1-83f2-708d0f522b21" />

<img width="1004" height="401" alt="09cedc8a-174c-49c5-a11d-b4ae47a5c934" src="https://github.com/user-attachments/assets/cc28484f-98fe-4f32-9b69-37bc1a7aa491" />

<img width="877" height="379" alt="f817b956-bf1a-49dc-b6e2-428a55a6b362" src="https://github.com/user-attachments/assets/fbbf9e69-c47c-4a2d-aea1-1e1a3b6b6c99" />

The SolidWorks Assembly is shown below and the part file for the crosshead and the assembly are below.

<img width="987" height="532" alt="1c019b66-de2f-4694-885b-876c3dc9df6b" src="https://github.com/user-attachments/assets/211a9123-eb48-4d18-9581-d339ec8a1662" />

<img width="792" height="636" alt="025aa102-b779-4363-9ff4-7e9d8a8049d4" src="https://github.com/user-attachments/assets/f86a41a1-95da-4643-b4ca-bbce090120bb" />

<img width="721" height="625" alt="a6a7e610-4010-45a9-b65a-461b0704f5d8" src="https://github.com/user-attachments/assets/2129c827-22e4-47fc-ac05-73cdadd180c6" />

[Crosshead.zip](https://github.com/user-attachments/files/34730075/Crosshead.zip)

[A10Assembly.zip](https://github.com/user-attachments/files/34730084/A10Assembly.zip)

## Cost (Morgan, Ethan, Lexie)

<img width="872" height="168" alt="Screenshot 2026-11-12 001557" src="https://github.com/user-attachments/assets/3d2e60c2-2a7b-45d3-955d-8fcb7c6eda26" />

## Lessons Learned (Lexie Cox)

In this assignment, we designed a conceptual tensile tester by establishing minimum testing requirements and calculating the specifications for its individual components. The most challenging aspect of the project was selecting appropriate bolt lengths and sourcing bearing fixtures that fit within our design constraints. This highlighted the critical importance of balancing cost, material properties, and applied forces when selecting off-the-shelf components for a mechanical design.

This assignment took us roughly 6 hours to complete. 

## Resources




