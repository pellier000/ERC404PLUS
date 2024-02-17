# ERC404PLUS
🚨🚨 This version of ERC404+ improvment has not yet been fully tested or audited. While we've made efforts to develop a robust and functional smart contract, there may still be undiscovered vulnerabilities or issues that could potentially lead to unexpected behavior or loss of funds. By using this type of contract on mainnet you use it at your own risk. 🚨🚨

***:warning:IMPORTANT NOTE***

ERC404+ represents an enhanced iteration of the initial ERC404 protocol pioneered by 0xacme, accessible via the repository [@0xacme](https://github.com/0xacme/ERC404). 

Our contributions to this project have been entirely voluntary, devoid of direct affiliation with the creators of ERC404. We are committed to providing consistent updates, rectifications, and enhancements. Your contributions to the project, in any capacity and at any juncture, are wholeheartedly welcomed.

***CHANGELOG***

**FORGE (ERC404+) v1.1 BETA**
- Implement an array to store burning IDs. Upon the burning of an NFT, append its ID to this array. Upon completion of the minting process for all NFTs, retrieve IDs from this array for utilization.
- Integrate a recyclable NFT logic by extracting the burning mechanism from the contract. Rather than burning NFTs, immobilize them within the contract. Following the minting completion of all NFTs, recycle them from the contract rather than initiating a new minting process. This methodology is devised to eliminate the necessity for gas optimization.

***LICENSING***

This software is released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
