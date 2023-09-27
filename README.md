pkg upgrade
pkg install python
pkg install git
rm -rf mogid
git clone --depth=1  https://github.com/blesseco/mogidsc.git
cd mogid
python SC.py 
