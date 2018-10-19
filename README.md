# fastping
Fast,stable,easy to configure icmp ping tool

### Why reinveting the wheel...
[go-fastping](https://github.com/tatsushid/go-fastping) is fast but not stable. I got different result in my stable subnet enviroment.

Why go-fastping so fast?
- Share a single icmp connection 
- Use goroutine to send icmp package

Why go-fastping is not stable?
- icmp is not tcp. It's unreliable, Packet Loss is serious when ping 100+ devices


Inspired by [fasthttp](https://github.com/valyala/fasthttp)
- Use conntion pool and goroutine pool to imporve concurrent capacity and decrease resource consumption


### How to use


### Configure
