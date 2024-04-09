# DOCKER IMAGE FOR NFT MARKET API

Docker environment for nft market api

Backend API:
https://github.com/ground-creative/nft-market-backend

Backend Docker:
https://github.com/ground-creative/nft-market-backend-docker

Frontend React:
https://github.com/Rutilusmeta/nft-market-frontend

Frontend Docker:
https://github.com/ground-creative/nft-market-frontend-docker


## Installation

1) Clone the repository
```
git clone https://github.com/ground-creative/nft-market-backend-docker
```

2) Change environment variables in env.sample file and rename it to .env

## Usage

```
docker compose --project-name=nft-market-backend up -d
```
Or
```
docker compose --project-name=nft-market-backend up -d --build
```

### Command Environment Variables

It's possible to override environmet variable file while starting or building a container

#### Example usage
```
TEST=true COMMAND="tail -f /dev/null" docker compose --project-name=nft-market-backend up -d
```
