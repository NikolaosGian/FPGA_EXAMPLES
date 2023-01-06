<div id="top"></div>

<br />
<div align="center">
  <h1 align="center">FPGA Running Examples using Vivado HLS 2019.2</h1>
  <h3 align="center">Writed by Nikolaos Giannopoulos</h3>
  <h3 align="center">MEng,Electrical & Computer Engineering AUTH GR</h3>
  
</div>
<br />


<p align="center">
    This is an simple FIR filter application using 
    #pragma HLS array_partition variable=shift_reg complete //make all as registers and not BRAM's
    #pragma HLS unroll factor = 11                          // unroll as the maximum array size
    <br />
    <br />
  </p>
  
