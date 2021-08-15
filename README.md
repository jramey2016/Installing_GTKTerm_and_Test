# Installing_GTKTerm_and_Test
This is a quick and simple comprehesive tutorial on how to install GTKTerm onto your Linux Ubuntu VM for our project.

We use GTK Term to communicate with the serialport. GTK term features: serial port window, Serial Port Setup (speed, parity, bits, etc), send RAW data, congigurations to control lines manually (DTR, CTS), and reads the state of the control lines (RTS,CD,DSR,RI).

## Pre-requisites
- [Setting up VM Environment](../virtual_machine_setup/tutorial.md)

# Steps

1.) Launch your terminal and enter the gollowing commands"

     ```bash
    sudo apt update
    sudo apt install gtkterm
    ```
 2.) Next, we will configure the settings for the Ultra96V2. Make sure that you board in correctly hooked up to your computer. We will start by going to Devices > USB > Xilinx JTAG+Serial[0700], click this option and launch GTK Term.
 
 ![USB config](https://user-images.githubusercontent.com/72533453/129467839-e82eaafd-c3bb-41c7-b2db-7dfb6909b177.png)

 
