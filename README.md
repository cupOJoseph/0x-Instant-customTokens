# 0x-Instant-customTokens
An informational repo with links and examples on setting up 0x Instant for custom tokens. I created this repo after spending too many hours researching setting this up and struggling with lack of good examples and complete docs. Hopefully this helps someone out there save some time.

## Requirements
Using Instant with a custom token is not very easy, although I expect it to become easier to do so soon. Until then you'll have to take some extra steps compared to using Instant as it ships.

- Serve liquidity
You need to use a relayer and its API to serve tokens through 0x.

- Sign order ahead of time
Sale orders your custom token must be already signed so 0x has permission to sell those tokens at some price.

- Integrate 0x Instant library with API and relayer, embed in your site. This is mostly just a copy paste, and *should* be the same as using any regularly supported token.

## Documentation Links

- Main Instant Docs: https://0x.org/docs/guides/integrate-instant
- Custom token info
- Relayers
- Relayer API connection
- Signing orders


## Other helpful things
- Manually create a signed order (via cooper at 0x): https://gist.github.com/coopermaruyama/10605bc36da6886f4fa10bf1dcd2fc63
