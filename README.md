# two_nattings
This project explores how to do two nats



### Create a network like this 



|Internet over wifi from apartement router| ))))))) |Linux box with WAN on wifi and lan on ethernet with NAT| ========> |second linux box with input on ethernet and out on wifi| )))))))) | devices connected to the wifi|


This can be used to do traffic monitoring, modification (example - CSU blocks certain UDP traffic so if you are using xbox then you can connect the xbox to the lst wifi and set up UDP tunneling or something to bypass the limitaiton)

I was able to set up one NAT on first linux box but I am having difficulties to set up wifi hotspot and NAT on the second linux box


### TODO
 - [ ] Look into setting up two linux boxes behind the apartment wifi with NAT
