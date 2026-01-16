Config and Overlay files for use with for `samples/net/wifi/shell` and board `nrf7002dk/nrf5340/cpuapp`  

- Copy these files to `samples/net/wifi/shell`

- Update UART_TX and UART_RX pins in overlay file as you see fit.

- Build
```
west build -b nrf7002dk/nrf5340/cpuapp samples/net/wifi/shell/ -- -DDTC_OVERLAY_FILE=ms12sf1.overlay -DEXTRA_CONF_FILE=ms12sf1.conf
```
