
# Scrape Tools

### An Ubuntu-based Docker image for routine scraping tasks

Open Terminal in macOS and paste in the following commands to launch the Docker container. (Be sure to press return to execute the last command.)

```
docker rm -f scrape_tools
docker pull stevemclaugh/scrape-tools
docker run --name scrape_tools -ti -p 8889:8889 --volume ~/Desktop/sharedfolder/:/sharedfolder/ stevemclaugh/scrape-tools

```

In Windows 10, open PowerShell and enter the following to launch the Docker container. (Be sure to swap in your username in the last command.)

```
docker rm -f scrape_tools
docker pull stevemclaugh/scrape-tools
docker run --name scrape_tools -ti -p 8889:8889 --volume C:\Users\mclaugh\Desktop\sharedfolder:/sharedfolder/ stevemclaugh/scrape-tools
```
