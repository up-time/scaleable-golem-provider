# scaleable-golem-provider

## Modifying the provider name and hardware preset
Just head into the /data-node/ya-provider/ directory and modify **globals.json** and **hardware.json** to your needs.


## Spawning providers
To spawn x amount of providers just simply run the following in the main directory:
`Docker-compose up -d --scale node=x`

