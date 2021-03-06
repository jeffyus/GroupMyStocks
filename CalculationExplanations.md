# Balance Sheet Calculations

## Assets

<table>
<thead><tr>
    <th><sub>Item</sub></th>
    <th><sub>Software Variable</sub></th>
    <th><sub>API Index Name</sub></th>
    <th><sub>Calculation Method (Software Variable)</sub></th>
</tr></thead>

<tbody><tr>
    <td><sub>Total Asset</sub></td>
    <td><sub>totalAssets</sub></td>
    <td><sub>totalAssets</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Total Current Assets</sub></td>
    <td><sub>totalCurrentAssets</sub></td>
    <td><sub>totalCurrentAssets</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Cash And Cash Equivalents</sub></td>
    <td><sub>cash</sub></td>
    <td><sub>cash</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Short Term Investments</sub></td>
    <td><sub>shortTermInvestments</sub></td>
    <td><sub>shortTermInvestments</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Receivables</sub></td>
    <td><sub>netReceivables</sub></td>
    <td><sub>netReceivables</sub></td>
    <td><sub></sub></td>
</tr></tbody>
		
<tbody><tr>
    <td><sub>Inventory</sub></td>
    <td><sub>inventory</sub></td>
    <td><sub>inventory</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Other Current Asset</sub></td>
    <td><sub>otherCurrentAssets</sub></td>
    <td><sub>otherCurrentAssets</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Total Long-term Assets</sub></td>
    <td><sub>totalLongTermAsset</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalAssets - totalCurrentAssets</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Net PPE</sub></td>
    <td><sub>propertyPlantEquipment</sub></td>
    <td><sub>propertyPlantEquipment</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Goodwill And Other Intangible Assets</sub></td>
    <td><sub>intangibleAssets</sub></td>
    <td><sub></sub></td>
    <td><sub>= goodWill + netIntangibleAssets</sub></td>
</tr></tbody>
		
<tbody><tr>
    <td><sub>Goodwil</sub></td>
    <td><sub>goodWill</sub></td>
    <td><sub>goodWill</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Other Intangible Assets</sub></td>
    <td><sub>netIntangibleAssets</sub></td>
    <td><sub>intangibleAssets</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Total Tangible Assets</sub></td>
    <td><sub>tangibleAssets</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalAssets - intangibleAssets</sub></td>
</tr></tbody>


</table>

## Liabilities

<table>
<thead><tr>
    <th><sub>Item</sub></th>
    <th><sub>Software Variable</sub></th>
    <th><sub>API Index Name</sub></th>
    <th><sub>Calculation Method (Software Variable)</sub></th>
</tr></thead>

<tbody><tr>
    <td><sub>Total Liabilities</sub></td>
    <td><sub>totalLiab</sub></td>
    <td><sub>totalLiab</sub></td>
    <td><sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Other Current Liabilities</sub></td>
    <td><sub>otherCurrentLiab</sub></td>
    <td><sub>otherCurrentLiab</sub></td>
    <td><sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Total Long-term Liablities</sub></td>
    <td><sub>totalLongTermLiab</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalLiab - totalCurrentLiabilities</td>
</tr></tbody>

</table>

## Equity

<table>
<thead><tr>
    <th><sub>Item</sub></th>
    <th><sub>Software Variable</sub></th>
    <th><sub>API Index Name</sub></th>
    <th><sub>Calculation Method (Software Variable)</sub></th>
</tr></thead>

<tbody><tr>
    <td><sub>Total Equity</sub></td>
    <td><sub>totalEquity</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalAssets - totalLiab</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Minority Interest</sub></td>
    <td><sub>minorityInterest</sub></td>
    <td><sub>minorityInterest</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Total Stockholders' Equity</sub></td>
    <td><sub>totalShareholderEquity</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalEquity - minorityInterest</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Common Stock</sub></td>
    <td><sub>commonStock</sub></td>
    <td><sub>commonStock</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Retained Earnings</sub></td>
    <td><sub>retainedEarnings</sub></td>
    <td><sub>retainedEarnings</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Gains Losses Not Affecting Retained Earnings</sub></td>
    <td><sub>treasuryStock</sub></td>
    <td><sub>treasuryStock</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Common Stock Equity</sub></td>
    <td><sub>commonStockEquity</sub></td>
    <td><sub>totalStockholderEquity</sub></td>
    <td><sub>( == commonStock + retainedEarnings + treasuryStock)</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Preferred Stock Equity</sub></td>
    <td><sub>preferredStockEquity</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalShareholderEquity - commonStockEquity</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Common Tangible Book Value</sub></td>
    <td><sub>commonBookValue</sub></td>
    <td><sub></sub></td>
    <td><sub>= commonStockEquity - intangibleAssets</sub></td>
</tr></tbody>
</table>

# Income Statement

<table>
	
<thead><tr>
    <th><sub>Item</sub></th>
    <th><sub>Software Variable</sub></th>
    <th><sub>API Index Name</sub></th>
    <th><sub>Calculation Method (Software Variable)</sub></th>
</tr></thead>

<tbody><tr>
    <td><sub>Revenue</sub></td>
    <td><sub>totalRevenue</sub></td>
    <td><sub>totalRevenue</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Gross Profit</sub></td>
    <td><sub>grossProfit</sub></td>
    <td><sub>grossProfit</sub></td>
    <td><sub></sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Cost of Good Sold</sub></td>
    <td><sub>goodSoldCost</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalRevenue - grossProfit</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Interest Expense</sub></td>
    <td><sub>interestExpense</sub></td>
    <td><sub>interestExpense</sub></td>
    <td><sub></sub></td>
</tr></tbody>
</table>

# Other Indicators
## Fundamentals

<table>
	
<thead><tr>
    <th><sub>Item</sub></th>
    <th><sub>Software Variable</sub></th>
    <th><sub>API Index Name</sub></th>
    <th><sub>Calculation Method (Software Variable)</sub></th>
</tr></thead>
	
<tbody><tr>
    <td><sub>Working Capitals</sub></td>
    <td><sub>workingCapital</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalCurrentAssets - totalCurrentLiabilities</sub></td>
</tr></tbody>

</table>

## Ratios

<table>
<thead><tr>
    <th><sub>Item</sub></th>
    <th><sub>Software Variable</sub></th>
    <th><sub>API Index Name</sub></th>
    <th><sub>Calculation Method (Software Variable)</sub></th>
</tr></thead>
	
<tbody><tr>
    <td><sub>Current Ratio</sub></td>
    <td><sub>currentRatio</sub></td>
    <td><sub></sub></td>
    <td><sub>= totalCurrentAssets / totalCurrentLiabilities</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Quick Ratio</sub></td>
    <td><sub>commonBookValue</sub></td>
    <td><sub></sub></td>
    <td><sub>= ( totalCurrentAssets - inventory ) / totalCurrentLiabilities</sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>BVPS</sub></td>
    <td><sub>bvps</sub></td>
    <td><sub></sub></td>
    <td><sub>= commonStockEquity /sharesOutstanding </sub></td>
</tr></tbody>

<tbody><tr>
    <td><sub>Tangible BVPS</sub></td>
    <td><sub>tanBvps</sub></td>
    <td><sub></sub></td>
    <td><sub>= (commonStockEquity - intangibleAssets)/sharesOutstanding </sub></td>
</tr></tbody>

</table>





