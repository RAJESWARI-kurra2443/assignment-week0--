
# assignment-week0--
Resizing the Ubuntu window to fit the screen



$ sudo apt update




$ sudo apt install build-essential dkms linux-headers-$(uname -r)



$ cd /media/spatha/VBox_GAs_7.1.8/


$ ./autorun.sh



TOOL CHECK



<img width="788" height="199" alt="Screenshot from 2025-09-20 16-19-14" src="https://github.com/user-attachments/assets/6542120d-3bbf-425d-8f4e-ad2f40cedbb3" />



Yosys


$ sudo apt-get update


$ git clone https://github.com/YosysHQ/yosys.git


$ cd yosys


$ sudo apt install make       

# If make is not installed


$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev


    
$ make config-gcc


# Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make


$ git submodule update --init --recursive


$ make 


$ sudo make install


Alt Text


<img width="799" height="207" alt="Screenshot from 2025-09-20 16-20-18" src="https://github.com/user-attachments/assets/f85766fb-d0d5-4b9f-a5cb-c21f0274b682" />



Iverilog


$ sudo apt-get update


$ sudo apt-get install iverilog


Alt Text

gtkwave
$ sudo apt-get update
$ sudo apt install gtkwave
Alt Text
<img width="998" height="626" alt="Screenshot from 2025-09-20 16-46-29" src="https://github.com/user-attachments/assets/3831b1a4-8a7a-4520-bdf9-7c45d6b729f8" />
