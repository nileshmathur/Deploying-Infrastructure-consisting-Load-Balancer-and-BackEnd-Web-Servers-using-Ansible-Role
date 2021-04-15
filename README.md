# Deploying-Infrastructure-consisting-Load-Balancer-and-BackEnd-Web-Servers-using-Ansible-Role

What are the Use Cases for Deploying this Infrastructure??
Let's take an example.

Assume you want to access a website.Now,for that,you need to have the IP Address of that particular server in which that website is hosted.

But,at the same time,company handling that website,does not want to provide the IP Address of that server as it may have sensitive data.So,the company deploys the Load Balancer over all the backend servers and provide the IP Address of Load Balancer to the client.

Now,clients are able to request the Load Balancer via browser and at that end,Load Balancer makes the request to one of the Backend Server which repsonds to the Load balancer and that data is send to the client via browser.
