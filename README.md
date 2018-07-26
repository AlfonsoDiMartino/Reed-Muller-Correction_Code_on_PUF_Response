# Reed-Muller_Correction_Code_on_PUF_Response
VHDL implementation of Reed-Muller Coder and Decoder for SSD exam. 

The Reed-Muller Code is used in PUF-based authentication protocol such a error-correction tecnique. In the Enrollment Phase it is used to encode secret random number cs to Cs, while in the Verification Phase it is used to decode the noisy version Cs'. 
The main feature of this component is that it is completely generic and customizable. The decoder is based on a majority voter, created using a parallel counter block, a generic adder and a generic comparator. 

This project was developed for Secure System Design exam in collaboration with https://github.com/piliguori and https://github.com/SalvatoreBarone.
