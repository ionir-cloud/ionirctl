# ionirctl
using ionirctl to run ionir commands remotely using REST APIs



## To install Ionir CLI perform the following steps (on a linux machine)
1.	Copy relevant ionirctl.<locale> files to your local folder
    You can use the following command to copy the directory:
    
    ``` kubectl -n ionir cp ionirctl-0:install <destination dir> ```
2.	Copy ionir_install.sh to your local folder
3.	Run
    ```ionir_install.sh -l <locale> ```
    with the relevant locale. Default value is en-US



### Note: you may need to add execute permissions (chmod +x) to the install.sh file 
###      Required packages - bash ; bash-completion curl miller jq

4.	Run the following command to complete the installation:
    ``` source ~/ionirctl_bash_completion```


##To configure the cluster url and the user credentials run the following command
``` ionirctl configure ```

Ionir Cluster DNS/IP []: <cluster-url>
User: <user>
Password: <Password
