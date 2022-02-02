# emberswap-tokenlist
![logo](https://user-images.githubusercontent.com/96666546/148650317-28ef069d-38e8-4c54-adc6-6d1572376aa3.png)


### Whitelisting

- Fork this repo
  ```
  gh repo clone emberswap/emberswap-tokenlist
  ```
- Create a folder under *assets/{blockchainName}/{tokenAddress}*
- Add token's icon (logo.png) under the folder created in the previous step
- Add token's info in the *community.tokenlist.json* file, in this format:
  ```
  {
      "name": [token_name],
      "address": [token_address],
      "symbol": [token_symbol],
      "decimals": [token_decimals],
      "chainId": 10000
  }
  ```
- Make a Pull Request to this repo including all of the above.

<br>

More info about pull requests:
- [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
