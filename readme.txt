Information:

This is a Fungible Token - RCKST. Developed on SUI.
module -> rckst
digest -> 0xd567797ba6b18894efae0b76135a498482cbb401e89e552b826c41aa2e645454
params -> TreasuryCap, amount*10^9, RecipentAddress
package id -> 0x8b1368b34b62eecda110958485fbd9f31a418c701590c0e8ffb90b384fd9307e
treasury id -> 0x01c0e6f08ca303e94933103c6c176dcda57c0a8cfbf655785ee60b174229ee27
callable function -> mint
explore -> https://devnet.suivision.xyz/object/0xd567797ba6b18894efae0b76135a498482cbb401e89e552b826c41aa2e645454

How to use:

sui client call `
  --package 0x8b1368b34b62eecda110958485fbd9f31a418c701590c0e8ffb90b384fd9307e `
  --module rckst `
  --function mint `
  --args 0x01c0e6f08ca303e94933103c6c176dcda57c0a8cfbf655785ee60b174229ee27 <amount> <recipient-address> `
  --gas-budget 10000000

  find RCKST sent to your wallet.
