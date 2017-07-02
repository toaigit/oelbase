Build Oracle Linux from Centos (oelbase) 
   oelbase.json - main packer file  
   vars.json    - defined variables to be referenced in the main packer file.  
Command to run packer  
   packer build -var-file= vars.json oelbase.json  
  
NOTE:  we use in-line shell in this example.  
