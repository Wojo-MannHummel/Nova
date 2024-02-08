INSTALL AND UPGRADE

1.  Download and install ignition from [Download Ignition by Inductive
    Automation](https://inductiveautomation.com/downloads/)

2.  Same process to upgrade ignition will recognize and do in place
    upgrade

3.  Default credentials are user:Admin password:password

4.  Required modules for app installation.

![](media/image1.png){width="6.614583333333333in"
height="6.938952318460193in"}

5.  Modify the following files to configure Ignition

\"C:\\Program Files\\Inductive
Automation\\Ignition\\lib\\runtime\\jre-win\\conf\\security\\java.security\"

-   Recommended to increase memory allocation to following values in
    this file

\# Initial Java Heap Size (in MB)

> wrapper.java.initmemory=4096
>
> \# Maximum Java Heap Size (in MB)
>
> wrapper.java.maxmemory=8192

\"C:\\Program Files\\Inductive
Automation\\Ignition\\data\\ignition.conf\"

-   Enable 'rsa\_pkcs1\_sha1, secp224r1' by removing from disabled algos

> \# jdk.tls.disabledAlgorithms=MD5, SSLv3, DSA, RSA keySize \< 2048, \\
>
> \# rsa\_pkcs1\_sha1, secp224r1
>
> jdk.tls.disabledAlgorithms=SSLv3, TLSv1, TLSv1.1, RC4, DES,
> MD5withRSA, \\
>
> DH keySize \< 1024, EC keySize \< 224, 3DES\_EDE\_CBC, anon, NULL

6.  Gateway setting configuration

![](media/image2.png){width="6.4375in" height="0.5254538495188101in"}

> ![](media/image3.png){width="6.5in" height="0.7444444444444445in"}
