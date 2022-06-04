<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/jaythemanchs/jaythemanchs.github.io/blob/main/assets/icons/logo_wide_dark.png?raw=true">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/jaythemanchs/jaythemanchs.github.io/blob/main/assets/icons/logo_wide.png?raw=true">
  <img alt="Shows an illustrated sun in light color mode and a moon with stars in dark color mode." src="https://github.com/jaythemanchs/jaythemanchs.github.io/blob/main/assets/icons/logo_wide.png?raw=true">
</picture>

# Server Manager For Minecraft
Welcome to the official **Server Manager For Minecraft** GitHub Repository 

[![Stable Release](https://img.shields.io/badge/dynamic/json?url=https://files.minecraftforge.net/net/minecraftforge/forge/promotions_slim.json&label=Stable&prefix=1.18.2-&query=$.promos["1.18.2-recommended"]&color=brightgreen&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyBjbGFzcz0ic3ZnLWlubGluZS0tZmEgZmEtc3RhciBmYS13LTE4IiBhcmlhLWhpZGRlbj0idHJ1ZSIgZGF0YS1pY29uPSJzdGFyIiBkYXRhLXByZWZpeD0iZmFzIiBmb2N1c2FibGU9ImZhbHNlIiByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCA1NzYgNTEyIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgo8cGF0aCBkPSJNMjU5LjMgMTcuOEwxOTQgMTUwLjIgNDcuOSAxNzEuNWMtMjYuMiAzLjgtMzYuNyAzNi4xLTE3LjcgNTQuNmwxMDUuNyAxMDMtMjUgMTQ1LjVjLTQuNSAyNi4zIDIzLjIgNDYgNDYuNCAzMy43TDI4OCA0MzkuNmwxMzAuNyA2OC43YzIzLjIgMTIuMiA1MC45LTcuNCA0Ni40LTMzLjdsLTI1LTE0NS41IDEwNS43LTEwM2MxOS0xOC41IDguNS01MC44LTE3LjctNTQuNkwzODIgMTUwLjIgMzE2LjcgMTcuOGMtMTEuNy0yMy42LTQ1LjYtMjMuOS01Ny40IDB6IiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K)](https://files.minecraftforge.net)
[![Latest Release](https://img.shields.io/badge/dynamic/json?url=https://files.minecraftforge.net/net/minecraftforge/forge/promotions_slim.json&label=Latest&prefix=1.18.2-&query=$.promos["1.18.2-latest"]&color=blue&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyBjbGFzcz0ic3ZnLWlubGluZS0tZmEgZmEtYnVnIGZhLXctMTYiIGFyaWEtaGlkZGVuPSJ0cnVlIiBkYXRhLWljb249ImJ1ZyIgZGF0YS1wcmVmaXg9ImZhcyIgZm9jdXNhYmxlPSJmYWxzZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTUxMS45ODggMjg4LjljLS40NzggMTcuNDMtMTUuMjE3IDMxLjEtMzIuNjUzIDMxLjFINDI0djE2YzAgMjEuODY0LTQuODgyIDQyLjU4NC0xMy42IDYxLjE0NWw2MC4yMjggNjAuMjI4YzEyLjQ5NiAxMi40OTcgMTIuNDk2IDMyLjc1OCAwIDQ1LjI1NS0xMi40OTggMTIuNDk3LTMyLjc1OSAxMi40OTYtNDUuMjU2IDBsLTU0LjczNi01NC43MzZDMzQ1Ljg4NiA0NjcuOTY1IDMxNC4zNTEgNDgwIDI4MCA0ODBWMjM2YzAtNi42MjctNS4zNzMtMTItMTItMTJoLTI0Yy02LjYyNyAwLTEyIDUuMzczLTEyIDEydjI0NGMtMzQuMzUxIDAtNjUuODg2LTEyLjAzNS05MC42MzYtMzIuMTA4bC01NC43MzYgNTQuNzM2Yy0xMi40OTggMTIuNDk3LTMyLjc1OSAxMi40OTYtNDUuMjU2IDAtMTIuNDk2LTEyLjQ5Ny0xMi40OTYtMzIuNzU4IDAtNDUuMjU1bDYwLjIyOC02MC4yMjhDOTIuODgyIDM3OC41ODQgODggMzU3Ljg2NCA4OCAzMzZ2LTE2SDMyLjY2NkMxNS4yMyAzMjAgLjQ5MSAzMDYuMzMuMDEzIDI4OC45LS40ODQgMjcwLjgxNiAxNC4wMjggMjU2IDMyIDI1Nmg1NnYtNTguNzQ1bC00Ni42MjgtNDYuNjI4Yy0xMi40OTYtMTIuNDk3LTEyLjQ5Ni0zMi43NTggMC00NS4yNTUgMTIuNDk4LTEyLjQ5NyAzMi43NTgtMTIuNDk3IDQ1LjI1NiAwTDE0MS4yNTUgMTYwaDIyOS40ODlsNTQuNjI3LTU0LjYyN2MxMi40OTgtMTIuNDk3IDMyLjc1OC0xMi40OTcgNDUuMjU2IDAgMTIuNDk2IDEyLjQ5NyAxMi40OTYgMzIuNzU4IDAgNDUuMjU1TDQyNCAxOTcuMjU1VjI1Nmg1NmMxNy45NzIgMCAzMi40ODQgMTQuODE2IDMxLjk4OCAzMi45ek0yNTcgMGMtNjEuODU2IDAtMTEyIDUwLjE0NC0xMTIgMTEyaDIyNEMzNjkgNTAuMTQ0IDMxOC44NTYgMCAyNTcgMHoiIGZpbGw9IndoaXRlIi8+Cjwvc3ZnPgo=
)](https://files.minecraftforge.net) [![](https://github.com/github/choosealicense.com/workflows/Build%20and%20Test/badge.svg)](https://github.com/github/choosealicense.com/actions?query=workflow%3ABuild%20and%20Test) [![Support](https://img.shields.io/badge/Patreon-Support-orange.svg?logo=Patreon)](https://www.patreon.com/LexManos)

## Installation

