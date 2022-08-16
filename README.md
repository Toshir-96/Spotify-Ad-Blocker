<center>
    <h1 align="center">Spotify Ad Blocker</h1>
    <h4 align="center">A multi-purpose adblocker and skip-bypass for the <strong>Windows</strong> Spotify desktop application.</h4>
    <h5 align="center">Please support Spotify by purchasing premium</h5>
    <p align="center">
        <strong>Last updated:</strong> 29 October 2021<br>
        <strong>Last tested version:</strong> 1.1.89.862.g94554d24
    </p> 
</center>

#### Important checks before installing:

0. Update Windows, update Spotify and update BlockTheSpot
1. Go to "Windows Security" -> "Virus & Threat Protection"
2. Click "Allowed threats" -> "Remove all allowed threats"
3. Autoinstaller requirements can be found [here](https://github.com/amd64fox/SpotX#system-requirements)

### Features:

- Blocks all banner/video/audio ads within the app
- Retains friend, vertical video and radio functionality
- Unlocks the skip function for any track
- Addtional features unlocked by [Spotify Ad blocker](https://github.com/Toshir-96/Spotify-Ad-Blocker)

:warning: This mod is for the [**Desktop Application**](https://www.spotify.com/download/windows/) of Spotify on Windows only and **not the Microsoft Store version**.

### Installation/Update:

- Just download and run [Spotify Ad blocker](https://github.com/Toshir-96/Spotify-Ad-Blocker)

or

#### Fully automated installation via PowerShell

- Run The following command in PowerShell:

```ps1
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; iex "& { $((iwr -useb 'https://raw.githubusercontent.com/amd64fox/SpotX/main/Install.ps1').Content) } -confirm_uninstall_ms_spoti -confirm_spoti_recomended_over -podcasts_on -cache_off -block_update_off -exp_standart -hide_col_icon_off -start_spoti"
```

- Checkout [Spotify Ad blocker Repo](https://github.com/Toshir-96/Spotify-Ad-Blocker) for more options and features.

#### Manual installation

1. Browse to your Spotify installation folder `%APPDATA%\Spotify`
2. Rename `chrome_elf.dll` to `chrome_elf_bak.dll`. The naming is important.
3. Download `chrome_elf.zip` from [releases](https://github.com/mrpond/BlockTheSpot/releases)
4. Unzip `chrome_elf.dll` and `config.ini` to Spotify directory.

### Uninstall:

- Just run [uninstall.bat](https://github.com/Toshir-96/Spotify-Ad-Blocker/Uninstall.bat)
  or
- Reinstall Spotify

### Additional Notes:

- "chrome_elf.dll" gets replaced by the Spotify installer each time it updates, hence why you'll probably need to apply the patch again when it happens
- [Spicetify](https://github.com/Toshiro-96) users will need to reapply BlockTheSpot after applying a Spicetify themes/patches.
- If the automatic install/uninstall scripts do not work, open issue at [SpotX](https://github.com/Toshir-96/Spotify-Ad-Blocker) or contact [Toshiro](https://github.com/Toshir-96).
- For more support and discussions, join our [Discord server](https://discord.gg/p43cusgUPm).

### DISCLAIMER

- Autoinstaller is maintaned at [Spotify Ad blocker](https://github.com/Toshir-96/Spotify-Ad-Blocker). Any issue related to it should be opened in the said repo. 
- Ad blocking is the main concern of this repo. Any other feature provided by SpotX or consequence of using those features will be the sole repsonsiblity of the user and not either BlockTheSpot or SpotX team will be responsible.
