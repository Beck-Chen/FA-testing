# FA-testing
A general testing script for failure analysis purpose

This project is consisted of a serial of shell scripts including:
  A. systeminfo.sh to gather system hardware/firmware configuration;
        A1.BIOSinfo.sh
        A2.BMCinfo.sh
        A3.Procinfo.sh
        A4.Meminfo.sh
        A5.Diskinfo.sh
        A6.NICinfo.sh
        ...
       
  B. stess.sh to burn-in key parts
        B1. cpustress.sh
        B2. memstess.sh
        B3. diskstress.sh
        B4. nicstress.sh
        ...
        
  C. compare configuration before and after burn-in test
        c1.cmpconfig.sh
      
  D. log system
        d1. testlog.sh
     
         
