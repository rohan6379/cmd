Audio and Music WAV File Download and Playback
This guide provides commands to download and play WAV audio and music files using curl and PowerShell. The commands are formatted for easy copying.
Download Audio WAV File
To download the audio WAV file, use the following command:
curl -O http://instead-ts.gl.at.ply.gg:33117/audio.wav

Play Audio WAV File
To play the downloaded audio WAV file using PowerShell, use this command:
powershell -c (New-Object Media.SoundPlayer 'audio.wav').PlaySync()

Download Music WAV File
To download the music WAV file, use the following command:
curl -O http://instead-ts.gl.at.ply.gg:33117/music.wav

Play Music WAV File
To play the downloaded music WAV file using PowerShell, use this command:
powershell -c (New-Object Media.SoundPlayer 'music.wav').PlaySync()

Note: Ensure the file names in the PowerShell commands match the downloaded files (audio.wav or music.wav). Run these commands in a terminal or command prompt with curl and PowerShell installed.
