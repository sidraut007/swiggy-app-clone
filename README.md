# Instruction to run swiggy-app

# clone repository
git clone https://github.com/sidraut007/swiggy-app-clone.git

cd swiggy-app-clone

docker build -t sidraut007/swiggy-app .

docker run -d -p 80:80 --name swiggy-app  sidraut007/swiggy-app

# How to Acess swiggy-app on browser

http://<server_ip>:80
