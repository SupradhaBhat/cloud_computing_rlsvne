RLSVNE CloudSim Simulator

Overview:\
This repository contains a Java implementation of the RLSVNE (Resource and Link-aware Service Function Chaining Virtual Network Embedding) algorithm using the CloudSim library. RLSVNE is a heuristic algorithm designed for efficient virtual network embedding in cloud environments.

Introduction:\
The RLSVNE algorithm is implemented in Java using the CloudSim library. It simulates the embedding of virtual nodes onto substrate nodes in a cloud environment, considering resource availability and link relations.

Features:\
RLSVNE Algorithm: Efficient virtual network embedding heuristic.\
CloudSim Integration: Utilizes the CloudSim library for network datacenter simulations.\
Modular Structure: Easily adaptable and extendable for further experimentation.

Requirements:\
Java Development Kit (JDK)\
CloudSim library (included in the lib folder)

Usage:\
Clone the repository: git clone https://github.com/your-username/your-repo.git\
Open the project in your favorite Java IDE.\
Run the RLSVNESimulator class.

Code Structure:\
RLSVNESimulator.java: Main class containing the RLSVNE algorithm and simulation setup.\
NetworkVm.java: Represents virtual and substrate nodes in the simulation.\
UtilizationModelDynamic.java and UtilizationModelFull.java: Utilization models for dynamic and full resource usage.
