# Critical Control 1 - Inventory of Authorized and Unauthorized Devices 
Actively manage (inventory, track, and correct) all hardware devices on the network so that only authorized devices are given access, and unauthorized and unmanaged devices are found and prevented from gaining access.

## ID.AM-1 Physical devices and systems within the organization are inventoried
Creating an up-to-date inventory of what systems are on your network is hard. The only way to do this is automation. If you would manually input each system in and remove them when they are end-of-life you create an overhead which is not necessary.

### The Accounting Records
Our first source for information are the accounting records. Since accounting should have track of what systems are bought and paid for you should somehow find them on your network or the system is considered missing/stolen.

When you introduce a system into your inventory it has an entry date and a retirement date. After the retirement date the system should not be on your network anymore. The accountant knows when the system is considered (accounting-wise) deprecated. You can start with that date. It is often considered 3 to 5 years.  

### The Network
By tapping the network or gathering flow records at the right points you will get insight who is talking to who. By using our logs we can correlate IP addresses with MAC addresses which are part of the Network Interface Card which sits in a computer/IoT/ICS.

We can for example leverage the log files from the DHCP server, the switch its CAM table and the firewall together with a network tap at the egress point of the network and build a map of what we see. The list of systems detected on a network is dynamic. 

Each new system detected should go to a screening procedure to check if the system belongs to you or meets the criteria to get access to the network. This technology is called network access control (NAC).

## ID.AM-2 Software platforms and applications within the organization are inventoried
## ID.AM-3 Organizational communication and data flows are mapped
## ID.AM-4 External information systems are catalogued
## ID.AM-5 Resources (e.g., hardware, devices, data, time, personnel, and software) are prioritized based on their classification, criticality, and business value
## ID.AM-6 Cybersecurity roles and responsibilities for the entire workforce and third-party stakeholders (e.g., suppliers, customers, partners) are established
