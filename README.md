# nginx-lab
Nginx is a high-performance, open-source web server designed for speed, scalability, and efficiency. It serves static web pages, handles reverse-proxying to backend applications, and manages load balancing across multiple servers. 
Known for its low resource usage and ability to handle thousands of simultaneous connections, Nginx is widely used for hosting websites, APIs, dashboards, and security tools.
The following process and commands will be executed in a Kali-Linux, WSL environment.  Refer to my WSL installation Repository to have Linux installed in a Windows environment.

Run the following:
# Refreshes Kali’s package index to ensure you download the latest available versions of all software, including Nginx.
sudo apt update
# Downloads and installs the Nginx web server along with all required dependencies. The -y flag auto-confirms the installation.
sudo apt install -y nginx
# Launches the Nginx service so it begins serving web content immediately.
sudo systemctl start nginx
