# CD_FLUP
This repository contains the generated instances for CD_FLUP

#for E_d_kl 
try:
   E_d_kl=np.fromfile(path+"/E_d_kl"+str(idx)+".bin",dtype=np.int)
   E_d_kl.shape=K,L
except:
   E_d_kl=np.fromfile(path+"/E_d_kl"+str(idx)+".bin")  
   E_d_kl.shape=K,L
#for A_ki
try:
   A_ki=np.fromfile(path+"/A_ki"+str(idx)+".bin",dtype=np.int)
   A_ki.shape=K,I
except:                     
   A_ki=np.fromfile(path+"/A_ki"+str(idx)+".bin")
   A_ki.shape=K,I     
try:
   M_l=np.fromfile(path+"/M_l"+str(idx)+".bin",dtype=np.int)
except:                     
   M_l=np.fromfile(path+"/M_l"+str(idx)+".bin")
S_i=np.fromfile(path+"/S_i"+str(idx)+".bin")
E_i=np.fromfile(path+"/E_i"+str(idx)+".bin")
