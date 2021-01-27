# Docker-LEMP-Angular
これCloneして
docker-compose up -d --build
を行えば、
http://localhost:5050/
でPHP、
http://localhost:6600/
でAngularのアプリケーションが見れます。

ちなみに、Angularのプロジェクトは、
開発を始める前に、
npm install
開発後に、
npm run build -- --output-path=./dist/out --configuration production
を行ってから、Dockerを立ち上げると確実かと。
