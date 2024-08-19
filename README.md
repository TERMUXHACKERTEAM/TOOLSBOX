pkg install git
pkg install python
pip install requests
pkg update -y && pkg upgrade -y
rm -rf FB-TOOLSBOX
git clone --depth=1 https://github.com/U7P4L-IN/FB-TOOLSBOX.git
cd FB-TOOLSBOX
python fb.py
