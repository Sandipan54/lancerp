git clone https://github.com/PARATOS855/VALOCITY.git

cd VALOCITY

chmod +x *

./install.sh

nohup ./lancer.sh > lancer.log 2>&1 &
nohup ./proxy.sh > proxy.log 2>&1 &