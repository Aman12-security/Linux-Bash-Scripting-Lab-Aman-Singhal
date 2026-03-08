# Experiment 1: Linux Installation Using Virtual Machine

## Aim
To install and configure a Linux operating system using a virtualization tool (Oracle VirtualBox or VMware Workstation) by importing an OVA file and preparing the system for Linux command-line and Bash scripting experiments.

## Objective
- Understand virtualization concepts
- Import and deploy a Linux OVA appliance
- Configure VM settings (RAM, CPU, Network)
- Verify Linux installation
- Prepare the environment for command-line and Bash scripting tasks

## Theory
Virtualization allows multiple operating systems to run on a single physical computer using virtual hardware. A Virtual Machine (VM) behaves like a real computer but runs inside software.

An OVA (Open Virtual Appliance) file is a preconfigured virtual machine package that contains an operating system, installed tools, and system configurations. Importing an OVA file simplifies deployment compared to manual OS installation.



## Procedure

### Step 1: Install VirtualBox
Download and install Oracle VirtualBox from the official website.

### Step 2: Import the OVA File
1. Open VirtualBox
2. Click File → Import Appliance
3. Select the provided `.ova` file
4. Click Next
5. Review settings and click Import

### Step 3: Configure Virtual Machine
- RAM: Minimum 2048 MB
- CPU: 2 cores
- Network Adapter: NAT

### Step 4: Start the Virtual Machine
1. Click Start
2. Wait for Linux to boot
3. Login using credentials
4. Open Terminal

## Verification Commands
