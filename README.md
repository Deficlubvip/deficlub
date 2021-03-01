Deficlub
Building the source
git clone https://github.com/Deficlubvip/deficlub.git
cd nrsc
cargo build
See Building the source for more information

Docker quick start
docker pull registry.cn-beijing.aliyuncs.com/nrsc/deficlub_testnet_dev:latest
docker run --rm -d --name nrsc -p 6615:6615 -p 8080:8080 registry.cn-beijing.aliyuncs.com/nrsc/deficlub_testnet_dev
See Docker quick start for more information

License
Deficlub is released under the terms of the LGPL-3.0 license. See COPYING for more information or see https://opensource.org/licenses/LGPL-3.0
