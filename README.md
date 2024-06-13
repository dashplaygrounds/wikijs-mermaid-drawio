# wikijs-mermaid-drawio

cd projects
mkdir wikijs-mermaid-drawio; cd wikijs-mermaid-drawio

nano deploy.sh
sudo mkdir -p /opt/postgres
docker network create wikinet
docker compose up -d
