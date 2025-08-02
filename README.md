docker network create enid_service_network
docker-compose up


RENOVAR CERTIFICADO ------
cd service_web/
docker-compose down
certbot renew --force-renewal
Algo similar 
Matas el 80 
lsof -i :80
2035  sudo kill 1979773
nuevamente d_up 