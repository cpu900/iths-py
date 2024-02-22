

# 🔥 PEN-TEST Python ITHS VT-24

En samling Python script som kan användas i Pen-Test miljöer.

# * Installation med Docker som container (rekommenderas)

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

# * Installation med bash i befintligt linux system med git

skapa katalog
```python
mkdir pentest
```

byt katalog
```python
cd pentest
```

kopiera git
```python
git clone https://github.com/cpu900/iths-py/
```

installera paket
```python
pip install -r requirements.txt
```

starta scriptet
```python
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
