



# Pen-TEST Python ITHS VT-24

En samling Python script som kan användas i Pen-Test miljöer.

## Installation i Docker

Installera docker först från https://www.docker.com/products/docker-desktop/

```bash
# Ladda ner docker bygg fil
https://github.com/cpu900/iths-py/blob/main/dockerfile.txt

# Bygg image 
docker build -t pentest:1.0 -f dockerfile.txt .

# Skapa container
docker run --name pentest --hostname kali -it pentest:1.0 
```

## Installation i Bash

```python

# skapa katalog
mkdir pentest

#byt katalog
cd pentest

# kopiera git
git clone https://github.com/cpu900/iths-py/

# installera paket
pip install -r requirements.txt

# starta script
python3 ./start.py
```

## Bidra

För ändringar, öppna ett ärende för att diskutera vad du skulle vilja förändra.

## Licens

[MIT](https://choosealicense.com/licenses/mit/)
