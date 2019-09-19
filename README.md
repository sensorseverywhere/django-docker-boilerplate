# Docker shell
docker-compose exec web sh

# Docker prod up / down
docker-compose -f docker-compose.prod.yml up -d --build
docker-compose -f docker-compose.prod.yml down -v

# Docker psql
docker-compose exec db psql --username=miriad --dbname=indms
