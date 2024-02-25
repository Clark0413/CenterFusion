# CenterFusion

origin link : https://github.com/mrnabati/CenterFusion

# requirements

pip install torch torchvision

pip install cython; pip install -U 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'

CF_ROOT=/path/to/CenterFusion
git clone --recursive https://github.com/mrnabati/CenterFusion.git $CF_ROOT

cd $CF_ROOT
pip install -r requirements.txt

cd $CF_ROOT/src/lib/model/networks/DCNv2
./make.sh

cd $CF_ROOT/src/lib/model/networks
git clone https://github.com/CharlesShang/DCNv2/


