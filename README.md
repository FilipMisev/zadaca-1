# zadaca-1
Every 30ms an isolated port with address 0Ah is read
data. If bits 2 and 5 are 1 and 0 respectively in memory
mapped port at address F00Ah is sent read
data divided by 2, otherwise the read data is sent
multiplied by 7. The frequency of the oscillator crystal is
5MHz.

 If bit 2,5==1,0 If bit 2,5==1,0 If bit 2,5==1,0
 F00Ah Data/2
 Else
 F00Ah Data*7 

![Screenshot (1)](https://github.com/tamaraatanasova/8085-Zadaca1/blob/main/image1.png)
