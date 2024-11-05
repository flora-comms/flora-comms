# FLoRa Communications

Hello! We are FLoRa Communications.
We are three Electronics and Computer Engineering Technology students at Camosun College in Victoria, BC, Canada, and this is our capstone semester project.
We are building an emergency communications network that can extend cellular coverage deep into remote wilderness areas, is accessible for anyone with a smartphone, and for the fraction of the cost of a cellular network upgrade.

We are currently building a proof-of-concept prototype called the Petal Radio (see photo below) and a network stack & web application called AVAlink. 
The Petal uses LoRa digital radio to send text messages over long distances through a "mesh" network with very low power draw.
The Petal is highly efficient and is designed to run on batteries and solar power.
In the future, the network will tie into existing cell networks and allow users to communicate with rescue services.

![Petal](https://github.com/user-attachments/assets/99636dc9-3c5e-4dd9-85fc-07d69e1258d2)

The AVAlink network is made up of multiple Petal Radios, or _nodes_. Nodes will be placed a few hundred to several thousand metres apart in remote locations that see lots of casual visitors, like ski resorts, popular hiking trails, or national parks.
A person in distress will be able to
1. Go to a Petal Radio node powered by solar and batteries.
2. Press a button to activate the node.
3. Connect to the AVAlink Wi-Fi network provided by the node.
4. Scan a QR code or navigate to "avalink.local" in their browser.

The Petal Radio will serve our web application where a simple and intuitive messaging interface will appear (sample below). Previous messages from other nodes will appear like one big network-wide group chat.
The user can send messages to this public forum, or press the SOS button to signal distress and contact emergency services.

![avalink layout](https://github.com/user-attachments/assets/d5fd395c-557e-4b48-9877-57e4437c1610)


# Navigating Our Repositories

We have three repos we use to organize development of AVAlink: flora-docs, flora-hardware, and flora-software.
Project progress is mangaged by the Capstone Development Management GitHub project, and all issues and milestones from these repos are linked to this project.

## flora-docs

This repo contains documentation related to school assignments, branding, and project management. 
Here, you can find our presentation material, branding, requirement specifications, budget, and schedule.
We also keep our group meeting minutes in this repo along with documentation templates.

## flora-hardware

This repo contains hardware design files, assembly notes, testing procedures, and testing results.

## flora-software

This repo contains our software and firmware. The main branch is generally stable, and other branches are unstable and under development.

<!---
flora-comms/flora-comms is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
