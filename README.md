# EXP-1
EXPT NO: 1	VERIFICATION OF KIRCHHOFF’S LAWS
AIM
a.   To verify Kirchhoff’s Voltage Law (KVL) for the given circuit. 
b.   To verify Kirchhoff’s Current Law (KCL) for the given circuits.

APPARATUS REQUIRED:
S.No.	Components	Range	Quantity
1	Resistor	1kΩ	3
2	Voltmeter (DC)	0-30V	3
3	Ammeter (DC)	(0-200)mA	3
4	Bread Board		1
5	Regulated Power Supply	(0-30)V	1
6	Connecting wires		As required

THEORY:
KVL: Kirchhoff's voltage law states that the sum of the voltage differences around any closed loop in a circuit must be zero. A loop in a circuit is any path that ends at the same point at which it starts.
KCL:
Kirchhoff's Current Law (KCL) Kirchhoff's Current Law states that the algebraic sum of the currents entering and leaving a node is equal to zero. By convention, currents entering the node are positive, and those leaving a node are negative


PROCEDURE:
a.   KVL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the voltmeter connected across each resistor.
7.   Take readings for different values of input voltage and tabulate them.


b.  KCL:
1.   Connect as per the circuit diagram.
2.   Check if the RPS voltage is set to zero voltage.
3.   Check all the meters for null position.
4.   Switch on the RPS.
5.   Set the input voltage to a value between 0V to 30V.
6.   Record the voltage values shown in the ammeter connected to each resistor.
7.   Take readings for different values of input voltage and tabulate them. 
CIRCUIT DIAGRAM:
a.   KVL:
<img width="984" height="557" alt="kvl" src="https://github.com/user-attachments/assets/1017921c-4796-4003-a6b1-57acdb67acc1" />

b.  KCL:
<img width="1235" height="573" alt="kcl" src="https://github.com/user-attachments/assets/c6283cc5-fc57-4470-8665-e32d3abf9639" />

Calculation:

a.   KVL:

$$
\begin{aligned}
V=V_{1}+ V_{2}+V3\to \left( 1 \right)\\
100=IR_{1}+IR_{2}+IR_{3}\\
R_{eq}=R_{1}+R_{2}+R_{3}\\
R_{eq}=180\Omega\\
I=\frac{V}{R_{eq}}=\frac{100}{180}=0.055A\\
\\
V_{1}=V30\Omega=IR_{1}=0.556X30=16.68V\\
V_{2}=V50\Omega=IR_{2}=0.556X50=27.8V\\
V_{3}=V100\Omega=IR_{3}=0.556X100=55.6V\\
\\
Sub. V_{1},V_{2},V_{3} in \left( 1 \right)\\
100=16.68+27.8+55.6=100\\
100V=100V\\
Hence, Proved
\end{aligned}
$$ 

b.  KCL:

$$
\begin{aligned}
At\enspace node\enspace A:\\
I_{30\Omega}=I_{50\Omega}+I_{100\Omega}\\
I_{30\Omega}=\frac{100-V}{30}\\
I_{50\Omega}=\frac{V}{50}\\
I_{100\Omega}=\frac{V}{100}\\
\frac{100-V}{30}=\frac{V}{50}+\frac{V}{100}\\
\frac{100-V}{30}=\frac{V}{5}+\frac{V}{10}\\
1000-10V=9V\\
19V=1000\\
V=\frac{1000}{19}\\
V=52.63\\
\\ \\
I_{30\Omega}=\frac{100-V}{30}=\frac{100-52.63}{30}=1.58A\\
I_{50\Omega}=\frac{V}{50}=\frac{52.63}{50}=1.05\\
I_{1000\Omega}=\frac{V}{100}=\frac{52.63}{100}=0.53A\\
\\ \\
At\enspace node\enspace A:\\
I_{30\Omega}=I_{50\Omega}+I_{1000\Omega}\\
1.58A=1.05A+0.53A\\
1.58A=1.58A\\
\\
Hence,Proved\\
\end{aligned}
$$

Tabulation:

a.   KVL:
|KVL|SOURCE(V)|$$V_{30\Omega}$$|$$V_{50\Omega}$$|$$V_{100\Omega}$$|$$V_{30\Omega}+V_{50\Omega}+V_{100\Omega}(V)$$|
|---- |-----|----|----|---|-----|
|Theoretical|100|16.68|27.8|55.6|100.05|
|Practical|100|16.68|27.8|55.6|100.08| 

b.  KCL:
|KCL|$$I_{30\Omega}$$|$$I_{50\Omega}$$|$$I_{100\Omega}$$|$$V_{A}$$|
|----|----|----|-----|----|
|Theoretical|-1.58A|1.05A|0.53A|52.63A|
|practical|-1.58A|1.05A|0.53A|52.63A|


RESULT:

Thus, for the given circuit, Kirchhoff’s Laws, (a) KVL and (b) KCL are proved.
