# altschoolassignment
IP address - http://54.147.207.149
I deployed my server using AWS cloud services, allowing SSH, HTTP, and HTTPS traffic from any source during the initial EC2 instance setup, later restricting SSH access for security. To automate the process, I created a script stored in a GitHub repository. On the server, I installed `wget`, `unzip`, `zip`, and `apache2`, then downloaded my HTML files from GitHub, unzipped them, and copied the content to the `/var/www/html` folder. Finally, I restarted the Apache web server to complete the deployment.
