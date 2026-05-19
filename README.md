Create a DAML contract for Enterprise Supply Chain Financing. 
The contract workflow must include:
1. Three parties: Buyer, Supplier, and Third-Party Logistics (3PL).
2. The Buyer locks the total payment of 50,000 USDT in an escrow state upon contract creation.
3. The Supplier updates the contract status to 'Shipped' with a tracking ID.
4. The 3PL party must sign a 'Delivery Confirmation' once the goods physically arrive.
5. Upon 3PL signature, the locked escrow funds must automatically release to the Supplier's balance. Include a penalty clause that deducts 1% of the total payment per day if the 3PL confirmation is delayed past the agreed maturity date.
