

# 🔥 PEN-TEST Python ITHS VT-24

En samling Python script som kan användas i Pen-Test miljöer.

## Installation i Docker (rekommendera)

* Installera docker först från https://www.docker.com/products/docker-desktop/

### Ladda ner docker bygg fil
```bash
https://github.com/cpu900/iths-py/blob/main/dockerfile.txt
```

### Bygg image 
```bash
docker build -t pentest:1.0 -f dockerfile.txt .
```

### Skapa container
```bash
docker run --name pentest --hostname kali -it pentest:1.0 
```

## Installation i Bash

```python
# skapa katalog
mkdir pentest
```

```python
#byt katalog
cd pentest
```

```python
# kopiera git
git clone https://github.com/cpu900/iths-py/
```

```python
# installera paket
pip install -r requirements.txt
```

```python
# starta script
python3 ./start.py
```


## ✍ Användning
```bash
# [1]
Söker upp geografisk position på en IP-adress samt anger AS den tillhör.
Använder IPAPI.co (tillåter 1000 förfrågningar / dag utan konto)
```

```bash
# [2]
Försöker knäcka hash MD5/SHA
prova med de35e405bfce64ed4f5410757bf17ef4
```


## 🙏 Bidra

För ändringar, öppna ett ärende för att diskutera vad du skulle vilja förändra.

## 💡 Licens

[MIT](https://choosealicense.com/licenses/mit/)
