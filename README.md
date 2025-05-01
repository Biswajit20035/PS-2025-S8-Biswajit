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
Gauss Theorem can mathemticallly expressed as :

$$\Phi_E = \oint\limits_S\overrightarrow{E} . \overrightarrow{dS} = \frac{Q _{in}}{\epsilon_o} .........................................(ii)$$
 
We imagine a closed gaussian surface around a plate of total charge "Q" and total electric flux coming out of that closed gaussian surface can be expressed as:

$$\Phi_E = EA=  \frac{Q}{\epsilon_o} $$

Q can be expressed as :

$$ Q=\overrightarrow{E}.A.\epsilon_o ...................(iii) $$

Assuming a large area and small separation "d" between plates , Electric feild between plates can be expressed mathematically as : 

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

$$=\frac{8.85 \times 10^{-12}\times 100 \times 10^{-6} \times 1 \times10^{-6} \times 3.9}{1 \times 10^{-6}} =3.4515 \times 10^{-15}=3.1545 \text{f F} $$

To calculate C2:                            

$$C_2=\frac {\epsilon_o.A.K}{d} $$

$$=\frac{ 8.85 \times 10^{-12}  \times 100 \times 10^{-6} \times 1 \times10^{-6} \times 3.9}{0.1\times 10^{-6}}=34.515 \times 10^{-15} =34.515 \text{f F}$$

### Datasheet of some different types of capacitors :

| Type             | Capacitance range  | Maximum voltage | Accuracy  | Temperature stability | Leakage   | Comments                                               |
|------------------|--------------------|-----------------|-----------|-----------------------|-----------|--------------------------------------------------------|
| Mica             | 1pF-0.01μF         | 100-600         | Good      | Good                  | Good      | Excellent; good at RF                                  |
| Tubular ceramic  | 0.5pF-100pF        | 100-600         | Selectable|                       |           | Several tempcos (including zero)                       |
| Ceramic          | 10pF-1μF           | 50-30,000       | Poor      | Poor                  | Moderate  | Small, inexpensive, very popular                       |
| Polyester (Mylar)| 0.001μF-50μF       | 50-600          | Good      | Poor                  | Good      | Inexpensive, good, popular                             |
| Polystyrene      | 10pF-2.7μF         | 100-600         | Excellent | Good                  | Excellent | High quality, large; signal filters                    |
| Polycarbonate    | 100pF-30μF         | 50-800          | Excellent | Excellent             | Good      | High quality, small                                    |
| Polypropylene    | 100pF-50μF         | 100-800         | Excellent | Good                  | Excellent | High quality, low dielectric absorption                |
| Teflon           | 1000pF-2μF         | 50-200          | Excellent | Best                  | Best      | High quality, lowest dielectric absorption             |
| Glass            | 10pF-1000pF        | 100-600         | Good      |                       | Excellent | Long-term stability                                    |
| Porcelain        | 100pF-0.1μF        | 50-400          | Good      | Good                  | Good      | Good long-term stability                               |
| Tantalum         | 0.1μF-500μF        | 6-100           | Poor      | Poor                  |           | High capacitance; polarized, small; low inductance     |
| Electrolytic     | 0.1μF-1.6F         | 3-600           | Terrible  | Ghastly               | Awful     | Power-supply filters; polarized; short life            |
| Double layer     | 0.1F-10F           | 1.5-6           | Poor      | Poor                  | Good      | Memory backup; high series resistance                  |
| Oil              | 0.1μF-20μF         | 200-10,000      |           |                       |           | High-voltage filters; large, long life                 |
| Vacuum           | 1pF-5000pF         | 2000-36,000     |           |                       | Excellent | Transmitters                                           |
 


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

Current flowing through '100 $$\Omega$$'  resistor:

$$\frac{0.1}{100}=1 \times 10^{-3}.....................................(ii)$$

Current Flowing through Shunt Resistor( R<sub>X</sub>):

$$10 - 1 - 1 = 8\ \text{mA}............................................(iii)$$

Value of resistance of shunt resistor (R<sub>X</sub>) : 

$$\frac{0.1}{8} \times 10^{-3} = 12.5 \ \Omega.................(iv) ..  (Ans)$$

SRAM 
