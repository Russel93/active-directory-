# Install the domain controller

1. use 'sconfig' to 
    -   Change the hostname
    -   Change the IP address to static
    -   Change the DNS server to our own IP address

2. Install the Active Directory windows feature

``` shell

    Install-Windowsfeature AD-Domain-Services -IncludemanagementTools
```

https://xpertstec.com/how-to-install-active-directory-windows-server-core-2022/#:~:text=Install%20Active%20Directory%20Core%20Server%202022&text=In%20Windows%20Admin%20Center%20very,then%20install%20the%20ADDS%20role.&text=If%20required%2C%20please%20reboot%20the%20server.