CrossLink I2C Hardened IP write Operation.


input	     reset_i,
input  wire  clk_i,		
//-----------------------------------------------		
input  wire [9:0] i2c_reg_num,
output wire [9:0] memArray_addr,
input  wire [7:0] memArray_dat,	
//-----------------------------------------------	
	
output wire [3:0] ip_adri_out,
output wire [9:0] ip_dati_out,
output wire ip_csi_out,    
output wire ip_stbi_out,
output wire ip_wei_out,
    
input  wire [9:0] ip_dato_in,
input  wire ip_acko_in,    	
	
output wire i2c_conf_done