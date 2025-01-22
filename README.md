![RV1103](https://raw.githubusercontent.com/LessPlum3393/Luckfox-Plus/refs/heads/main/rv1103.png)
![Luckfox Plus](https://raw.githubusercontent.com/LessPlum3393/Luckfox-Plus/refs/heads/main/Luckfox-Pico-Plus-1-1600x1200.jpg)
# Luckfox Plus (RV1103)
|                    | Working?                 | Note                                                                                    |
| :----------------: | :-----------------------: | :-------------------------------------------------------------------------------------: |
| tailscale          | ❌                       | -                                                                                       |
| ubuntu             | ✅                        | Official image by luckfox                                                               |
| temperature        | ✅                      | Type ``echo $(( $(< /sys/class/thermal/thermal_zone0/temp) / 1000 ))°C``, and the output will be like 49°C |
| apt                | ✅                      | Slow when installing package. Only available for Debian-based systems.                   |
| screen             | ❔                       | Not tested yet |
| cpuminer        | ❔                       | Not tested yet |
| echo             | ✅                       | - |
| htop             | ✅                         | - |
