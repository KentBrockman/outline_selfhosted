# Guide

https://app.getoutline.com/s/770a97da-13e5-401e-9f8a-37949c19f97e/doc/docker-7pfeLP5a8t

## 2022-10-23T22-06:00

What is working:
- can fire up all containers 
- can run DB provisioning scripts (with `network_mode: host`)

What isn't working:
- i havent set up any authentication method as per their suggestions
- redis + database are the only containers that stay up
  - minio loops and dies, their config needs work. guess i could use AWS instead but i want an encapsulated deploy
  - https-portal loops as well, havent looked into it
