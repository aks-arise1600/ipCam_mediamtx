# ipCam_mediamtx
IP Camera viewer and recorder. It has real-time media server and media proxy that allows to publish, read, proxy, record and playback video and audio streams.

## Dependencies 
1. Docker
2. mediamtx


## Build and Run

		git clone https://github.com/aks-arise1600/ipCam_mediamtx.git
		cd ipCam_mediamtx
		docker compose up -d
		
## check 

		docker logs -f mediamtx
		
## Stop and restart

		cd ipCam_mediamtx
		docker compose down
		docker compose up -d
		
## ** NOTE **
1. Before compose docker change your Camera's paths (Stream URL) from mediamtx.yml
2. To view in HTML just see the sample web/index.html
3. Recording saves in UTC timestamp (default)		
		
## Helps
1. [MEDIAMTX](https://github.com/bluenviron/mediamtx/blob/main/README.md)
2. [Docker](https://docs.docker.com/engine/install/)


