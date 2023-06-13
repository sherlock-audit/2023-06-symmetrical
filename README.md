
# Symmetrical contest details

- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)

# Q&A

### Q: On what chains are the smart contracts going to be deployed?
Arbitrum One, Arbitrum Nova, Fantom, Optimism, BNB chain,  Polygon, Avalanche
___

### Q: Which ERC20 tokens do you expect will interact with the smart contracts? 
USDT and USDC 
___

### Q: Which ERC721 tokens do you expect will interact with the smart contracts? 
none
___

### Q: Which ERC777 tokens do you expect will interact with the smart contracts? 
none
___

### Q: Are there any FEE-ON-TRANSFER tokens interacting with the smart contracts?

none
___

### Q: Are there any REBASING tokens interacting with the smart contracts?

none
___

### Q: Are the admins of the protocols your contracts integrate with (if any) TRUSTED or RESTRICTED?
TRUSTED
___

### Q: Is the admin/owner of the protocol/contracts TRUSTED or RESTRICTED?
TRUSTED
___

### Q: Are there any additional protocol roles? If yes, please explain in detail:
MUON_SETTER_ROLE: Can change settings of the Muon Oracle.
SYMBOL_MANAGER_ROLE: Can add, edit, and remove markets, as well as change market settings like fees and minimum acceptable position size.
PAUSER_ROLE: Can pause all system operations.
UNPAUSER_ROLE: Can unpause all system operations.
PARTY_B_MANAGER_ROLE: Can add new partyBs to the system.
LIQUIDATOR_ROLE: Can liquidate users.
SETTER_ROLE: Can change main system settings.
Note: All roles are trusted except for LIQUIDATOR_ROLE.
___

### Q: Is the code/contract expected to comply with any EIPs? Are there specific assumptions around adhering to those EIPs that Watsons should be aware of?
ERC-2535: Diamonds, Multi-Facet Proxy  
Create modular smart contract systems that can be extended after deployment.
___

### Q: Please list any known issues/acceptable risks that should not result in a valid finding.
none
___

### Q: Please provide links to previous audits (if any).
none
___

### Q: Are there any off-chain mechanisms or off-chain procedures for the protocol (keeper bots, input validation expectations, etc)?
Liquidator Bots, Force close Bots, Force cancel Bots, Anomaly detector Bots
___

### Q: In case of external protocol integrations, are the risks of external contracts pausing or executing an emergency withdrawal acceptable? If not, Watsons will submit issues related to these situations that can harm your protocol's functionality.
1- Collateral tokens, which are stablecoins, we accept the risks.

2- The potential for the Muon app to be down or give inaccurate data is also considered acceptable.
___



# Audit scope
