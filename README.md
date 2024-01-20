# txt.ibid.work

txt takes plain text and converts it to a URL search query that can be shared without ever touching the server.

txt is inspired by [itty.bitty.site](https://github.com/alcor/itty-bitty), but strips down many of its features to imitate a plain text file rather than HTML. The weight of the page is about 10x less than itty.bitty, 

According to the developer of itty.bitty, most browsers support a minimum of [2000 bytes (2kb) in the url](https://itty.bitty.site/#Link_sizes/XQAAAAIyBQAAAAAAAAAeHMqHyTY4PyKmqfkwr6ooCXSIMxPQ7ojYR153HqZD3W+keVdvwyoyd+luwncAksyBpBYltNr1Oj+0nFtw4rO71K7JRYBTu1/STbYi7TdKa6fx163w7+2NwPfmhoOPwFp2gWV4ZXeA0rB2gi0U/f9/E2cOaRXxIZgD6U7i6ie89XizK8ZD8Fq+/mkO2WUH0lg9l4PA8NUA4dETHmtQudwTqIJL20SLWQ869JVs8/sYUY6BxSzDgdelbMfaJp4YOuMV0trst4M0VycsfX7c4lFzueWTLzBWWWZLbv0cng0f6Yucm6Spvy04sIcHd7745pNbf8qoFG8Lk+ZTVNQEGvw3062z32Mt1RC1aiEfrT+/2WDIDj0QCJNiVgjHGsyvEEJUdKESrTEVRSPHkH3mS9ZM0yHEH2FiNWLHeHV08kcsHw517OziyN2/I6HEgRxRBv6qazKKSWv2YL3sKtL1bHmlw1kEmk3oXZUPui8nTDz69+6538W4XvsnGgn1VCy/6Ro99wWHxDQ4JwGuHJLCralhEFFM5PamhzrITZsULHd1DQdZWJgCrADVpHMZN9oV/zt6B5Za/N67UQJk/MwB+IG9f89weYnIKR8dyENh5V7i+52eMtcLiyPDyKUxz2N5YLq1bn1iDi4v4WV2bWNYZNNZX807U3xehdpiE0Z7ekifCX0qn6iMTzch8kCeGawescQEukIv2cxu3oEU8Je3l5LhUqVtxx43frl2X8T0qRzL4iy5gFnOC65uIVCWEKuiK7BBCqX2fG++EZqw60D4/e3p0PHdCS74kNlxooJpcahblAZzdd+u01Q0o+Bd9cBHiNw//P75XruL). For more, see [how.bitty.site](https://itty.bitty.site/#How_it_Works/XQAAAAK4CgAAAAAAAAAeHMqHyTY4PyKmqfkwr6ooCXSIMxPQ7ojYR153HqZD3W+keVdvwyoyd+luwncAksxo8PWJs+831jtAVty8rDpGXmyebtxMTP3PSa4g8/593sWue8MDcpOgi1bQyEtfa0JNQZ6T1I/xyNULg1rpwWgE2Y9BnqDq8fDN1N+nd58bizHxZrkeBhdg8inSQ/xKDX7JxpEnuwOAh4FOfn3+EHSxzhJsdQjZfh3lk4tTCDexgFND30Ea3NmmJGK84pdMtEVlcmKC5lrnUNmgoJa3QFsHJkr5595tk03idElTDVhmcQI3jSvPrkTVFTnSLeARVZXV/EUiF0y7+cR3bVkLoTkamZWDMiCTY2Xhv0LdNqWlb/xxyk6takRLrNnS8DkifXEbevTbJOUamuK7uy55kL61btF+/lYNHLWGbh1ckCYglReWWMlM0k4uuqM24okcS74tHtOW3Y5HZYBmPvRR+ItSrZPvbj3kbztOrWapUp7nAzgfIjYoBV/4xOXpFbbaHRft5GICE5Mr1PQhmW/nB63nTpnR+7UdHag8WIMa7nf+NvTPKC5MmQnKzhaMuqEnwGgcM5vkWbekimBclkGJwTGeyhxL7N6hivY+KS3H7vcOSFHXGr7K3PBIQZbywqQiimQ6B6zu4RvH7ZZ3ZN++ii00HKM0FPMcNHuOnL99vAxEl6TEFnx4J4+fwzJwNbuut30TFMBgcrE4iKAGncFIHmvOstFWxE+VlvTLC+uy6XArTO8BdfmbByGiyFv8Al7HqLAzGShdGWNzJ6cPpRwMAmWl5GNRA4qwjQAlfF1dtTwfIXSWOL7AyRwxPs27uY2cvVHCdmVVTNDYiTzHeKX6D9e2ApDRFD6pgcA9VMVP6UeOdVdmwRJ+iLTwQuCdLbVWzQ5T2i/chlihD+RawylXJQ8bKvxW9egXGcrgR5dyKaZCr8nBrArAgtRLR7PdqBQQbr5VodBvPc2FP3fZ6UuQVI1Kg4KcY44GIU5vnlM029TU+ibO2iSX3FhusTFhyOxl4TjjkuXBqA1V7Ha/Op2m8QZaP68p7AAZPOcTHAwP5PxENqIf8qS2aaG2Fiwp5rNED3LhPMjtN54klBYylr5hSAr0TD8J+XwFds8Gq9LToLE8Cq7XNJnE9RqNudIozaMWkfc6PRFjp/aH87x97nPDelKKHGyUEnGJyobw45BOhJMKzZST0VA5v+uQQo0djDXc0UXwzNRIWeBLuUJQpaXZY2gZMuLiSERgyDHg2MBI6trWsyb3ZWbFS4rm8Gq2dxfih3Kj6MdNapUo/jltQ31nx2LepJCQe9DNNF6JEMecls6dHTAM2RfHxEODSSKkF17FfjRLRAfxCK927UvizAxxggP5S/HrX6mGc5xonBy3StLd16thiAG860IdvFyBKfE6+CIhe2jzIwIofNiBILYlKA61vKkjlfZjqsUGDLi426U/Y8bdpxfg7FX1gqNEHeVM17dlBTO7pNOnKyeM2xmLoE7lr92/VIrxJ2OqNfcHu9XjrD6l71vU083VwwAq8Vencm9xLAlDyy3/6BB0kRBiJbjayYrLUbQyMGTFfEvOPmc/zJjfdnqHmg5O/0kuzf2+w5CHD426iPngjmiTo5Snlf+qW8emK/ltnQQIv2ufykH+Px3XZM+zsOclAyHI5MbCKBKeT6j5geCiz3uqci1w5ZlpRjtJWUT6zCj8Fx1eg4F4ov51gaODKV+QQWeFJSyuVTm3Nu2i7AbhKikNzb3RBeQinEh9KrhHc+o4JGezOU55h1UZtonB0+J5dfBRqHnc+6HaXfTmcLrMZjWErq15cBmC0Kx6BNyqP3uGhMUSF+OuIzffEX9fGUNDpUtCjKdbml8uF43e4fN8o10TxYkbggTcyYKI+xWHMyKM2tjOideyDwt33minfEy/JgSLsihBnBua9sfXCg32/+i2okk=). 

## Acknowledgements
- [pieroxy's lz-string](https://github.com/pieroxy/lz-string/)
- [alcor's itty-bitty](https://github.com/alcor/itty-bitty)

## To-do
- Drag text file into field
- Implement a YAML metadata function (to fill `<meta>` head elements like `<title>`)
- Add Warning before clicking `About` button
