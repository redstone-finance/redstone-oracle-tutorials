# Base interface

```js

function postOnSell(uint256 itemId, uint256 usdAmount);

function getPriceForItem(uint256 itemId) public pure returns(uint256);

function listItemsForSale() public pure returns(uint256[] memory);

function buyItem(uint256 itemId); // requires sending the appropriate amount of ETH

```
