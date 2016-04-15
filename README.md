# stackoverflow-36102680


## Setup

    echo "# Stackoverflow 36497197" | sudo tee --append /etc/hosts
    echo "127.0.0.1 foo.localhost" | sudo tee --append /etc/hosts
    echo "127.0.0.1 bar.localhost" | sudo tee --append /etc/hosts

##  Start
    
    docker-compose up
    
## Open

http://foo.localhost/ -> shows "404" from /404/index.html
http://bar.localhost/ -> shows "bar" from /subdomains/bar/index.html
