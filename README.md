
![Banner](.github/banner.jpg)
## Installation

Install Go Lang Version 1.18 or Higher - https://go.dev/doc/install

Clone the Repository

git clone https://github.com/cryptoclassictech/crccoin.git

cd crccoin


go build  -o crcd



#Initialize the Data 

./crcd secrets init --data-dir ~/.crc

#Run the Node

./crcd  server --data-dir  ~/.crc  --chain genesis.json  --libp2p 0.0.0.0:1478 --nat "Your IP" --seal



## CRC

CRC  is a modular and extensible framework for building Ethereum-compatible blockchain networks.

To find out more about CRC, visit the [official website](http://crytpoclassic.org/).

WARNING: This is a work in progress so architectural changes may happen in the future. The code has not been audited yet, so please contact [CRC team](mailto:cryptoclassictech@gmail.com) if you would like to use it in production.

## Documentation 📝

If you'd like to learn more about the CRC , how it works and how you can use it for your project,


---

Copyright 2022 Polygon Technology

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
