git clone https://github.com/Wholitical/wholitical-frontend.git ./angular
docker build -t wholitical_frontend .
docker run wholitical_frontend
