# Sonarqube Webserver on Docker with docker-compose.yml

## Run

- With `sh`
```
sh build.sh
```
- With docker-compose
```
docker-compose build --no-cache --force-rm && docker-compose up -d
```

## Clean all (!danger)
- With `sh`
```
sh clean.sh
```

## Webpage:

- Go to http://localhost:9000
- Create your project
- Scan project with [SonarScanner](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/)
- Recommend **SonarScanner** with node: [sonarqube-scanner npm packages](https://www.npmjs.com/package/sonarqube-scanner)