THIS IS CURRENT AS OF VERSION 33.1.592088.0

### ready-at-dawn-echo-arena/\_data/5932408047/rad15/win10/

## -> manifests

    If the manifest files are indeed ZSTD files, they are missing the file signature and frame descriptor as outlined here:
    https://github.com/facebook/zstd/blob/dev/doc/zstd_compression_format.md#frame_header

### ready-at-dawn-echo-arena_local\r14logs

    [07-08-2022] [18:22:35]: No item assignment found for item: 0x7F630C94B0EAFD0B
    [07-08-2022] [18:22:35]: No item assignment found for item: 0xEB76E6852CB20D25
    [07-08-2022] [18:22:35]: No item assignment found for item: 0x1719C695329F5815
    [07-08-2022] [18:22:35]: No item assignment found for item: 0x7CAC5BAF4E884102
    [07-08-2022] [18:22:35]: No item assignment found for item: 0x59DA5AF3C4F11CA2
    [07-08-2022] [18:22:35]: No item assignment found for item: 0xB0CACC88C22CE548
    [07-08-2022] [18:22:35]: No item assignment found for item: 0x925AFFCCBB93C0BE

### Interesting Findings

Game seems to be accessing `appdata/local/d3dscache`
