# ☁️ Cloud Computing Lab

## CS4V51 — Cloud Computing Laboratory

This repository contains the experiments, source code, configuration files, screenshots, and results performed as part of the **Cloud Computing Lab**.

---

## 📚 List of Experiments

| Experiment | Title |
|------------|-------|
| **01** | Virtual Workstation Installation |
| **02** | C Compiler in Virtual Machine |
| **03** | Google App Engine – Hello World Application |
| **04** | GAE Launcher – Web Application |
| **05** | CloudSim – Cloud Scenario Simulation |
| **06** | File Transfer Between Virtual Machines |
| **07** | Hadoop Single Node Cluster – WordCount |
| **08** | Creating and Executing a Docker Container |
| **09** | Running a Container from Docker Hub |

---

# 🧪 Experiment 01 — Virtual Workstation Installation

### Aim
To install VirtualBox/VMware or an equivalent cloud workstation and install a Linux/Windows operating system as a guest OS.

### Tools Used
- Oracle VirtualBox / VMware
- Windows Host OS
- Linux / Windows Guest OS
- ISO Image

### Procedure
1. Install VirtualBox/VMware.
2. Create a new virtual machine.
3. Select the required ISO image.
4. Configure RAM, processor and storage.
5. Start the virtual machine.
6. Install the guest operating system.

### Result
A virtual workstation was successfully created and the guest operating system was installed and executed.

---

# 🧪 Experiment 02 — C Compiler in Virtual Machine

### Aim
To install a C compiler in the virtual machine and execute simple C programs.

### Tools Used
- VMware
- CorePlus
- C Compiler / GCC
- C Programming

### Procedure
1. Start the virtual machine.
2. Install the required C compiler.
3. Create a C source program.
4. Compile the program using the C compiler.
5. Execute the generated program.
6. Verify the output.

### Result
The C compiler was successfully installed and simple C programs were compiled and executed inside the virtual machine.

---

# 🧪 Experiment 03 — Google App Engine

### Aim
To install Google App Engine and create a Hello World web application using Python/Java.

### Tools Used
- Eclipse
- Google Plugin for Eclipse
- Google App Engine SDK
- Java / Python

### Procedure
1. Install the Google Plugin for Eclipse.
2. Configure the Google App Engine SDK.
3. Create a new Web Application Project.
4. Generate the Hello World application.
5. Run the application locally.
6. Deploy the application to Google App Engine.

### Result
A Hello World web application was successfully created, executed and deployed using Google App Engine.

---

# 🧪 Experiment 04 — GAE Launcher

### Aim
To use GAE Launcher to launch and deploy a web application.

### Tools Used
- Google App Engine
- GAE Launcher / Google Cloud SDK
- Python
- HTML
- CSS

### Procedure
1. Create the web application files.
2. Configure the `app.yaml` file.
3. Open the application using GAE Launcher.
4. Start the local development server.
5. Test the web application.
6. Deploy the application to Google App Engine.

### Result
The web application was successfully launched and deployed using Google App Engine.

---

# 🧪 Experiment 05 — CloudSim

### Aim
To simulate a cloud scenario using CloudSim and execute a scheduling algorithm.

### Tools Used
- Eclipse
- Java
- CloudSim 3.0.3
- Apache Commons Math

### Procedure
1. Install Eclipse and Java.
2. Download and configure CloudSim.
3. Add the required libraries.
4. Create a CloudSim Java project.
5. Configure datacenters, hosts, VMs and cloudlets.
6. Implement the required scheduling algorithm.
7. Run the simulation.
8. Observe the simulation results.

### Result
A cloud computing scenario was successfully simulated using CloudSim and the scheduling algorithm was executed.

---

# 🧪 Experiment 06 — File Transfer Between Virtual Machines

### Aim
To transfer files from one virtual machine to another virtual machine.

### Tools Used
- VirtualBox / VMware
- Two Virtual Machines
- USB / Shared Folder / Network

### Procedure
1. Create and start two virtual machines.
2. Configure communication or file-sharing between the VMs.
3. Transfer files using one of the following methods:
   - Copy and Paste
   - USB Drive
   - Shared Folder
4. Verify the transferred files.

### Result
Files were successfully transferred from one virtual machine to another using the available file-sharing methods.

---

# 🧪 Experiment 07 — Hadoop Single Node Cluster

### Aim
To set up a single-node Hadoop cluster and run a simple WordCount application.

### Tools Used
- Java
- Hadoop
- HDFS
- YARN
- MapReduce
- Linux

### Procedure
1. Install Java and configure SSH.
2. Install Hadoop.
3. Configure Hadoop environment variables.
4. Configure HDFS and YARN.
5. Format the NameNode.
6. Start Hadoop services.
7. Create an input directory.
8. Add input files.
9. Execute the WordCount MapReduce program.
10. Display the output.

### Result
A single-node Hadoop cluster was successfully configured and the WordCount MapReduce application was executed successfully.

---

# 🧪 Experiment 08 — Creating and Executing a Docker Container

### Aim
To create and execute a Docker container.

### Tools Used
- Docker
- Python
- Dockerfile
- Ubuntu/Linux

### Procedure
1. Install Docker.
2. Create a Python application.
3. Create a `Dockerfile`.
4. Build the Docker image.
5. Run the image as a container.
6. Verify the container output.
7. Manage the container using Docker commands.

### Example

```bash
docker build -t python-test .
docker run python-test

# 🧪 Experiment 09 — Running a Container from Docker Hub

### Aim
To run a container from Docker Hub using Docker.

### Tools Used
- Docker
- Docker Hub
- Ubuntu
- Nginx
- MongoDB

### Procedure
1. Install Docker on the system.
2. Verify the Docker installation.
3. Pull a container image from Docker Hub.
4. Create and run a container using the downloaded image.
5. Configure the required port mapping.
6. Access and verify the running container.
7. Stop and remove the container when required.

### Example

Run an Ubuntu container:

```bash
docker container run -it ubuntu top
