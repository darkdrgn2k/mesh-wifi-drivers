
| Device                                                                                                             | Chipset   | Driver                                                                                                 | 802.11s | AdHoc | AP   |Band        | Notes                                                                       |
| :----------------------------------------------------------------------------------------------------------------- | :----------- |:--------------------------------------------------------------------------------------------------- | :------ | :-----| :----| :----------| :-------------------------------------------------------------------------- |
| TL-WN722N [v1](https://wikidevi.com/wiki/TP-LINK_TL-WN722N_v1.x)                                                    | AR9271L      | ath9k_htc                                                                                          | | X       | X  | X       | 2.4Ghz     |            |
| TL-WN722N [v2](https://wikidevi.com/wiki/TP-LINK_TL-WN722N_v2),[v3](https://wikidevi.com/wiki/TP-LINK_TL-WN722N_v3) | RTL8188EUS   | [rtl8188eus](https://github.com/aircrack-ng/rtl8188eus/tree/v5.3.9)                                 | -      | ?   | ?       | 2.4Ghz     |TXPower broken. Default driver uses old Wifi API. | 
| TP-Link AC600 Archer T2UH [v2](https://wikidevi.com/wiki/TP-LINK_Archer_T2U_v2)                                    | MT7610U    | [mt7610u](https://github.com/ulli-kroll/mt7610u.git)| -| ? | ? | 2.4/5Ghz | Compile [patch](https://github.com/tomeshnet/802.11s-adapters/blob/master/drivers/mt7610u.md#ulli-kroll-driver)|

# Install headers

**Rasbian**  
apt-get install raspberrypi-kernel-headers

**Armbian**  
apt-get install linux-headers-next-sunxi
