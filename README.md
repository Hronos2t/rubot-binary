# rubot-binary
Paid bot for MMORPG AION

official site https://rubotaion.ru

## Requiments
- Windows 7 or newer (32 or 64 bit)
- .NET framework 4.5

## Aion-client supports
- actual Game-forge client [EU] 32-bit edition
- actual NA client 32-bit edition

## Steps to start
- run Aion client in 32-bit edition
- login to the game with your character
- start the bot and select client version (`NA` or `EU`)
- configurate bot and launch it

## Runing clients
### NA + XignCode (need to perform after each update)
- rename or delete `<GameFolder>/bin64/aion.bin` file
- download [xignCodeFake](https://github.com/Hronos2t/XCFakeClient/releases/download/v1-beta1/x3.xem) and replace file `<GameFolder>/bin32/XignCode/x3.xem`
- start the game with launcher

### EU GameForge
- [!] use game launcher only for update
- run ```start bin32\aion.bin -ip:79.110.83.80 -port:2106 -cc:2 -lang:eng -noweb -noauthgg -charnamemenu```
(you can execute this command by creating a `.bat` or `.cmd` file in `the game folder` and write this line to it)
