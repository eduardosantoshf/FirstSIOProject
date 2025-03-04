﻿# First SIO Project

This project aims to explore the concepts related with the assessment of **vulnerabilities**, and to acknowledge the risk and impact of **exploring common vulnerabilities**.

## Course
This project was developed under the [Information And Organisational Security](https://www.ua.pt/en/uc/4143) course of [University of Aveiro](https://www.ua.pt/).

## Install and run the VM
The compressed disk volume with a **Debian 64bits linux host** can be downloaded from the following [link](https://uapt33090-my.sharepoint.com/:u:/g/personal/eduardosantoshf_ua_pt/Ee5hwD9cZTJBjJxsFVc_lB4BiZG9rkzyZ2ctxrXshZldig?e=pA1ibx).

### Steps:
1. Obtain the disk image, create a **virtual machine**, and add the image as a **hard disk**.
2. Add a **network interface** to the virtual machine (both **Bridge** and **HostOnly** interfaces can be used).
3. Start the image, and after some time, the current **IP address** will be presented in the terminal.
4. Access that address using a web browser and you should get the page of a simple online shop.
> Note: Do **not** use a **NAT** interface as it will **not allow** you to communicate with the services

## Tasks completed
- [x]  Enumerate all **communication ports** available, describing their functionality.
- [x]  Enumerate the **operating system**, **services available**, including versions. Describe the function of each service and **validate** if the information found is coherent (that is, it’s really a specific server with that version).
- [x]  Enumerate and describe all **potential vulnerabilities** containing a [CVE Score](http://cvedetails.com) of at least **6**.
- [x]  Assess if **public exploits** are able to validate the existence of the vulnerability.
- [x]  Analyze the web page and describe the **vulnerabilities** found.
- [x] Explore the vulnerabilities found, describing each step. In the end, describe the potential **impact of the exploitation**.

## Tools
During the **exploitation** of the VM, we used the following tools:
* [nmap](https://github.com/nmap/nmap)
* [sqlmap](https://github.com/sqlmapproject/sqlmap)
* [nikto2](https://github.com/sullo/nikto)

## Grade 
This project's grade was **20** out of 20.

## Authors
* **Eduardo Santos**: [eduardosantoshf](https://github.com/eduardosantoshf)
* **Margarida Martins**: [margaridasmartins](https://github.com/margaridasmartins)
