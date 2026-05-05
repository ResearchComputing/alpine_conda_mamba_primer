## RC Primer: Installing Software on Alpine with Conda and Mamba


Research software is often complex and difficult to manage, particularly on shared 
high-performance computing systems like the [Alpine cluster](https://www.colorado.edu/rc/alpine) 
housed at CU Boulder. [Conda](https://docs.conda.io/en/latest/) is an open-source software and 
environment management system that makes it easy to install complex software packages and their 
dependencies. Conda supports multiple languages and is particularly well-suited for managing 
Python and R software environments. In this RC Primer* we will cover using Conda, and its newer, 
faster relative, [Mamba](https://mamba.readthedocs.io/en/latest/), to create Python and R 
environments on the Alpine cluster.

In order to follow along with the hands-on component of this workshop, you’ll want to have a 
Research Computing account. If you need assistance with creating an account, see the 
[RC Quick Byte - Getting a Research Computing Account](https://github.com/ResearchComputing/Getting_An_Account).

The ability to navigate a Linux environment is useful, but not required for this training. If you would like to 
develop your understanding of Linux, see the [RC Short Course - Supercomputing Spinup 1: Working with Linux](https://github.com/ResearchComputing/Supercomputing_Spinup/tree/main/linux_bash_spinup).


* _What is an RC Primer?: An RC Primer is a session that provide an introduction to concepts, systems, and tools. 
You can expect to leave "Primers" with an introductory-level understanding of the topic_.

--- 

We aim to make our online resources accessible to everyone. 
If you encounter any barriers in the materials contained in this repository, please report them through our support request form
https://colorado.service-now.com/req_portal?id=ucb_sc_rc_form
