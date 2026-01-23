# Python installation

### Linux

```bash
sudo apt-get update
sudo apt-get install -y python3 python3-pip python3-venv
```

### Windows

#### Without WSL

Please download Python installer from python website: https://www.python.org/

#### With WSL

Install WSL

```powershell
wsl.exe --install Ubuntu-24.04
```

Then run WSL

```powershell
wsl.exe -d Ubuntu-24.04
```

Then install python

```bash
sudo apt-get update
sudo apt-get install -y python3 python3-pip python3-venv
```