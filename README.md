# Virtualized-Network-Project
A project simulating a server-client virtualized network using VirtualBox and Ubuntu, including network configuration and basic web server setup.

## Technologies Used
- VirtualBox (virtualization)
- Ubuntu 24.04 (Linux operating system)
- Apache Web Server (HTTP server)
- Bridged Adapter Networking (VM network configuration)

## Project Steps
1. **Created two Ubuntu virtual machines**:
   - `Ubuntu-Server`
   - `Ubuntu-Client`

2. **Configured networking**:
   - Both VMs set to use `Bridged Adapter` so they appear on the same network as the host machine.
   - Verified both VMs received IP addresses in the same subnet.

3. **Tested network communication**:
   - Used `ping` to confirm both VMs could communicate with each other.

4. **Installed Apache on the Server VM**:
   ```bash
   sudo apt update
   sudo apt install apache2
