
<h1 align="center"> YouTube_to_m3u </h1>

[![M3U_Bernama](https://github.com/varisrc/YouTube2m3u/actions/workflows/m3u_Bernama.yml/badge.svg)](https://github.com/varisrc/YouTube2m3u/actions/workflows/m3u_Bernama.yml)

[![M3U_SukaTV](https://github.com/varisrc/YouTube2m3u/actions/workflows/m3u_SukaTV.yml/badge.svg)](https://github.com/varisrc/YouTube2m3u/actions/workflows/m3u_SukaTV.yml)

[![M3U_ErrorScreen](https://github.com/varisrc/YouTube2m3u/actions/workflows/m3u_ErrorScreen.yml/badge.svg)](https://github.com/varisrc/YouTube2m3u/actions/workflows/m3u_ErrorScreen.yml)

`https://raw.githubusercontent.com/varisrc/YouTube2m3u/main/youtube.m3u`

Updated m3u links of YouTube live channels, **auto-updated every 1 hours**.


### Add more channels
Edit `youtube_channel_info.txt` to add your favourite YouTube livestreams

Create a pull request or connect: https://discord.gg/dmgYmAEdee

### Usage
Paste this URL: `https://raw.githubusercontent.com/varisrc/YouTube2m3u/main/youtube.m3u` to any player which supports M3U playlists

### Run the tool on your local machine
``` bash
git clone https://github.com/benmoose39/YouTube_to_m3u.git
cd YouTube_to_m3u
chmod +x autorun.sh
./autorun.sh
```

Do not forget to add a cron job set for every 4 hours(or 5) if you plan to run the script locally.
(At schedule:
    - cron: '0 0/1 * * *' ) in m3u_Generator.yml 1 is 1hr
    
### Support

🙂 https://www.buymeacoffee.com/benmoose39
    https://github.com/weareblahs/yttestlabs
    https://github.com/AqFad2811/randomlivefromyt
