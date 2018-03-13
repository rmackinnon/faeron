# Faeron v0.0.0-alpha

### About
This project is designed as a flexible and extensible building automation and monitoring platform.
With additional modules, support for additional technologies is possible. This project hopes
to provide such a framework for powerful monitoring, statistics gathering, automation, and management
of the majority of inside plant systems (electrical, plumbing, heating, cooling, etc.).

### Planned Features
##### Core Features
* Pipeline Style IPC
* Insertable Module Framework
* Configurable Web UI
* Cross Protocol Bridging (e.g. MQTT<->LCM)

##### Core Plugin Modules
* Roll-up Statistics Gathering and Storage
* Period Defined Polling Modules
* Event and Trigger Based Modules

### Required Packages
* \>= LCM-1.3.1

### Installation
**TODO: Section to be completed at a later date.**

### Building LCM From Source
First download or clone the source from: [http://github.com/lcm-proj/lcm]

Additional documentation about LCM can be found [here|http://lcm-proj.github.io/index.html].

From within the cloned LCM directory run the following:
```
cmake
make
make install
```