# ***4-BIT-Binary-Code-Converter***
## *YouTube Presentation Video [https://youtu.be/LKjUK4XkPTA?si=LpwLQKzt9dTyg0jz](https://youtu.be/LKjUK4XkPTA?si=LpwLQKzt9dTyg0jz)*
## ***Abstract***
This Project discusses the conversions of various binary codes from one form to another. A code converter is a logic circuit that changes data presented in one type of binary code to another type of binary code, such as binary to gray code, gray code to binary, BCD to excess-3 code and excess-3 code to BCD. 
The group of symbols is called as code. The digital data is represented, stored and transmitted as group of bits. This group of bits is also called as binary code. Binary codes can be classified into two types and they are weighted codes and non-weighted codes. If the code has positional weights, then it is said to be weighted code. Otherwise, it is an unweighted code. Weighted codes can be further classified as positively weighted codes and negatively weighted codes. 
Coding is the process of translating the input information which can be understandable by the machine or a particular device. Coding can be used for security purpose to protect the information from steeling or interrupting. Code converters are used to convert the information into the desired code. These are basically encoders and decoders which converts the data into an encoded form. The four types of codes which are included in this project are Excess-3, BCD, Gray code and Binary.  

## ***Introduction***
A 4-bit binary code converter is a circuit that can convert a 4-bit binary code represent
from one form to another.

The excess-3 code (or XS3) is a non-weighted code used to express code used to
express decimal numbers. It is a self-complementary binary coded decimal (BCD)
code. Excess-3 codes are unweighted and can be obtained by adding 3 to each
decimal digit then it can be represented by using 4 bit binary number for each digit.

BCD code or Binary coded Decimal codes. It is a numeric weighted binary codes,
where every digit of a decimal number is expressed by a separate group of 4-bits.
There are various BCD codes like 8421, 2421, 5211, etc. The BCD code is also known
as the 8421 code.

Gray code is a non-weighted code. The successive gray code differs in one bit
position only that means it is a unit distance code. It is also referred as cyclic code. It
is not suitable for arithmetic operations. It is the most popular of the unit distance
codes. It is also a reflective code.

Binary code in electronics refers to the representation of data and information using
only two digits, 0 and 1. In digital electronics, binary codes are used to store, process
and transmit information in computers and other digital devices. The binary system
uses only two digits, 0 and 1, to represent all types of data, including numbers, letters,
and special characters. The binary code is converted into electrical signals that can
be processed and manipulated by electronic circuits. The binary system is a
fundamental concept in digital electronics and forms the basis of modern computing.

Binary to Gray code conversion: The Binary to Gray code conversion involves
converting a binary number into a gray code number. The gray code is a non-weighted
code where only one bit changes between consecutive values. The conversion is
performed by XORing the binary number with its right shift by 1 position.

BCD to Excess-3 conversion: BCD to Excess-3 conversion involves converting a BCD
number into an Excess-3 number. In the Excess-3 code, the decimal equivalent of
each code is 3 more than the BCD code. For example, if the BCD code is 1001, its
Excess-3 code will be 1100.

Gray code to Binary conversion: The Gray code to Binary conversion involves
converting a gray code number into its equivalent binary number. The conversion in
general is performed by starting with the least significant bit (LSB) and XORing it with
the previous bit. This process is repeated for each bit, starting from the LSB, to get the
equivalent binary number.

Excess-3 to BCD conversion: The Excess-3 to BCD conversion involves converting
an Excess-3 code into its equivalent BCD code. The conversion in general is
performed by subtracting 3 from each digit in the Excess-3 code. For example, if the
Excess-3 code is 0100, its BCD code will be 0001.

## ***Design and Implementation***
A 4-bit binary code converter can be designed and implemented using different
techniques such as hardware circuitry or software algorithms.
The Circuit is designed using multiplexer (MUX) and demultiplexer (DEMUX) along
with Logic gates like OR, AND, NOT and XOR.
### ***Block diagram of the Code Converter Circuit*** ###
![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/f7503480-1f66-4b40-9ebe-5f2abc508a19)

### ***Code Converter Circuit Diagram*** ###

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/0a53c13a-1ec3-4e0c-b7d3-8cef2eaf1e6c)

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/c2812aea-0929-4ffd-a28c-4eecb6515502)

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/a5f747ed-a7ab-4d02-86a7-cad477d0c225)




## ***Tech Stack***
KiCAD software was used for the design of the circuit.

## ***Hardware Components***
1. IC 74153 (Dual 4-input multiplexer) - 8

