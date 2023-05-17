# Connectwise/Screenconnect

Currently named Connectwise, but old Screenconnect name still persists

## Event logs

|Event Log | Event ID | Provider | Message
|-|-|-|-
|Application.evtx|0|`ScreenConnect Client (<random>)`* or `Screenconnect`| Cloud account administrator connected
|Application.evtx|0|`ScreenConnect Client (<random>)`* or `Screenconnect`| Cloud account administrator disconnected
|Application.evtx|0|`ScreenConnect Client (<random>)`* or `Screenconnect`| Transferred files with action 'Transfer'
|Application.evtx|0|`ScreenConnect Client (<random>)`* or `Screenconnect`| "Executed command of length" (but no command)

* No Evtxecmd map can cover this due to engineering decisions. The result will be in the Payload column.

## References

1. https://vikas-singh.notion.site/vikas-singh/Remote-Access-Software-Forensics-3e38d9a66ca0414ca9c882ad67f4f71b
1. https://www.youtube.com/watch?v=0qSWfbti4yM&list=PLfouvuAjspToNFRwt0ssrvaSMI11RcSgp&index=7
1. https://jsac.jpcert.or.jp/archive/2023/pdf/JSAC2023_1_1_yamashige-nakatani-tanaka_en.pdf