ROM
PPUI
MIUI 
REDMI

# Recovery

aparentemente o primeiro boot precisa ser manual

- flash

`$ fastboot flash recovery ARQUIVO.img`

- desliga segundando o botão por alguns segundos
- liga segundando as teclas + e - ao mesmo tempo
- no SHRP tem uma opção dentro de tweaks ([MIUI] Disable Replace SHRP) 


# ROM

enviar o .zip via sideload

- entrar no recovery
- habilitar sideload
- enviar o arquivo 

`$ adb sideload FILE.zip`

- wipe: Internel, Dalviik, Data, Cache
- reboot

# Boot loop?

- se o aparelho entrar em modo boot loop, segura power. Pode ser preciso fazer 2 ou 3 vezes
- Se nem entrar no logo da ROM, entrar no recovery e formatar
