# Base interface

```js

// All ERC-20 functions

function mint(uint256 amount); // requires sending some base tokens (e.g. ETH)

function burn(uint256 amount);

function addCollateral();

function removeCollateral(uint256 amount);

function solvencyOf(address account) public view returns(uint256);

function liquidate(address account, uint256 amount);

```