Basic CMOS Circuits Simulated with LTspice
This repository contains simulations of basic CMOS (Complementary Metal-Oxide-Semiconductor) logic circuits using LTspice. It includes the implementation of essential CMOS logic gates: NOT, NAND, and NOR, which are fundamental for understanding CMOS technology and digital circuit design. These gates can be combined to form other logic gates such as AND and OR.

Key Features and Descriptions:
1. CMOS NOT Gate (Inverter)
The CMOS NOT gate, also known as the inverter, is the simplest logic gate. It takes a single input and produces an output that is the logical negation (complement) of the input. In CMOS technology, this gate is constructed using a combination of PMOS and NMOS transistors:
![image](https://github.com/user-attachments/assets/ee09abef-da8b-4329-9996-c61534822e3c)


When the input is high (1), the NMOS transistor conducts, pulling the output low (0), while the PMOS transistor is off.
When the input is low (0), the PMOS transistor conducts, pulling the output high (1), while the NMOS transistor is off.
This gate serves as the building block for all other logic gates, including AND, OR, and more complex digital circuits.

2. CMOS NAND Gate
The CMOS NAND gate is a universal gate that performs the negation of the AND function. It has two inputs and produces an output that is the logical negation of the AND operation:
![Screenshot 2025-03-17 095652](https://github.com/user-attachments/assets/0ecc21ad-d1f3-4bc2-8008-6fb37046e855)

If both inputs are high (1), the output is low (0).
If any one or both inputs are low (0), the output is high (1).
In CMOS implementation, this gate is made by combining two NMOS transistors in series (for the pull-down network) and two PMOS transistors in parallel (for the pull-up network). NAND gates are widely used in digital circuits because any other gate (AND, OR, NOT) can be created from just NAND gates.

3. CMOS NOR Gate
The CMOS NOR gate is another universal gate that performs the negation of the OR function. It has two inputs and produces an output that is the negation of the OR operation:
![Screenshot 2025-03-17 094916](https://github.com/user-attachments/assets/8cbfc65b-35bb-4bee-9d1f-559dfb567dc8)

If both inputs are low (0), the output is high (1).
If any input is high (1), the output is low (0).
In CMOS technology, the NOR gate is implemented by connecting two NMOS transistors in parallel (for the pull-down network) and two PMOS transistors in series (for the pull-up network). Like the NAND gate, the NOR gate is also widely used in digital logic because it can be used to construct all other logic gates.

Combining These Gates
AND Gate: An AND gate can be created by combining a NAND gate and a NOT gate. Since NAND is the negation of AND, inverting the output of a NAND gate will result in an AND gate.
![image](https://github.com/user-attachments/assets/7d396e39-c7cf-4962-b749-e1e01c4a518b)

OR Gate: An OR gate can be created by combining a NOR gate and a NOT gate. Since NOR is the negation of OR, inverting the output of a NOR gate will yield the OR function.
![image](https://github.com/user-attachments/assets/8dcb21d2-73b3-4107-8a73-a69e86911896)

These gates serve as the foundational elements in more complex digital circuits, such as adders, multiplexers, and memory elements.


Modify the circuits and parameters as needed to explore different behaviors.

Purpose:
This repository is an educational resource for learning about CMOS logic gate design and simulation. It is useful for students, engineers, and hobbyists who are interested in exploring how basic logic gates are implemented using CMOS technology and how they can be combined to form complex digital systems.

Feel free to contribute by adding new simulations, improving existing designs, or providing feedback.

