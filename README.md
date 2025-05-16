pkg update && pkg upgrade -y
pkg install python git -y
pip install requests colorama
git clone https://github.com/KelvinTXCybers/spamotp
cd spamotp
python spamotp.py
