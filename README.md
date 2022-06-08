# ngrok-termux
# ngrok installation for termux and Kali Linux.    
ngrok is a cross-platform application used to expose a local development server to the Internet, the server appears to be hosted on a subdomain of ngrok (e.g., 4f421deb219c[.]ngrok[.]io) by creating a long-lived TCP tunnel to the localhost. The experts pointed out that ngrok server software runs on a VPS or a dedicated server and can bypass NAT mapping and Firewall restriction.

# command 

```bash
 $ apt update && apt upgrade 

$ apt install git 

$ git clone https://github.com/i-omgautam/ngrok-termux/

$ cd Ngrok-Termux

$ chmod +x Ngrok-Termux.sh 

$ sh Ngrok-Termux.sh 

```


# What is ngrok?   
ngrok is a reverse proxy that creates a secure tunnel from a public endpoint to a locally running web service. ngrok captures and analyzes all traffic over the tunnel for later inspection and replay.

# ngrok 2.x   
ngrok 2.x is the successor to 1.x and the focus of all current development effort. Its source code is not available.

# NOTE This repository contains the code for ngrok 1.x.  

# Status of the ngrok 1.x project       
ngrok 1.x is no longer developed, supported or maintained by its author, except to ensure that the project continues to compile. The contribution policy has the following guidelines:

# All issues against this repository will be closed unless they demonstrate a crash or other complete failure of ngrok's functionality.
All issues against this repository are for 1.x only, any issues for 2.x will be closed.
No new features will be added. Any pull requests with new features will be closed. Please fork the project instead.
Pull requests fixing existing bugs or improving documentation are welcomed.
The ngrok 1.x hosted service
ngrok.com ran a pay-what-you-want hosted service of 1.x from early 2013 until April 7, 2016. Afterwards, it only runs 2.x service.

# Production Use   
DO NOT RUN THIS VERSION OF NGROK (1.X) IN PRODUCTION. Both the client and server are known to have serious reliability issues including memory and file descriptor leaks as well as crashes. There is also no HA story as the server is a SPOF. You are advised to run 2.0 for any production quality system.

# What can I do with ngrok?   
Expose any http service behind a NAT or firewall to the internet on a subdomain of ngrok.com
Expose any tcp service behind a NAT or firewall to the internet on a random port of ngrok.com
Inspect all http requests/responses that are transmitted over the tunnel
Replay any request that was transmitted over the tunnel
What is ngrok useful for?
Temporarily sharing a website that is only running on your development machine
Demoing an app at a hackathon without deploying
Developing any services which consume webhooks (HTTP callbacks) by allowing you to replay those requests
Debugging and understanding any web service by inspecting the HTTP traffic
Running networked services on machines that are firewalled off from the internet.

Project by Om Gautam
