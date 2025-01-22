# Luckfox Plus
|                    | Working?                 | Note                                                                                    |
| :----------------: | :----------------------: | :-------------------------------------------------------------------------------------: |
| Tailscale          | ❌                        | -                                                                                       |
| Ubuntu             | ✅                      | Official image by luckfox                                                               |
| Temperature        | ✅                      | Type ``echo $(( $(< /sys/class/thermal/thermal_zone0/temp) / 1000 ))°C``, and the output will be like 49°C |
| Apt                | ✅                      | Slow when installing package. Only available for Debian-based systems.                   |
| Screen             | ❔                       | Not tested yet |
| Cpuminer        | ❔                       | Not tested yet |
