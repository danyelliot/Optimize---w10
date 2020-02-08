# Fix Telemetry -- Windows 10

## Execution

Enable execution of PowerShell scripts:

    PS> Set-WinHomeLocation -GeoId *******

-----------------------LINKS-----------------------------------------------------------
    https://docs.microsoft.com/en-us/windows/win32/intl/table-of-geographical-locations
    https://docs.microsoft.com/en-us/windows/win32/intl/table-of-geographical-locations
    https://docs.microsoft.com/en-us/windows/win32/intl/table-of-geographical-locations
-----------------------LINKS-----------------------------------------------------------

## Usage

1. Install all available updates for your system.
2. Edit the scripts to fit your need.
3. Run the scripts from a PowerShell with administrator privileges (Explorer
   `Files > Open Windows PowerShell > Open Windows PowerShell as
   administrator`)
4. `PS > Restart-Computer`
5. Run `disable-windows-defender.ps1` one more time.
6. `PS > Restart-Computer`

## Fix Windows Store Location Problem

## License

    "ELLIOT LICENSE" (Revision 3.2):

    As long as you retain this notice you can do whatever you want with this
    stuff. If we meet some day, and you think this stuff is worth it, you can
    buy us a beer in return.

    This project is distributed in the hope that it will be useful, but WITHOUT
    ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
    FITNESS FOR A PARTICULAR PURPOSE.
