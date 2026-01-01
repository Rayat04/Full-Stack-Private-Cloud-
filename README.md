# Full-Stack-Private-Cloud-

Full Stack Private Cloud Implementation using Nextcloud on Rocky Linux

## Project Overview
This project demonstrates the implementation of a private cloud storage system using
Nextcloud deployed on Rocky Linux within an Oracle VirtualBox virtual machine.
The system provides secure file storage, sharing, and cross-platform access while
maintaining complete data control.

## Implementation Steps
1. **Virtual Machine Setup**  
   A virtual machine was created using Oracle VirtualBox with allocated CPU, RAM, and storage resources. Rocky Linux 9.6 was installed as the guest operating system.

2. **Network Configuration**  
   The VM network adapter was configured in **Bridged mode** to allow access from external devices on the same network.

3. **Web Server Installation**  
   Apache HTTP Server was installed and configured to serve web applications.

4. **Database Configuration**  
   MariaDB database server was installed, secured, and a dedicated database and user were created for Nextcloud.

5. **PHP Environment Setup**  
   PHP 8.2 and required PHP extensions were installed to meet Nextcloud compatibility requirements.

6. **Nextcloud Deployment**  
   Nextcloud was downloaded, extracted into the Apache document root, and proper file permissions were applied.

7. **Application Configuration**  
   Nextcloud was configured through the web interface by creating an admin account and connecting it to the MariaDB database.

8. **Security Configuration**  
   Firewall rules were adjusted to allow HTTP/HTTPS traffic, and access permissions were properly configured.

9. **Testing and Validation**  
   The system was tested for file upload, download, and cross-platform access from Windows and Android devices.

## Documentation
Detailed configuration steps, screenshots, and testing results are available in the project report.


## Tools & Technologies Used
- Oracle VirtualBox
- Rocky Linux 9.6 (64-bit)
- Apache HTTP Server
- MariaDB Database
- PHP 8.2
- Nextcloud Hub
- Firewalld


## System Architecture
The private cloud system is deployed on a virtual machine using a full LAMP stack:
- Linux as the operating system
- Apache as the web server
- MariaDB as the database backend
- PHP as the runtime environment
- Nextcloud as the cloud application

The virtual machine is configured using a **Bridged Network Adapter**, enabling access from external devices on the same network.


## Key Features
- Self-hosted private cloud storage
- Secure file upload and download
- Web-based user interface
- Cross-platform access (Windows & Android)
- Full data ownership and privacy


## Project Structure
- `Report/` – Final project report (PDF)
- `Presentation/` – Project presentation (PPT)
- `Screenshots/` – Implementation and result screenshots


## Author
**Name:** Anush Rayat  
**Project Type:** Individual Academic Project  

## Platform
Oracle VirtualBox with Rocky Linux 9.6