2. IC 74139 (Dual 2-to-4 line Decoder) - 1

3. IC 7432 (Quad OR Gate) - 1

4. IC 7486 (Quad XOR Gate) - 2

5. IC 7408 (Quad 2 input AND gate) - 1

6. IC 7404 (Hex Inverter) - 2

7. LM7805 IC (5V voltage regulator) - 1

8. Cathode 7-segment display - 4

9. 9V battery - 1

10. Diodes (1N4007) - 16

11. 6 Pin Button Switch - 6

## ***Hardware Components Description***

1. IC 74153 (Dual 4-input multiplexer)
The multiplexer, shortened to “MUX” is a combinational logic circuit designed
to switch one of several input lines through to a single common output line by
the application of a control signal. IC 74153 is a multiplexer IC (Integrated
Circuit) that allows the user to select one of four inputs and send it to the output.
It has four data inputs (A0, A1, A2, A3), a selection input (S1, S0) to choose
one of the four inputs, and an output (Y).

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/db405b40-9745-443f-98ea-a44f1883c45f)

2.IC 74139 (Dual 2-to-4 line Decoder)
IC 74139 is a dual 2-to-4 line decoder/demultiplexer integrated circuit. It has
two inputs (A, B), two selection inputs (S1, S0), and four outputs (Y0, Y1, Y2,
Y3). The device is used to convert two binary inputs into four outputs, where
only one output is active at a time based on the selection inputs.

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/2caf4772-4830-4f19-9200-df38275f7c4c)

3.IC 7432 (Quad OR Gate)
IC 7432 is a logic gate IC which consist of four OR Gates. The OR gate
performs logical OR operation. The OR gates come in form of DIP package
ICs. Each gate has three terminal two inputs and one output. The OR gate
outputs a high (1) signal if one or both of its inputs are high (1), and outputs a
low (0) signal if both inputs are low (0). The inputs of the OR gate are labeled
A and B, and the output is labeled Y.

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/97c87621-5a01-481c-9e9a-8f9770db1079)

4.IC 7486 (Quad XOR Gate)
The IC 7486 is a quad 2-input XOR gate integrated circuit. It consists of four
independent gates, each of which performs the logical exclusive OR (XOR)
function. The XOR gate outputs a high (1) signal if one, but not both, of its
inputs are high (1), and outputs a low (0) signal if both inputs are either high
(1) or low (0). The inputs of the XOR gate are labeled A and B, and the output
is labeled Y.

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/7a56446c-653d-46c5-9d99-1ba115a63802)

5.IC 7408 (Quad 2 input AND gate)
The IC 7408 is a quad 2-input AND gate integrated circuit. It consists of four
independent gates, each of which performs the logical AND function. The AND
gate outputs a high (1) signal if both of its inputs are high (1), and outputs a
low (0) signal if one or both inputs are low (0). The inputs of the AND gate are
labeled A and B, and the output is labeled Y.

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/b45910d9-e984-430d-bfa9-bd5c1c4594ac)

6.IC 7404 (Hex Inverter)
The IC 7404 is a hex inverter integrated circuit. It contains six independent
inverter gates, each of which performs the logical NOT function. The NOT
function, also known as inversion, outputs a low (0) signal if its input is high
(1), and outputs a high (1) signal if its input is low (0). The input of the inverter
gate is labeled A, and the output is labeled Y.

![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/e4cc5374-c9a2-4a35-a6dd-9ac1f1dba3f1)

## ***Working***

The 4-bit binary code converter Circuit using Demultiplexer (DEMUX) and Multiplexer
(MUX) works as follows:

 Initially the DEMUX is used to select a Particular Conversion, the output of the
DEMUX is applied to the enable of the MUX. The DEMUX is used to select a
particular binary conversion out of 4 different conversion. The selection lines of
the DEMUX determine the Conversion which has to be performed.

 The inputs A, B, C, D is given once after selecting the conversion which is
needed to be performed.

 The logic Gates Like OR, NOT, AND, XOR are Used to Perform Operations on
inputs C and D and the outputs of the Logic Gates is then applied to the inputs
of the MUX.

 The MUX is used to map the Logic gates input to output and the conversion to
gray code or Excess-3 code or binary is performed. The selection lines of the
MUX that is A and B determine the mapping of the binary code to the gray code
or Excess-3 code.

 The outputs of the MUX represent the converted code in the desired format.
 The Converted output is displayed on the 7 Segment displays along with the
