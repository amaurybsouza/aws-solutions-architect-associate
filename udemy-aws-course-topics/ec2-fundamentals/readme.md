# Amazon EC2
- EC2 is one of the most popular of AWS offering
- EC2 = Elastic Compute Cloud = Infrastructure as a Service
- It mainly consists in the capability of



# Elastic IP
- when you stop and then start an EC2 instance, it change its a public IP.
- if you need a fixed public IP for your instance you need an Elastic IP.
- an Elastic IP is a public IPv4 you own as long as don't delete it 
- you can attach it to one instance at a time.
- you can onlye have 5 Elastic IP in your account. (you can ask to AWS to increase that)
- Overall, try to avoind using the Elastic IP:
  - they often reflect poor architectutal decisions.
  - instead use a random public IP and register a DNS name to it.
  - use a load balancer and don't use a public IP.