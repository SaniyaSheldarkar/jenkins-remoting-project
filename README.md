# Jenkins Remoting Project

This project demonstrates how to set up Jenkins Remoting to connect Jenkins agents (nodes) securely to the Jenkins master. It enables distributed builds, improves scalability, and ensures secure job execution on remote nodes.

---

## Features

- Setup of Jenkins agent using `jenkins-agent.exe` and `.xml` configuration files.
- Secure connection between Jenkins master and agent node using authentication tokens.
- Installation of Jenkins agent as a Windows service for automatic startup.
- Distributed job execution to offload build tasks from the master node.
- Isolation of build environments to improve security and stability.

---

## Project Setup

1. **Download `agent.jar`** from your Jenkins master server.
2. **Generate** `jenkins-agent.exe` and configure `.xml` file with connection details.
3. **Install** Jenkins agent as a Windows service on the remote node.
4. **Start** the agent service to connect to the Jenkins master.
5. **Verify** the node connection on Jenkins master’s "Manage Nodes" page.
6. **Assign** jobs to run on this remote node from Jenkins.

---

## Benefits

- Enables distributed builds across multiple machines.
- Allows running jobs on different operating systems or architectures.
- Improves Jenkins master’s performance by delegating build tasks.
- Secures agent connections via token authentication and configuration files.

---

## How to Use

- Start your Jenkins master server.
- Ensure the agent service is running on the remote node.
- Create or configure Jenkins jobs to run on the remote agent node.
- Monitor job execution and node status from Jenkins UI.

---


## Author

Saniya Sheldarkar  
[GitHub Profile](https://github.com/SaniyaSheldarkar)

---

Feel free to open issues or submit pull requests to improve this project!
