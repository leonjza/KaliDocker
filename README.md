# KaliDocker

Kali Linux (Rolling) Docker Image

Buld the image with:
  `$ docker build -t kali-rolling .`

Start a container for the first time from a built image with:
  `$ docker run -ti --name kali -h kali kali-rolling`

After the first run, start the image with:
  `$ docker start -ai kali`
