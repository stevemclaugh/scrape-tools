
# Scrape Kit

### An Ubuntu-based Docker image for routine scraping tasks

Open Terminal in macOS and paste in the following commands to launch the Docker container. (Be sure to press return to execute the last command.)

```
docker rm -f scrape_kit
docker pull stevemclaugh/scrape-kit
docker run --name scrape_kit -ti -p 8889:8889 --volume ~/Desktop/sharedfolder/:/sharedfolder/ stevemclaugh/scrape-kit

```

In Windows 10, open PowerShell and enter the following to launch the Docker container. (Be sure to swap in your username in the last command.)

```
docker rm -f scrape_kit
docker pull stevemclaugh/scrape-kit
docker run --name scrape_kit -ti -p 8889:8889 --volume C:\Users\mclaugh\Desktop\sharedfolder:/sharedfolder/ stevemclaugh/scrape-kit
```