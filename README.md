# SKILL-ASSESSMENT-1

# TM AND TE WAVES PROBLEMS
<img width="243" height="312" alt="image" src="https://github.com/user-attachments/assets/c67dab33-4f23-47c4-9fef-9ef68bb60bde" />

##  WHAT IS TM WAVES?

## INTRODUCTION:
- A TM (Transverse Magnetic) wave is a type of electromagnetic wave where both the electric and magnetic fields are perpendicular to each other and to the direction of wave propagation.
- In TM waves, the magnetic field has no component along the direction of propagation.
-  However, the electric field possesses a longitudinal component, aligning partially with the wave's travel path

<img width="675" height="449" alt="image" src="https://github.com/user-attachments/assets/41bb0856-6c14-48e2-bdc3-331b384182b6" />

## WHAT IS TE WAVES?

## INTRODUCTION
- A TE, (Transverse electric) wave, is a type of electromagnetic wave propagation in which the electric field is entirely perpendicular (transverse) to the direction of wave propagationON
- Electric field has no component along the direction of propagation, but the magnetic field exhibits a longitudinal component.

<img width="940" height="527" alt="image" src="https://github.com/user-attachments/assets/26cf442f-d220-420d-af1a-e8a3bae0997d" />

## PROBLEM 1

# A rectangular waveguide with inner dimensions a = 3 cm and b = 2 cm is used to propagate electromagnetic waves. The waveguide is air-filled (ε₀, μ₀).
# (i) Derive the expressions for the cutoff frequency of TE and TM modes in a rectangular waveguide.
# (ii) Calculate the cutoff frequencies for the TE₁₀, TE₀₁, and TM₁₁ modes.
# (iii) If the operating frequency is 10 GHz, determine which modes will propagate and which will be attenuated.
# (iv) Explain, with a real-world example, why TE modes are preferred over TM modes in practical waveguides.

## ANSWER:

# (i) Derivation of Cutoff Frequency 
For a rectangular waveguide, the cutoff frequency for TE and TM modes is given by:

<img width="366" height="76" alt="image" src="https://github.com/user-attachments/assets/b84925ce-1610-4ad2-ab29-ae36c9d20efe" />

- Since it’s air-filled: μ=μ0, ϵ=ϵ0
<img width="279" height="74" alt="image" src="https://github.com/user-attachments/assets/85cb91fb-828b-4771-ab9b-be2c78e37611" />

where,
- m,n= mode indices (integers)
- a,b= waveguide dimensions
- c=3×10^8  m/s 

# (ii) Calculation of Cutoff Frequencies 
Convert dimensions:
a = 0.03 m ,b = 0.02 m
- For TE₁₀:
<img width="461" height="122" alt="image" src="https://github.com/user-attachments/assets/e125286a-d5d1-4157-a1eb-57bf3544f37f" />

- For TE₀₁:
<img width="471" height="124" alt="image" src="https://github.com/user-attachments/assets/a5fce545-19f5-49ab-a588-cc9308db1405" />

- For TM₁₁:
<img width="554" height="114" alt="image" src="https://github.com/user-attachments/assets/d602b6df-8f6e-43f8-a3f2-4afa56dbaf40" />

# (iii) Mode Propagation at 10 GHz (3 marks)

Only modes with (f_c<f) will propagate.

Mode	f_c(GHz)	Propagation at 10 GHz? 
- TE₁₀	-  5.0<10
So,Yes it will propagate

- TE₀₁ -	7.5<10
So,Yes it will propagate

- TM₁₁ -	9.01<10
So,Yes it will propage(barely above cutoff)

Thus, all three can propagate at 10 GHz, but TE₁₀ will dominate because it has the lowest cutoff (hence least loss).

# (iv) Real-World Example & Conceptual Understanding 

In microwave communication systems and radar waveguides, TE₁₀ mode is preferred because:

•	It has no electric field along the direction of propagation, reducing dielectric losses.

•	Easier to excite and transmit efficiently.

•	Provides uniform field distribution — ideal for consistent power transmission.

For example, radar antennas and microwave ovens use TE₁₀ mode for efficient energy transfer.

## PROBLEM 2
# A rectangular waveguide with dimensions 𝑎 = 2.5 cm b=1.5cm operates at a frequency of 8 GHz.
# (i) Calculate the cutoff frequency for the TE₁₀ mode.
# (ii) Determine whether the TE₁₀ mode will propagate at 8 GHz.
# (iii) Explain why the TE₁₀ mode is the dominant mode in rectangular waveguides.

## ANSWER

# (i) Cutoff Frequency
<img width="314" height="96" alt="image" src="https://github.com/user-attachments/assets/af8d2808-3099-4e64-ac05-869e8f06c8d5" />

For TE₁₀: m=1,n=0

<img width="373" height="99" alt="image" src="https://github.com/user-attachments/assets/c526be0e-f41c-4617-aaa2-74adf1ed4d72" />

# (ii) Propagation Condition

Since ,f = 8 GHz > fc = 6 GHz ,

TE₁₀ mode will propagate.

# (c) Conceptual Explanation (1.5 marks)

•	The TE₁₀ mode is the dominant mode because it has the lowest cutoff frequency among all possible modes.

•	It offers maximum power transmission with minimum attenuation.

•	Used in practical systems like microwave guides and radar feeds for efficiency.
