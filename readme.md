# Cross platform mc server 

bridges Java, bedrock, and even eaglercraft 1.8 so they can all play on the same server. (When it works its quite responsive)

Java port = ```25565```

Bedrock port = ```19132```

eaglercraft port = ```8081```


uses paper java server, and a few plugins to translate the java server to different versions.

# To Start

1) extract to anywhere.
2) install java 17 or newer
3) run ```runall.bat``` for windows.
4) no it won’t run on replit as it is desinged to run on your own hardware. don’t ask

# bugs

I have had problems with ports and using anything other than localhost for eaglercraft. This was fixed by setting the server adress to ```0.0.0.0```. Geyser translates to mc bedrock which seems to work flawlessly.

since Eaglercraft is so old compared to the current bedrock and java it is missing some things.
I found an ocelot in the sand with the name tag "turtle". also, there is the minor issue where if you 
try to travel anywhere below y0 you can't (whereas if you were to join with a newer client you could travel to a -y).
