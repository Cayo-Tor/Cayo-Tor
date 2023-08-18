<style>
a img.hover {
    display: none;
}
a img.default {
    display: inherit;
}
a:hover img.hover {
    display: inherit;
}
a:hover img.default {
    display: none;
}

.background {
  background-image: url('https://im4.ezgif.com/tmp/ezgif-4-27f77a6365.gif');
  background-position: center;
  background-size: 30%;
  overflow: hidden;

}
</style>

<div class="background">
  <!-- your website content here -->
<h1> Cayo Tor
        <a href="https://www.linkedin.com/in/cayofletcher-smith/">
            <img align="right" class="default" width="25px" style="padding-right:10px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/ResearchGate_icon_SVG.svg/2048px-ResearchGate_icon_SVG.svg.png"/>
            <img align="right" class="hover" width="27px" style="padding-right:10px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/ResearchGate_icon_SVG.svg/2048px-ResearchGate_icon_SVG.svg.png" title="ResearchGate"/>
        </a>
        <a href="https://medium.com/@CayoTor">
            <img align="right" class="default" width="25px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-medium-2296046-1912005.png?f=avif&w=256"/>
            <img align="right" class="hover" width="27px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-medium-2296046-1912005.png?f=avif&w=256" title="Medium"/>
        </a>
        <a href="https://twitter.com/0xCayo">
            <img align="right" class="default" width="25px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-twitter-53-189787.png?f=avif&w=256"/>
            <img align="right" class="hover" width="27px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-twitter-53-189787.png?f=avif&w=256" title="Twitter"/>
        </a>
        <a href="https://etherscan.io/address/0x233adaaE8A5A04893D6BF6F64A0C74cafF53Abc0">
            <img align="right" class="default" width="25px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-ethereum-8-645838.png?f=avif&w=256"/>
            <img align="right" class="hover" width="27px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-ethereum-8-645838.png?f=avif&w=256" title="Etherium Wallet"/>
        </a>
        <a href="https://www.linkedin.com/in/cayofletcher-smith/">
            <img align="right" class="default" width="25px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-linkedin-42-151143.png?f=avif&w=256"/>
            <img align="right" class="hover" width="27px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/free/png-512/free-linkedin-42-151143.png?f=avif&w=256" title="LinkedIn"/>
        </a>
   </h1>
</div>
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"></a>
   **`Solidity Auditor and Blockchain Researcher`**

I'm a blockchain researcher, Solidity smart contract auditor, and overall technology enthusiast. My focus is primarily on Ethereum security, with an emphasis on tooling (fuzzing) and bug bounties; although I have exposure in layer-one consensus design, and byzantine mechanism architecture.

Alongside my pursuit for technological impact, I enjoy playing games, creating technical web 3.0 content, and travelling.

## My Stack
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?logo=solidity&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?logo=javascript&logoColor=%23F7DF1E)
![Git](https://img.shields.io/badge/git-%23F05033.svg?logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?logo=amazon-aws&logoColor=white)

___
###### Systems
![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Kali](https://img.shields.io/badge/Kali-268BEE?logo=kalilinux&logoColor=white)
![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?logo=Manjaro&logoColor=white)

___
###### Technical Writing
![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?logo=ResearchGate&logoColor=white)
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?logo=latex&logoColor=white)
![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)





## Smart Contract Auditing
I'm an active member in the smart contract security space. I can be found on Medium crafting technical resources for others to learn; exchanging insights in a range of Web 3.0 communities; and obviously, getting stuck in on bug bounties.

#### My Findings
<details>
    <summary>
        Gas
    </summary>
    <li align="left" style="padding-left:18px;"> [G] - Redundant Variable Assignment </li>
    <li align="left" style="padding-left:18px;"> [G] - Public visibility functions should be external if not called internally </li>
    <li align="left" style="padding-left:18px;"> [G] - Uint8 --> Uint256 to save gas on EVM conversion </li>
    <li align="left" style="padding-left:18px;"> [G] - Use unchecked math to increment loops </li>
    <li align="left" style="padding-left:18px;"> [G] - Adjust order of || and && operations </li>
    <li align="left" style="padding-left:18px;"> [G] - Perform revert conditional earlier </li>
</details>
<details>
    <summary>
        Low
    </summary>
    <li align="left" style="padding-left:18px;"> [L] - Insufficient Loop Bounding </li>
    <li align="left" style="padding-left:18px;"> [L] - Incorrect initialization or update of bounding variable irrecoverable </li>
</details>
<details>
    <summary>
        Medium
    </summary>
    <li align="left" style="padding-left:18px;"> [M] - Unbound loop results in DOS </li>
</details>

#### Secured Projects
<img align="left" alt="Venus Protocol" width="30px" style="padding-right:10px;" src="https://code4rena.com/_next/image?url=https%3A%2F%2Fstorage.googleapis.com%2Fcdn-c4-uploads-v0%2Fuploads%2FzTpwCnWwq4z.0&w=96&q=75" />

<img align="left" alt="Chainlink" width="30px" style="padding-right:10px;" src="https://cdn.iconscout.com/icon/premium/png-512-thumb/chainlink-link-7151095-5795788.png?f=avif&w=256" />

<br>
<br>

To learn and grow I actively participate in capture the flags, auditing competitions and workshops.

#### My Stats
<details>
    <summary>
        Competition Stats
    </summary>
    <li align="left" style="padding-left:18px;"> Top 25% (Secureum 20)</li>
    <li align="left" style="padding-left:18px;"> Top 10% (Secureum 18)</li>
    <li align="left" style="padding-left:18px;"> Top 50% (Secureum 17)</li>
    <li align="left" style="padding-left:18px;"> Top 50% (Secureum 16)</li>
</details>

<details>
    <summary>
        Workshops
    </summary>
    <li align="left" style="padding-left:18px;"> Secureum Bootcamp</li>
    <li align="left" style="padding-left:18px;"> Fuzzing (Medusa) - Trail of Bits</li>
</details>

<details>
    <summary>
        CTF's Completed
    </summary>
    <li align="left" style="padding-left:18px;"> Ethernaut (29/29)</li>
    <li align="left" style="padding-left:18px;"> Damn-Vulnerable-Defi (9/15)</li>
</details>

## 📟 Blog Posts
<!-- BLOG-POST-LIST:START -->
- [Talking to Ethereum - Smart Contracts to Opcodes](https://medium.com/coinsbench/talking-to-ethereum-smart-contracts-to-opcodes-3fc53a8de7d1)
- [Ethereum Smart Contract Upgradeability](https://medium.com/coinsbench/how-can-ethereums-immutable-smart-contracts-be-upgraded-a4b582893f29)
- [Essential ERC Standards Every Developer Should Know](https://medium.com/coinsbench/essential-erc-standards-every-developer-should-know-3de3fec969e5)
- [Understanding Address Types - A Comparison of Bitcoin, Ethereum and Cardano](https://medium.com/coinmonks/understanding-address-types-a-comparison-of-bitcoin-ethereum-and-cardano-45354a8ceb68)
- [Flash Loans Explained in 5 Minutes](https://medium.com/coinmonks/flash-loans-explained-in-5-minutes-8f9c0468d9f5)
- [Blockchain State Models](https://medium.com/coinsbench/blockchain-state-models-explained-ea708fe7a4f2)
<!-- BLOG-POST-LIST:END -->

[blog]: s
[twitter]: s
[wallet]: s
[linkedin]: s
[discord]: s
