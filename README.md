docker-tmux-static
==================

Build static tmux using docker

    docker build -t tmux .
    docker run --rm tmux cat /tmux/tmux > tmux && chmod +x tmux
    docker rmi tmux  
    
    docker run -it tmux:latest /bin/bash
    docker cp imageid:/root/local/bin/tmux ./
