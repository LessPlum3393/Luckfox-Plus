# Luckfox Plus
|                    | Working?                 | Note                                                                                    |
| :----------------: | :----------------------: | :-------------------------------------------------------------------------------------: |
| tailscale          | ❌                        | -                                                                                       |
| ubuntu             | ✅                      | Official image by luckfox                                                               |
| temperature        | ✅                      | Type ``echo $(( $(< /sys/class/thermal/thermal_zone0/temp) / 1000 ))°C``, and the output will be like 49°C |
| apt                | ✅                      | Slow when installing package. Only available for Debian-based systems.                   |
| screen             | ❔                       | Not tested yet |
| cpuminer        | ❔                       | Not tested yet |
