# Instruction to run swiggy-app

![Login diagram](images/home.png)
---

## clone repository:
```bash
git clone https://github.com/sidraut007/swiggy-app-clone.git

cd swiggy-app-clone
```

## Containerisation:
```bash
docker build -t sidraut007/swiggy-app .

docker run -d -p 80:80 --name swiggy-app  sidraut007/swiggy-app
```

## How to Acess swiggy-app on browser
- http://<server_ip>:80
