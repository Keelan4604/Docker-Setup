# Docker-Setup
8/22/24

I was running my instance of homebridge through Hyper-V virtualization which was working fine but for a few reasons I am going to switch it over to Docker. I want to be able to manage multiple containers, Docker uses less resources, want Rustdesk set up in Docker as well, better control over the containers, better UI, etc. 

Right now I have gotten Homebridge config and others copied over to the new instance running in docker but am having issues getting it to connect to HomeKit because of networking issues. I am pretty certain that my IP is being used by Hyper-V on the same port so I cant connect this new Homebridge to my phone. I'm trying to remove the IP connection to Hyper-V and also connect a different port but then forward the new 8080 port to 8581 inside of Docker. I have a super basic understanding all of this but am learning a lot and hopefully will get it figured out soon. ChatGPT is super helpful.

I plan to set up the Rustdesk instance after and get that to work.
