# Cisco Switch Configuration Lab - Physical Setup Guide

# Lab Overview

This guide provides step-by-step instructions for configuring a Cisco switch using physical equipment in a computer lab environment.

# Pre-Lab Checklist

- Cisco switch powered OFF

- PC powered OFF

- Console cable available

- Ethernet cable available

- Network rack access

# Physical Setup Steps

# Step 1: Identify Your Workstation

- Location: Row 2, Seat 5

- PC Designation: PC-A

- Switch Location: Network rack

# Step 2: Console Connection Setup

1. Connect Console Cable:

- Switch end Upper Switch (R2 L1 1 / TOP PWR CH1): Connect to switch Console port

- PC end (C5): Connect to PC USB port 
  
  ![Console](https://github.com/VivianGoshashy/packet-tracer-basic-switch-config-physical-mode/blob/17bd5eb62dd0d11dd9d7d32691e82fa7222bf3b3/Image2/console.jpeg)


2. Identify COM Port:

- Power ON PC-A

- Open Device Manager

- Navigate to Ports (COM & LPT)

- Note: USB Serial Port (COM4)

# Brief Explanation:
COM4 is your digital key to the switch's configuration interface. Without it, the switch is just a 'black box' with it, you have complete control over the device's configuration and operation.

This single sentence powerfully captures the entire purpose of the console connection in the lab. It highlights:

- The Essential Tool: COM4 (the serial console).

- The Core Function: It's the "key" that unlocks the switch.

- The "Before" State: A useless "black box."

- The "After" State: A device under your "complete control."

  ![Port](https://github.com/VivianGoshashy/packet-tracer-basic-switch-config-physical-mode/blob/d1f5928b8d14210ce00ddeb5a94e0172bb368f78/Image2/port%20com4.png)

# Step 3: Configure Serial Connection

1. Open PuTTY:

- Connection type: Serial

- Serial line: COM4

- Click Open
  
  ![PuTTY]()

2. Establish Connection:

- Press Enter to activate console session

- You should see switch prompt: Switch>



