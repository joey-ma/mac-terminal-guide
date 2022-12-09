# mac-terminal-guide
Exploring the world of Terminal on macOS.

For a full list of Mac Termainal Commands, you can see here:
https://www.makeuseof.com/tag/mac-terminal-commands-cheat-sheet/

## Personal Touch

| Syntax      | Description |
| ----------- | ----------- |
| export PATH=$PATH:absolute/path to/program/ | Execute a program via terminal only in your current session. If you use a program regularly, add the path to shell configuration file. |
| top | display live information about currently running processes. |
| system_profiler | reports system hardware and software configuration. |
| system_profiler -listDataTypes | Shows a list of the available data types. |
| system_profiler SPDisplaysDataType | Shows a list of the available data types. |

Example: 

```zsh
yoyoyojoe@Joeys-MacBook-Pro ~ % system_profiler SPDisplaysDataType
Graphics/Displays:

    Apple M1 Pro:

      Chipset Model: Apple M1 Pro
      Type: GPU
      Bus: Built-In
      Total Number of Cores: 16
      Vendor: Apple (0x106b)
      Metal Family: Supported, Metal GPUFamily Apple 7
      Displays:
        Color LCD:
          Display Type: Built-in Liquid Retina XDR Display
          Resolution: 3456 x 2234 Retina
          Main Display: Yes
          Mirror: Off
          Online: Yes
          Automatically Adjust Brightness: Yes
          Connection Type: Internal
        HP V24i:
          Resolution: 1920 x 1080 (1080p FHD - Full High Definition)
          UI Looks like: 1920 x 1080 @ 60.00Hz
          Mirror: Off
          Online: Yes
          Rotation: Supported
        HP V24i:
          Resolution: 1080 x 1920
          UI Looks like: 1080 x 1920 @ 60.00Hz
          Mirror: Off
          Online: Yes
          Rotation: 90

```
