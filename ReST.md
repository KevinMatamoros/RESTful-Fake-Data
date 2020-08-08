## What is REST?
Representational State Transfer.
A kit of rules that let understand the service to anyone to want use it.


## The Constraints -  Client Server

```
Client                Server
/ / /  /   Request    / / / / /
/      /   ------>    /       /
/      /              /       /
/      /   <------    /       /
/ / /  /   Response   / / / / /  
```


## The Constraints -  Staless Server
```

                      Server
                     / / / / /
                     /       /
                     /       /
                     /       /
                     / / / / /  

Client                Server
/ / /  /   Request    / / / / /
/      /   ------>    /       /
/      /              /       /
/      /   <------    /       /
/ / /  /   Response   / / / / /  


                      Server
                     / / / / /
                     /       /
                     /       /
                     /       /
                     / / / / / 

```


Client send a request and any server could response if another is unavailable.