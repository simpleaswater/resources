BOUNTY_NAME : Remove Web3.js injection dependency from your Dapp

LINK_TO_ORIGINAL_BOUNTY_ANNOUNCEMENT : https://explorer.bounties.network/bounty/2326

LINK TO APPLY FOR BOUNTY : https://explorer.bounties.network/bounty/2326

BOUNTY_AMOUNT : 10 DAI [$$10.07 USD]

OTHER_DETAILS : A common issue we see in Dapps is that their developers assume that a Web 3 browser == MetaMask and that they will magically have access to a Web3.js library, injected inside the page on their behalf. We see this implicit dependency & injection as a bad practice that needs to disappear for the ecosystem to move forward. Developers should import the web3 convenience library of their choice and build their Dapp on top of that, just as they do for other Javascript libraries. Opera exposes a Web3 Provider (window.web3.currentProvider) which you need to instantiate your own web3 object from. Removing this dependency on MetaMask Web3.JS library injection will make your dapp more compatible and resilient with other Web3 browsers such as Opera and make it future-proof as this will likely be deprecated.
