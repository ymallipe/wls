# wls
Weblogic server 

Execution Steps
Step 1:
Update inventory info in inventory file
Step 2:
Download JAVA JDK and ORACLE Weblogic and place in below mentioned locations

Java: ~/wls/roles/java/files/<file>
OWLS: ~/wls/roles/wls/files/<file>


Step 3:
Execute below command to Install Java and WLS

$ ansible-playbook -i inventory install.yml

Above command set up Java followed by Oracle Weblogic server  
