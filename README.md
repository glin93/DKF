# DKF Code
Thanks to the code from [Mem2Seq](https://github.com/HLTCHKUST/Mem2Seq). You can download the dataset from this repo.

## Install the Requirements
absl-py==0.8.1

astor==0.8.0

astroid==2.3.3

boto3==1.10.28

botocore==1.13.28

cachetools==3.1.1

certifi==2019.9.11

chardet==3.0.4

cycler==0.10.0

docopt==0.6.2

docutils==0.15.2

gast==0.2.2

google-auth==1.7.1

google-auth-oauthlib==0.4.1

google-pasta==0.1.8

grpcio==1.25.0

h5py==2.10.0

idna==2.8

isort==4.3.21

jieba==0.39

jmespath==0.9.4

joblib==0.14.0

jsonpatch==1.24

jsonpointer==2.0

Keras-Applications==1.0.8

Keras-Preprocessing==1.1.0

kiwisolver==1.1.0

lazy-object-proxy==1.4.3

Markdown==3.1.1

matplotlib==3.1.1

mccabe==0.6.1

mosestokenizer==1.1.0

moverscore==0.85

mysql==0.0.2

mysql-connector==2.2.9

mysqlclient==1.4.5

nltk==3.4.5

numpy==1.17.4

oauthlib==3.1.0

openfile==0.0.7

opt-einsum==3.1.0

pandas==0.25.3

Pillow==6.2.1

pipreqs==0.4.9

portalocker==1.5.2

protobuf==3.10.0

pyasn1==0.4.7

pyasn1-modules==0.2.7

pyemd==0.5.1

pylint==2.4.3

pyparsing==2.4.5

python-dateutil==2.8.0

pytorch-pretrained-bert==0.6.2

pytz==2019.3

pyzmq==18.1.1

regex==2019.11.1

requests==2.22.0

requests-oauthlib==1.3.0

rope==0.14.0

rsa==4.0

s3transfer==0.2.1

scikit-learn==0.21.3

scipy==1.3.2

six==1.13.0

SQLAlchemy==1.3.11

tensorboard==2.0.1

tensorboardX==1.9

tensorflow==2.0.0

tensorflow-estimator==2.0.1

termcolor==1.1.0

toolwrapper==1.0.0

torch==0.4.1

torchfile==0.1.0

tornado==6.0.3

tqdm==4.38.0

typed-ast==1.4.0

typing==3.7.4.1

uctools==1.2.1

urllib3==1.25.7

visdom==0.1.8.9

websocket-client==0.56.0

Werkzeug==0.16.0

wrapt==1.11.1

yarg==0.1.9

## Run the Code
python multi_mem_train.py -lr=[learning rate] -layer=[set dialogue history blocks layer] -hdd=[set hidden state] -dr=[set dropout rate] -dec=Mem2Seq -bsz=64 -ds=[kvr or babi(for DSTC 2)] -t=6[for DSTC 2]  -kb-layer=[Database layer] -enbirnn -debirnn