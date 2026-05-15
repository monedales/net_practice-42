*This project has been created as part of the 42 curriculum by maria-ol.*

# NetPractice

## Description

NetPractice is a networking training project from the 42 curriculum focused on understanding and applying fundamental networking concepts.
The main goal is to configure small network topologies by correctly assigning IP addresses and routing information so that all devices can communicate as expected.

Through a series of 10 progressive levels, the project helps students develop a practical understanding of how data flows through a network, how devices are interconnected, and how addressing and routing decisions affect connectivity.

The project is completed using an interactive web-based interface provided by 42, without writing code, but by applying theoretical networking knowledge in a practical way.

## Instructions

### Training Mode

1. Open the NetPractice training interface by launching the provided `index.html` file in a web browser.
2. Select **"Training"** mode.
3. Enter your 42 intranet login in the field provided (required for your personal configuration).
4. Click **"Start"**.
5. A non-functioning network diagram will appear — configure it by filling in the unshaded fields:
   - IP addresses
   - Subnet masks
   - Default gateways
   - Routes
6. Click **"Check again"** to verify whether your configuration is correct.
7. If the level is complete, a **"Next level"** button will appear — click it to proceed.

> You can also use the **"Evaluation"** tab for a random configuration, which simulates the peer-evaluation environment.

### Exporting Configurations

- After successfully completing each level, click the **"Get my config"** button to download your configuration file.
- Each level generates one configuration file.
- Export the file **before** moving to the next level.

### Submission Details

- A total of **10 exported configuration files** must be submitted — one per level.
- All 10 files must be placed **at the root of the Git repository** before submission.
- Make sure your 42 login is entered in the interface before exporting, as the files are generated based on it.

## Resources

### Networking Concepts Studied

This project involves studying and applying the following networking concepts:

- TCP/IP addressing
- Subnet masks
- Default gateway
- Routers and switches
- Hub vs. Switch vs. Router
- IPv4 vs. IPv6
- OSI model layers
- Network segmentation and routing between subnets

### Study Materials: Video Resources

* [Hub, Switch & Router](https://www.youtube.com/watch?v=1z0ULvg_pW8&t=1s)
    - **Hub**: a signal replicator — it broadcasts data to all devices on the network.
    - **Switch**: similar to a hub, but keeps a MAC address table to send data only to the intended destination device.
    - **Router**: reads the IP address of a data packet and forwards it across networks until it reaches the intended device.

* [Default Gateway](https://www.youtube.com/watch?v=pCcJFdYNamc)
    - A **default gateway** is the device a host uses to send data outside its own network.

### Study Materials: Text Resources

* [IPv4 Addresses, Routing and Subnet Masks – CodeQuoi](https://www.codequoi.com/en/ipv4-addresses-routing-and-subnet-masks/#the-internets-hardware)
    - Explains how IPv4's 32-bit addresses uniquely identify devices and enable packet routing across the Internet via hierarchical addressing and routing tables, why IPv6's 128-bit addresses are replacing IPv4 to solve address exhaustion, and covers the physical components of the Internet (routers, switches, links).

### Use of Artificial Intelligence

AI tools were used during this project in a limited and controlled manner:

- **Claude (Anthropic)** was used to:
  - Clarify specific networking concepts such as subnetting, CIDR notation, and routing tables.
  - Help understand how subnet masks determine network and host portions of an IP address.
  - Review and improve the structure and clarity of this README file.

AI was **not** used to directly solve the exercises or generate network configurations.
