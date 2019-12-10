## Usage

- customer_id: ['KH01', 'KH02', 'KH03', 'KH04']

```python
from after_sale import BotAfterSale

bot = BotAfterSale.Bot()

res = bot.interactive(customer_id='KH01', message='msg')
print(res)
```

## Flowchat
[Click xem flowchat của 3 kịch bản](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Th%C3%A1i%20Minh%20Flowchat#R%3Cmxfile%3E%3Cdiagram%20id%3D%22fMtIVgBL8J5Bw8ak2eWi%22%20name%3D%22MissCall%22%3E7Zrdk9smEMD%2FGs20D%2B0IkGT70dKdk04vSWfcmTRPHdkiEoksdDI62%2F3rCxJYX45C4g%2F5ZvR0sCycgP3h3QUDeZv9m8xPo3c0wLEBzWBvoAcDQgBMyP8IyaGU2FMpCDMSSKVKsCT%2FYSk0pTQnAd42FBmlMSNpU7imSYLXrCHzs4zummqfadz8r6kf4o5gufbjrvQjCVhUSqe2WcnfYhJG7Dhh2bLxlbIUbCM%2FoLuaCD0ayMsoZWVps%2FdwLBZPrUvZb%2FGN1uOHZThhOh2m5NlDs%2Bd%2F0bP598cvk2D14e3yN2jJj2MHNWMc8AWQVZqxiIY08ePHSupmNE8CLIY1ea3SeaI05ULAhV8wYwe5m37OKBdFbBPLVrwn7B%2FR%2FXdb1j7VWh72cuSiclCVhGWHWidR%2FVRvq7oVNdWvnJ%2BY1DfXTYq2NM%2FWuGexlP35WYhZ36Ied5djgekG8%2B%2Fh%2FTIc%2B4y8NL%2FDl%2FYZHvWqLeQFuYs%2FsKNy3Bc%2FzuV%2FemM8AsN1jekD4Q1xUZsbcyBqXyPDQ7y8jnilLJtJKLhrdEoiWZ3z4Z2YT95dZbwUitIv7%2F5YLrmSN396%2BrVjTtzsU1FMM7rGWz5bdxcRhpepX6z1jh8bTeNY%2BeuvYWFiH3IWkwRL%2BWeaMGWXapI4Y3jfv6%2FdfZAdkCJVnkyWrO4qzKFSiWqIT80r7RxEI4vaLEJNFtGQLMIOi55kjBritHYL6CRoCw0e54Y7ScWICmI7EQN5ljEDahxQaIuenoEWHZOqDAZ8n8WLMwftBnNg2oUO2Cegc64F3XRkTps5pMmcdSZzRdd5lvmHmkJKScK2tZH%2FEoLKtKzWcY5Qyx1q6QPUq88L5RdUpnWcys9b22y0totbm%2FMarA3OBrA2FUON5nZBc5u8BnNznCHMDYzmdnFzs1%2BDudn9%2BtcxN9Rxrru%2BbkQ3q1wj5ryEa9tCDp5wbacnPFvrWp4tGMNJfRwtTRzBoLkdq2Pyf9bjxTJ4dK0iYHzOfREbsqIdbrpsNHb6xnHgpHVe2CfCQHjLMBCMcaA%2BLLYuLOf6Smdtqd0PS5k08QtWViqd8pDcFyeWdXeg2CMo2qA4uqCcmzE5a0udDijvQ8NzDNeUKcWZugMo0pHtLGXjpuCe4IHtDM%2Fg8MAxQtKHZ6IJT%2B0ydQB4Jv2%2FMuvCI0OqNIe50Ur53xMxTjuOG5wY0H%2BFwo6XmRvxM07Uwk5YF7Q4JukWD%2B7rHtd4uDV1xlNI%2F87%2FZpGh3jWF3b5%2BLj9M9mpZxiWSet2Y832kqFuICDP5jrPAZIML2s5C8y3CPR2EbdfBOnVPeVtoX9%2FVEWggWxF8A2h1fYdh0zmg6zx4yjeYAXEIsKhBVUiKnE4PRPJlAO%2Fgtp8T3BNf7bh2eL5gN3t8p3xdkJOzXWe92yenneO%2B8m%2BWMpz6G7io9oxNJno84ZVH%2BUHRhIp8KVEPbRZp0U6rXzMoFF5IUZ7fWaao7bpfkyherZ6tlptWPf5Fj%2F8D%3C%2Fdiagram%3E%3Cdiagram%20id%3D%22C2fIZFZQDAGN41Cf-X20%22%20name%3D%22AfterSale%22%3E7Vtbl5s2EP41nNM%2BpAckwPgRfEnOybZp45w06RvGWkMWkCOLXTu%2FvhJIXL1esq659PjFloaRDMP3jWZGsgJn0eEtcXf%2B73iDQgWom4MC5woAmqYC9sUlx0xiWEKwJcFGKBWCVfADCaEqpEmwQfuKIsU4pMGuKvRwHCOPVmQuIfipqnaPw%2Bqv7twtaghWnhs2pX8HG%2BpnUstQC%2Fk7FGx9mj%2BwuBK5UlkI9r67wU8lEVwocEYwplkrOsxQyI2X28WB939Nv6yif8i34%2F6zf%2FyI5m%2ByyZY%2FMyR%2FBIJi%2Buqpoz8%2BgWD1%2FeHH8u7D5rN6%2BG6Y6zfy0ehR2gttmPlEFxPq4y2O3XBRSB2Ck3iD%2BKwq6xU6dxjvmFBjwm%2BI0qPAgptQzEQ%2BjUJxFR0C%2BoUP%2F80Qva%2BlK%2FODmDntHGUnpuRYGsS7X8vXimFpT47Lno8%2FVA0OL9hS6O1xQjx0xoAS0i7ZInpGD%2BaAYUxDOELsJtk4gkKXBo%2FVm3MF5Le5XvFaWUO82Z94y2LeRzdMxC%2FNfGWmKxaM%2BDMqM6g40GPNB5%2B3bc3zWSdrq%2FGWPx9RZqbiqMpCUxxHmTpcm08x1bLRla7Nu1uha80DPoEcaaTzlXTV7HI2PbvJVNFWbCNWgBkymzprwlpb3vrFXn5afGRaK%2Ftu8WsDu4yhO97cEeyhPbOi8%2BQHFK12bvoOn5iHqyJx7XoP2xTPHxIaBjES8nscU0kCaTxEKDq8AkTNly5mARPBPuFZddF9KtwUkM7IL7koS70STMDNGVzmDGBLZ2D16QzgSWfAiYg5MYGTUl9wdynIyS7P4sIpZO0ocdkdbFIHME1pvZfkhTG3qy%2B7U%2B5nouxX6m6m5jZoPmjppYNKvRo6C%2BxpL1O9G0pPjQqlNavJac04wWnzWpzWb5y%2BjNNWS05r6mlktCZ1OtQmxD2WFHY4iOm%2BNPOfXFAADtbWEAhrQWBNP49uT%2BuzRnYHBeDyR3k9Bo0bBjvCoD4GDObOrksMmjcMdoRBcwwYNPvwg5MbBjvCIBgDBnXd6B6DYDSOcChgAsYYwDQxenBowoSlVLIBLuLjaJ20KMUoV0rJpCGkYcCJlMw6kZHp18rIZGG8ZLX35XyYfaS1MFdm2M9mvepAsl69Bj3jRNILukx6Na1htYE6uaGutBpo6x2fgUZHhW1wnkspf1Qia88wUMCsRrFEXtR4BWvwXINWLWjon2zwRrYLyaa3jWunvZJN%2F78tXKCeBfZPplut7FIymW1Xrn63ZM3zZMp2Rdx0V2VkS5QxvHhw0jB2ec%2BLyj0mjW9TrQO5%2BTWhTTKGYbDbo4FYGtaSPvPEFnLHlrZu%2FutC%2FzVtGwxMLvRf7XaIjPpxg%2BzGxKgaXP6DmoJ8%2FopjTI4pW22%2Bq1zZPI4LeRbrP%2BabzKV96cG7zHogop%2FaN%2B6UyLJqMnwiX5uQF2e4z1R%2FtWd8d0c8k3fcjmf7%2FOBX1AhIRKwSjIBn9ey5f56BZsl0oDzLF0ytslwWq2dPCyZoe%2BrqSgumCXsmcvNA17vK8S0FmG7E2ZZ9Msl7SvhaeUBRneflw1yl4512KgjzyFhLqvn%2B4Ilfz0n6Jz4cYY16YMRvXTa7lPiXefgXymYZ%2Fxw9pVgWxMaCZ%2FZyDNwaXLoPbknopdQyWlIL9Est4zy1vPy%2FCWnLBnzZqpxtHjy5zOng2DUdC7uuzpLrBJT1oxydB5TNaulbnweScX40fx7LjVSWMcqYMC6lgrKCymXsXecF1iAdhLPJUkpyjccAxSPk4jWDSNYt%2FlmYvdni%2F5lw8S8%3D%3C%2Fdiagram%3E%3Cdiagram%20id%3D%22Iu3tNANXRyjaGaJGJeL-%22%20name%3D%22T%C3%ADch%20%C4%91i%E1%BB%83m%22%3E7ZlLc5swEIB%2FjWbaQzs8bXI02GkyaZJm0mmSowwqqAFEZRHb%2FfWVQDIv16ahTpoZX2ztsiuQtN9qBcD0ktUnCrPokgQoBoYWrIA5BYah65rB%2F4RmXWpsRypCigNpVClu8S8klZrU5jhAi4YhIyRmOGsqfZKmyGcNHaSULJtm30ncvGsGQ9RR3Pow7mrvcMCiUuvYWqU%2FQziM2GbA8koClbFULCIYkGVNZc6A6VFCWNlKVh6KxeSpeVne%2BedeYF8sHh6n3vXdPc4urz6UnZ3%2BjctmCBSl7NldO04euHM0%2FXUf3GTxDcXfbrIPamhsreYLBXz6pEgoi0hIUhjPKq1LSZ4GSPSqcamy%2BUxIxpU6V%2F5AjK1lLMCcEa6KWBLLq2iF2b1w%2F2hL6aF2ZbqSPRfCWgkpo%2BuakxAf6tcqt0JSfuX4xKBa4bBnLqXdguTURzsmUIU0pCFiO%2BzMTcBw0hBJEH9I7kdRDBl%2Baj4clCEfbuyqZeUNubJ%2Fscqy3ycY5%2FJOZ8AbAVcDMx24Ljhx01AgXogTMHFTLj1GwDPBRPcjMb6iPS3awLPAiY6lr2Mm7xqm%2FKfoG%2B5zew%2BMUcznzJ1T3gpF693Xc%2B%2BM207PZ5fvO6HJAcxEM6PERws%2BSe4ywgzdZrBYoiVPYM1Am0P%2FMSzC9TpnMU6R1H8nKVMxruYGUYZWz4iR7prKXkyVSGTitKS4rLKQoUyiWgZytANFgXFkfRjrZk%2FWnddk3eyw7pV0agQYnog1ReApFsGKkoJTSb4udAtI2vz3hroTY1UE6fuBfRkwDbsBpu50ydTtLWSODkWmdSRzGJlOTzJ1bXtk9EazcJ1QCtc1g4zglC1qPX8RiirgrNZOYJqtSq1lr5s77XmjfIIq4DZDeX4M2scYfKEYtN5CDI522x8mBp3O3tXdTiKSzPMetd%2FBdo9Rc2KMLbuHs2XzsA5W1o2P5A48w2k90TWGojvsFKd18Lj4U402x7Kic09Z7ZL4nejFYY%2FRwtVL9x7vdpR02n9S0o1byWq0paIzXrKi080jlAOhtPrupyevCqW1G8omiOL8lUoWCwrrzMblMe0t8GZbLeDsVwdu3FmH2rm3dsBNqkXh2W3MupzGMc4W6D%2BZ6VZm25RlrzfRzjGzDcxsJ30z23hgZut3vLTbbxzLB5NerXD5B1W%2BGn8N1atI8XnaefVcpcVNacItBNSJcrLF6H7ma0W1nhZ%2BpTQx8RvMqNa2l1IvCrpxBH0g6EbvEmYo6MMWulvCfMKbL0OCNhZVG2au3iLv%2FYDk9%2F1%2B9AbwbG3D1vhwdHKx%2BqZc5tzqy7w5%2Bw0%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E)
