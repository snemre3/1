# 1
1
pkg up -y

pkg install git -y
pkg install python -y
git clone https://github.com/maldevel/IPGeoLocation
cd IPGeoLocation
pip install colorama
pip install termcolor
python ipgeolocation.py -351713118116279 
