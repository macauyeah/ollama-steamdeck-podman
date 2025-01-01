podman compose -f podman-compose.yaml up -d
podman exec -it ollama ollama pull llama3.2
visit localhost:8080
podman compose -f podman-compose.yaml down
