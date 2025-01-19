[# PS-2025-S8-Biswajit]
*ps*: 
 <p align="center">
   <img src="https://github.com/user-attachments/assets/c156504e-aa2f-4d54-9583-70e9134ee6c7" alt="Description" width="600" height="400"/>
</p>

Consider a block of metal or semiconductor material with dimensions L,W, and H .\
Let N= Free charges per unit volume. \
A battery of "V" volt connected across the block .To calculate the current I<sub>R</sub> for an applied voltage across the length of the material, We will consider an incremental cross section of the material with length.The current can be written as the total charge in the incremental volume in time. 

$$I_R = \frac{\Delta Q}{\Delta T}= Q_S\frac{\Delta X}{\Delta T}=Q_SV_D ...............................(i)$$

or,

$$I_R=SheetCharge * AverageVelocity$$

Here Q_S is the Sheet charge or the Free charges per unit length

$$Q_S= NWH = NA.............................................(ii)$$

V<sub>D</sub>  is the average velocity of free charges:

$$ V_D= \frac{\Delta X}{\Delta T} =\mu E ....................................................(iii) $$

$$E= \frac{\Delta V}{\Delta X}....................................................(iv)$$ 

Therefore from equation (i),(iii) and (iv)

$$I_R =Q_SV_D= Q_S\mu E= \mu Q_S \frac{\Delta V}{\Delta X}.....................................(v) $$

The incremental resistance can be expressed as :

$$\Delta R = \frac{\Delta V}{ I_R}$$

$$ =\frac{\Delta V}{\mu Q_S \frac{\Delta V}{\Delta X}}=\frac{\Delta V \Delta X}{Q_S \mu\Delta V}=\frac{\Delta X}{Q_S \mu}=\frac{\Delta X}{N A \mu}=\frac{\rho \Delta X}{A}$$

Total resistance of the material can be expressed as:

$$R = \sum \Delta R=\sum \frac{\rho\Delta X}{A}=\frac{\rho}{A} \sum \Delta X=\frac{\rho L}{A}.................................................(vi)$$

Here L and A are the length and cross-sectional area (WH) of the block respectively .

$$ R =\left( \frac{\rho}{H} \right) \left(\frac{L}{W} \right)....................................................(vii) $$

$\frac{\rho}{H}$ is called sheet-rho( $\rho_{sheet}$).


Calculate the resistance of an aluminum wire with the following dimension:
L= 100\mu, W=1Um, h=0.5 Um $$ \mu m $$
| Material | Resistivity in μm | Resistance | Sheet-row | Melting point | Cost/10 gram | Temprature coefficient of resistance |
|----------|----------|----------|----------|----------|----------|----------|
| Aluminium    | 2.65     | 26.5     | Data     | Data     | Data     | 0.00429     |
| Copper   | 1.68 | 16.8    | Data     | Data     | Data     | 0.00393   |
| Gold | 2.44| 24.4  | Data     | Data     | Data     | Data     | 0.0034

:

Lets consider 2 parallel plates connected with a battery of "V" volt .After sometimes of battery connection let the plate connected with the cathode of battery has total charge +Q on its surface and the plate connected with the anode of battery has total charge -Q on its surface .\
Gradually as the charge increases on the plate potential also increases.Let the potential on the plates are V1 and V2 respectively .\
Relation between total charge on either plate and potential difference between two parallel plates (V= V1-V2) can be mathematically expressed as:

$$ Q \propto V $$
 
Here the proportionality constant is the capacitance of the parallel plates : 

$$ Q = CV .......................(i)$$  
 
We will apply Gauss's theorem to calculate the capacitance of the parallel plates .\
Gauss Theorem can mathemticallly expressed as

$$\Phi_E = \oint\limits_S\overrightarrow{E} . \overrightarrow{dS} = \frac{Q _{in}}{\epsilon_o} .........................................(ii)$$

We imagine a closed gaussian surface around a plate and total electric flux coming out of that closed gaussian surface can be expressed as

$$\Phi_E = EA=  \frac{Q}{\epsilon_o} $$

Q can be expressed as :

$$ Q=\overrightarrow{E}.A.\epsilon_o ...................(iii) $$

Assuming a large area and small separation "d" between plates , Electric feild between plates can be expressed mathematically 

$$ \overrightarrow{E} = \frac{V}{d}...........................(iv)$$

From the equation 1 Capacitance C can be expressed as  : 

$$C= \frac{Q}{V} $$

Therefore putting the values of Q and V from equation 3 and 4 the capacitance of the parallel plates can be expressed as:

 $$ C=\frac{\epsilon_0 \cdot AE}{Ed} = \frac{\epsilon_0 \cdot A}{d} ............................(v)$$

* Calculate C1 and C2 of the imagegiven below.
 <p align="center">
   <img src="https://github.com/user-attachments/assets/1eb4bfff-6368-469d-bfcd-5d40f87470b8" alt="Description" width="600" height="400"/>
</p>
Answers:To calculate C1:

$$ C_1= \frac {\epsilon_o.A.K}{d} $$

$$=\frac{8.85 \times 10^{-12}\times 100 \times 10^{-6} \times 1 \times10^{-6} \times 3.9}{1 \times 10^{-6}} =3.4515 \times 10^{-15}$$

To calculate C2:                            

$$C_2=\frac {\epsilon_o.A.K}{d} $$

$$=\frac{ 8.85 \times 10^{-12}  \times 100 \times 10^{-6} \times 1 \times10^{-6} \times 3.9}{0.1\times 10^{-6}}=34.515 \times 10^{-15} $$

| Dielctrics| A=5000 mm<sup>2</sup> D= 0.5mm| A=5000 mm<sup>2</sup>D= 1.5mm|  A=5000 mm<sup>2</sup> D= 2.5mm |  A=5000 mm<sup>2</sup> D= 3.5mm |  A=5000 mm<sup>2</sup> D= 4.5mm |  A=5000 mm<sup>2</sup> D= 5mm|
|----------|----------|----------|----------|----------|----------|----------|
| Air  | C=89 K=1.005     | C=30 K=1.016   | C=18 K=1.016   | C=13 K=1.028   | C=10 K=1.016  | C=9 K=1.016    |
| Mica  | C=456 K=5.15  | C=148 K=5.016| C=89 K=5.028   | C=64  K=5.062  | C=48 K=4.88    | C=45 K=5.08   |
| Paper    | C=307 K=3.46  | C=104 K=3.52    | C=63 K=3.55    | C=45 K=3.55  | C=34  K=3.45  | C=32 K=3.615   |
| Paraffin    | C=210 K=2.37   | C=67  K=2.27    | C=42  K=2.37    | C=28 K=2.21    | C=23 K=2.33   |C=21 K=2.37   |
| Porcelain    | C=546   K=6.16 | C=188 K=6.37   |C=108   K=6.10    | C=80 K=6.32    | C=63  K=6.40    |C=54  K=6.10    |
| Glass   | C=601  K=6.79  | C=204 K=6.91    |C=121 K=6.83   | C=89   K=7.03    | C=68  K=6.91 | C=63 K=7.11   |






| Dielectrics |A=5000 mm<sup>2</sup> D= 0.5mm | A=10000 mm<sup>2</sup> D= 0.5mm| A=15000 mm<sup>2</sup> D= 0.5mm | A=20000 mm<sup>2</sup> D= 0.5mm | A=25000 mm<sup>2</sup> D= 0.5mm | 
|----------|----------|----------|----------|----------|----------|
| Air    |C= 89 K=1.005|C=177 K=1|C=266 K=1.001|C=354 K=1    | C=443  K=1.001|
| Mica    | C=456   K=5.15|C=858 K=4.84 |C=1314 K=4.94 |   | C=1 | 
| Paper    | C=307   k=3.46| C=620 K=3.50|C=911 K=3.43| C=1202 K=3.39 | C= 1533 K=3.46|
| Paraffin    |C=210 K=2.37 | C=407 K=2.29     |C=617 K=2.32    | C=806 K=2.27  | C=1028 K=2.32 |
| Procelain  |C=546 K=6.16| C=1104 K=6.23     | C= 1689 K=6.36     | C=1 K=0.0028| C=1 K=0.0022| 
| Glass    |C=601 K=6.79|C=1264 K=7.141     | C=1877 K=7.069     | C=1 K=0.0028     |C=1 K=0.0022  |    


 


* What is the maximum current that can flow through a ⅛-W,6.8-kΩ resistor? What is the maximum voltage that can be across it?
Answers:

Here Power(P) = 1/8 W, Resistance of Resistor= 6.8 K

$$P = \frac{v^2}{r}$$

$$v = \sqrt{P \cdot R}$$
 
$$v = \sqrt{\frac{1}{8} \times 6.8 \times 10^{-3}}=29.15$$

$$P = I^2 \cdot R$$

$$I = \sqrt{\frac{P}{R}}$$ 

$$\sqrt{\frac{\frac{1}{8}}{6.8 \times 10^3}}$$

* Given i 1 = +4 A, i 3 = +1 A, i 4 = +2 A in the circuit shown in
Figure 2–11 , find i 2 and i 5 .

Answers:

$$i_1+i_2=0 $$

$$ i_1=-i_2$$

$$i_2+i_3+i_4=i_5$$

$$i_5= -4+1+2=-1$$

* The circuit below shows a delicate device that is modeled by a 90-Ω equivalent resistance. The device requires a current of 1 mA to operate properly.A 1.5mA fuse is inserted in series with the device to protect it from overheating. The resistance of the fuse is 10 Ω. Without the shunt resistance (R<sub>X</sub>) ,the source would deliver 5 mA to the device, causing the fuse to blow. Inserting a shunt resistor (R<sub>X</sub>) diverts a portion of the available source current around the fuse and device. Select a value of (R<sub>X</sub>) so only 1 mA is delivered to the device.
<p align="center">
   <img src="https://github.com/user-attachments/assets/026d07e7-9fa4-4b57-8217-ef82875cd28a"  alt="Description" width="800" height="250"/>
</p>
Answer: Value of 'V' :

$$(90 + 10)\ \Omega \times 1\ \text{mA}=0.1v ........................(i)$$

Current flowing through '100Ω' resistor:

$$\frac{0.1}{100}=1 \times 10^{-3}.....................................(ii)$$

Current Flowing through Shunt Resistor( R<sub>X</sub>):

$$10 - 1 - 1 = 8\ \text{mA}............................................(iii)$$

Value of resistance of shunt resistor (R<sub>X</sub>) : 

$$\frac{0.1}{8} \times 10^{-3} = 12.5 \ \Omega.................(iv) ..  (Ans)$$





2–34 In Figure P2–34 find the equivalent resistance between
terminals A–B, A–C, A–D, B–C, B–D, and C–D.







