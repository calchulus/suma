# SUMA

<h2>The Problem</h2>
	<p>Users who are lending tend to want to lock in high interest rates, or at least do not want to see their interest rates fall.</p>
	<p>Conversely, borrowers want certainty over their interest rates.</p>
	<p>The easiest way to do this is to set fixed rate, fixed term loans, but these are rigid and fail to give users the full flexibility of DeFi.</p>
	
<h2>Introducing SUMA - Secure with UMA</h2>
	<p>We are introducing the proposal to create SUMA assets - assets powered by UMA Protocol that track the real value of lending &amp; borrowing rates for all DeFi platforms</p>
	
<h2>Why is this Important</h2>
<p>
	SUMA assets provide exposure to the interest rate directly on various DeFi products. 
</p>
	<h3>Scenario 1</h3>
	<p>A user coming from CeFi to DeFi wants to place her funds in a secure, interest-bearing "checking account" with full flexibility on withdrawal. She wants to maximize return while keeping flexibility</p>
	<p>She visits dYdX or Compound and sees interest rates for USDC, her preferred stablecoin, at nearly 10%! She doesn't know if they will stay that way though.</p>
	<p>She then allocates a small percentage of her portfolio to hedge against the risk of the interest rate moving against her</p>

<p>Additional Scenarios to be added soon!</p>

<h2>Mechanics</h2>
<p>All SUMA assets in v1 will be valued according to the following formula: </p>
				<p style="padding-left: 2.5%"><i>Price = 100 - leverage ( interest rate in % )</i></p>


<p>Thus, users can choose how much to long or short this asset to cover their portfolio needs. In scenario 1 described above, the user may decide to go create a UMA token (or use an existing one) and sell/short the token for the interest rate of her desired product and term-length, thus giving her insurance incase the interest rate decreases for her DeFi.
	</p>
	
<ul>Key benefits
		<li>No fixed term length on insurance - user can sell value at any time</li>
		<li>User can purchase at any time/get hedged/more safe interest rates</li>
		<li>Can be used as a signal/tool for interest rate governance</li>
	
</ul>

## Next Steps
- Add an easy way to claim all the free subdomains for an email (check if price is free) automatically
- Interest Rate Spread/ Brent/WTI-style Strategies
- Building onchain price feed for UMA
- Utilize this ENS address I bought as an easy to find and fund faucet: [ethboston.wantsome.eth](https://etherscan.io/tx/0x71394662f983d4488df54f1c3fce02f19b32627c0fb741b3cccfefc028c7b274)

### Improvements Encountered to work with Project Teams on
- Integrate Torus with more dApps
- Add more custom styling/location features on Torus  interface/add a widget to drop in
- Added functionality on UMA TokenBuilder to allow for UMA Token Search
- Launching compatibility for more testnets for UMA, ENS.
- Encorporate cDAI/cTokens directly into UMA (support for more than just DAI as collateral)
- create a TCR for price feeds/repository of useful price feed sources for UMA