LEDs.
## ***Truth Table***
![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/a0e18eb5-2c1d-4ce2-a144-bfd64acfc321)
![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/658f1e63-390e-4270-ab21-4a9fb3b0a45d)
![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/4004b224-3fdc-46db-9afe-23b481380b11)
![image](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/6e43e89e-a0f7-4a5a-86a3-388f9a4e1920)


##	***Project Gallery*** ##
![photo_3_2023-09-17_11-48-13](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/f13eaac6-84f7-4d7e-9c9a-419d8c816889)

![photo_4_2023-09-17_11-48-13](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/cbdacbb1-e56b-455f-a75d-cc50b6a716ef)

![photo_2_2023-09-17_11-48-13](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/d1759e0e-fc70-4131-8d6d-bee2da5a36b4)

![photo_2_2023-09-17_11-48-13](https://github.com/tusharshenoy/4-BIT-Binary-Code-Converter/assets/107348474/e70e231a-070f-4cb9-a5a0-130bcebafbc2)



##	***Results and Discussion*** ##

Result:
The 4 Bit Binary Code Converter was successfully implemented using relative ICs on
the breadboard. The results showed that the conversion process was fast and efficient
with minimal delay. The circuit design was able to accurately convert Binary to Gray
code, BCD to Excess-3, Gray code to Binary and Excess-3 to BCD. The results of the
4-bit binary code converter are accurate and consistent as long as the binary numbers
are correctly represented.

Discussion:
The 4-bit binary code converter is a useful tool for converting Binary to Gray code,
BCD to Excess-3, Gray code to Binary and Excess-3 to BCD.
The implementation of the 4-bit binary code converter can be done using hardware
components or software algorithms. Both methods have their advantages and
limitations. The hardware implementation provides faster and more efficient
conversion but can be expensive and complex to design.

4-bit binary code converter is a digital circuit that can convert a 4-bit binary code into
different data encoding formats, such as Gray code, BCD (Binary-coded Decimal), and
Excess-3. The conversion is performed using logical operations, such as XOR, AND,
OR gates and by using multiplexers (MUX) and Demultiplexers (DEMUX).The 4-bit
binary code converter provides versatility in digital systems, enabling efficient and
accurate data storage, transmission, and processing. It can be used for binary
arithmetic operations, error detection and correction, digital displays, and data
encoding. In summary, the 4-bit binary code converter is a fundamental component in
digital systems, providing essential data conversion capabilities that support the
functioning of more complex digital circuits.

##	***Conclusion*** ##

The circuit was implemented through Demultiplexer (DEMUX), Multiplexer (MUX) and
Logic gates the inputs were given by 6 Pin Button Switch and the Output bits are
connected to LED’s and 7 segment displays. In conclusion, the 4-bit binary code
converter is a crucial component in many digital systems, and it provides a simple and
effective way to convert binary to other forms. The project involves the design and
implementation of a circuit that can convert 4-bit binary codes into different data
encoding formats, such as Gray code, BCD (Binary-coded Decimal), and Excess-3
The results of the converter can be used in various applications, including digital
circuits, computer science, and communication systems, making it an essential tool
for modern technology.

Overall, the 4-bit code converter project is a great opportunity to deepen one's
understanding of digital systems and gain practical experience in circuit design and
digital logic.

##	***References*** ##

[1] Binary to Gray code conversion: [https://www.javatpoint.com/binary-to-gray-codecconversion-in-digital-electronics](https://www.javatpoint.com/binary-to-gray-code-cconversion-in-digital-electronics)

[2] Binary to Excess-3 conversion: [https://www.geeksforgeeks.org/code-convertersbcd8421-to-from-excess-3/](https://www.geeksforgeeks.org/code-converters-bcd8421-to-from-excess-3/)

[3] LM7805 data sheet : Data sheet acquired from SLVS056J – MAY 1976 – REVISED MAY 2003,Texas Instruments, for µA7800 SERIES POSITIVE-VOLTAGE REGULATORS [https://www.sparkfun.com/datasheets/Components/LM7805.pdf](https://www.sparkfun.com/datasheets/Components/LM7805.pdf)

[4] IC 74153 Data Sheet [https://datasheetspdf.com/pdf/248155/NationalSemiconductor/74153/1](https://datasheetspdf.com/pdf/248155/NationalSemiconductor/74153/1)

[5] IC 74139 Data Sheet [https://www.futurlec.com/74LS/74LS139.shtml](https://www.futurlec.com/74LS/74LS139.shtml)



