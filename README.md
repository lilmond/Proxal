# Proxal
Automated working proxy servers finder.

![image](https://github.com/user-attachments/assets/a3ce6992-44a3-46a3-8bb1-65dd8098d6a6)

# Installation
Linux / Termux
```
git clone https://github.com/lilmond/Proxal
cd ./Proxal
pip install -r requirements.txt
```

For widows computers, manually download this repository here: https://github.com/lilmond/Proxal/archive/refs/heads/main.zip

After unzipping, execute the command below:
```
pip install -r requirements.txt
```
If it doesn't work, try this one:
```
python -m pip install -r requirements.txt
```
Or this one:
```
py -m pip install -r requirements.txt
```

# Usage
Linux / Termux
```
python3 proxal.py -o good_proxies.txt -t 500 --tries 5 --timeout 20
```
Windows
```
python proxal.py -o good_proxies.txt -t 500 --tries 5 --timeout 20
```
If it doesn't work, try this one:
```
py proxal.py -o good_proxies.txt -t 500 --tries 5 --timeout 20
```

# Help
```
 _______                                          __
|       \                                        |  \
| $$$$$$$\  ______    ______   __    __  ______  | $$
| $$__/ $$ /      \  /      \ |  \  /  \|      \ | $$
| $$    $$|  $$$$$$\|  $$$$$$\ \$$\/  $$ \$$$$$$\| $$
| $$$$$$$ | $$   \$$| $$  | $$  >$$  $$ /      $$| $$
| $$      | $$      | $$__/ $$ /  $$$$\|  $$$$$$$| $$
| $$      | $$       \$$    $$|  $$ \$$\\$$    $$| $$
 \$$       \$$        \$$$$$$  \$$   \$$ \$$$$$$$ \$$

                                lilmond@github/proxal

usage: proxal.py [-h] -o OUTPUT [-t THREADS] [--tries TRIES] [--timeout TIMEOUT]

Proxal, automated working proxy servers finder.

options:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Output file after checking if a proxy is alive.
  -t THREADS, --threads THREADS
                        Max threads for checking proxies. Default: 20
  --tries TRIES         Max tries for connecting to a proxy server. Default: 3
  --timeout TIMEOUT     Socket connection timeout. Default: 10
```
