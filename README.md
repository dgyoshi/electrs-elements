# electrs with elements

API document is available here https://github.com/blockstream/esplora/blob/master/API.md

## Run

`docker-compose up --build`

## Call electrs APIs

1. connect elements container  
`docker exec -it elements /bin/bash`

2. generate block where n is the number of blocks to generate
`ecli generate n`

3. call API  
`curl http://localhost:3002/blocks/tip/hash`
