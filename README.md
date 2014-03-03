# Docker redis

warning: ssh login is enabled and my private key is included!

## Usage

### in Dockerfile
    FROM aooj/redis:latest

### build
    git clone https://github.com/AoJ/docker-redis.git
    make build
    
### and start it
    make run

### or build, start and attach
    make debug

    
## Changelog
- 1.1 update to aooj/base:1.5
- 1.0 first realese
