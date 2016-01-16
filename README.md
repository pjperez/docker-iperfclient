# docker-iperfclient
Docker image that connects to Wormhole's overlay network and starts and iPerf client

## Building docker-iperfclient
    
    git clone https://github.com/pjperez/docker-iperfclient
    sudo docker build -t wormhole/docker-iperfclient .

## Running docker-iperfclient
    sudo docker run -t -i --privileged=true -e IPERF_SERVER=100.64.0.30 wormhole/docker-iperfclient
    
Change 100.64.0.30 for your iPerf server's IP address.

## More info

Read [docker-wormhole](https://github.com/pjperez/docker-wormhole) if you're not familiar with Wormhole's Docker image.