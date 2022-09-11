# CloudFrontIPSelector
To select the best CloudFront IPs for low latency in connections.

### Background 
In most cases, people who use AWS CloudFront got very stable experience because AWS's DNS works very well.

On the other hand, people living in China use it often get timeout,  packages lost and high latency. So some people want to find some IPs with low latency and bind on CloudFront's domain.
For these cases, I wrote this script to select lowest latency IPs.


### How to use?

1. set up node environment.
Some pople who have no experience on Node  may need to set up [nvm](https://github.com/nvm-sh/nvm).

2. run this JS file.
```
node ./main.js
```

3. wait minites to get `result.txt` which contain best IPs will be saved in this folder.
