# Namada SE IBC channels from Cosmic Validator

### Channel creation txs
1. namada channel on omniflix: 
https://testnet.ping.pub/omniflix/tx/FC31CF9C9932EFB03D52B9DC2F399BD10E3FCEE30397C7DA17049F0FE3D045BB
```
INFO ThreadId(01) 🎊  flixnet-4 => OpenConfirmChannel(OpenConfirm { port_id: transfer, channel_id: channel-33, connection_id: connection-40, counterparty_port_id: transfer, counterparty_channel_id: channel-283 }) at height 4-11124290
```
2. namada channel on osmosis:
https://testnet.mintscan.io/osmosis-testnet/txs/0BC2297E370E44E700F0089708D29DA1DD070E74DF09A72D5B06C79E1065345C
```
🎊  osmo-test-5 => OpenConfirmChannel(OpenConfirm { port_id: transfer, channel_id: channel-5822, connection_id: connection-2131, counterparty_port_id: transfer, counterparty_channel_id: channel-287 }) at height 5-5576196
```
3. namada channel for cosmos:
https://testnet.mintscan.io/cosmoshub-testnet/txs/8F177F64AAAFD9189FED7DA42B961B74C2FEDC75FE82EDDBE9A36D22C60E27D9
```
 🎊  shielded-expedition.88f17d1d14 => OpenConfirmChannel(OpenConfirm { port_id: transfer, channel_id: channel-290, connection_id: connection-437, counterparty_port_id: transfer, counterparty_channel_id: channel-3823 }) at height 0-47987
```
4. namada channel on noble
https://testnet.mintscan.io/noble-testnet/txs/2EA01F6B29C50C3377984000625BFFBDF8AEAC91B10B46F6045DB7D2982774FC
```
 🎊  grand-1 => OpenConfirmChannel(OpenConfirm { port_id: transfer, channel_id: channel-82, connection_id: connection-108, counterparty_port_id: transfer, counterparty_channel_id: channel-304 }) at height 1-5407914
```


---
### Relay transactions

#### omniflix <> namada
namada ibc transfer to flixnet-4 tx:
https://namada-se-api.cosmicvalidator.com/tx/B52EB07E38DD9C403064B5F9CAD7381293BE9A5918092F0D63D31C4EC76E0544

flixnet-4 relay tx
https://api.testnet.omniflix.network/cosmos/tx/v1beta1/txs/77B5EDAFBD4D6B2C889A9BF9258C10E045B42F86E40DCBEBD00E99AA0E03E376

f4 to namada ibc transfer tx:
https://testnet.ping.pub/omniflix/tx/8D42EF42576C3A7A3E0A0B910310907CEA5D5AB5AD2973125781242EBF648CF7

f4 ack tx:
https://testnet.ping.pub/omniflix/tx/8DE1313236D2FB7FD9CD28D3C0DF0BF462EFFB23106B9E755F28F0BA784503A1

#### osmosis <> namada

ibc transfer tx
https://testnet.mintscan.io/osmosis-testnet/txs/2609EC5FEFFB0478801FD7A8A1BD92D10DA3B1699A93BFBC4C1F1AE224AA8EA5

relay tx
https://testnet.mintscan.io/osmosis-testnet/txs/2F7CA1883D0B0B86F1BD15832A4EB9252513C12A98087A0AA2E7A38B7D906BA8


#### cosmoshub <> namda

ibc transfer tx
https://testnet.mintscan.io/cosmoshub-testnet/txs/EDB90676067D6124479F113847CD7541A270AC009CE5E5A42B1BE4AF86307C8F

packet ack tx
https://testnet.mintscan.io/cosmoshub-testnet/txs/C3827BBE2F1BE5879D1F7A3D913EFE77F0DF7FE91D7B43CAD9F5AEAEA31DD91F

#### namada <> noble

ibc transfer tx
https://namada-se-api.cosmicvalidator.com/tx/56A041A857A2037B70FC1187B43A2DE1C81DC97597B69CE6B490068DE79E4BFD

packet relay tx
https://testnet.mintscan.io/noble-testnet/txs/3E402F33D270952E56630AA02161A88FE910FA105D38C27553FB0C5885FDB753?height=5407991

