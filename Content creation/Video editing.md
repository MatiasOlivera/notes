### Clip steps
1. Create 2 timelines: one for 16:9 to cut and 9:16 for tik tok
2. Rough cut (assemble footage) + Fine cut (review first edit, add b roll, text, transitions, fix sound)
3. ***Normalize volume** per track* DO NOT USE, its just a volume knob
4. Voice: -18lufs. Videogame -10lufs diff
5. Adjust pan to see the action ALL THE TIME
6. Add @matiasox and video title
7. Use solo in voice track and **Subtitles**: Linea de tiempo > Herramientas IA > Crear subtitulos. 
8. Analyze audio levels: Timeline > Bounce mix to track > New track
9. **Export for Shorts:** Youtube 1080, type nvidia, audio optimize to standard
10. ~~Add **transition between videos**~~
11. ~~Add **fade-out** at the end (30 sec)~~
12. ~~Add **transitions between audios** -> Shift + T~~

13. Efectos > Titulos > Subtitulos > Animated > arrastrar sobre Subtitulo 1 (rectangulo izquierda, no en la linea)
14. **Magic Zoom**: Edición (abajo) > Efectos > MagicToolkit > MagicZoom. *Usar clip de ajuste siempre que se pueda. Efectos -> Clip de ajuste. El efecto va sobre el clip*

### 3 stages
- Rough cut: assemble footage, remove silences and bad takes
- Fine cut: review first edit, add b roll, text, transitions, fix sound
- Final cut: final review, add music, color grade, export

#### Long-form YouTube
- remove loading screens / menus
- remove dead time
- remove long silences
- normalize audio
- good thumbnail/title
- Detect silent to mark silence (select clip, Timeline > Detect silence -40db, 0.5s)
- Farlight > Normalize audio level to all clips
- Mark chapters with M

### Audio
Shorts: People usually watch Shorts on phones in noisy environments. -14 LUFS
Long-form gameplay: -16 LUFS
- Voice: around **-16 to -14 LUFS short-term** while speaking.
- Game: about **6–10 LU quieter than your voice** most of the time.
- Music: **10–15 LU below your voice**.

**Voice: -17 LUFS. Discord: -23LUFS. Game: -27LUFS** 
### Fonts
- top: SF Pro rounded, roboto condensed
- inter, san francisco, roboto?
- TikTok Sans
- Rubik
- Rubik Mono: twitch overlay socials

Tik Tok:
- Extra bold. Sequel, _Montserrat Black_, _Poppins ExtraBold_, _Archivo Black_, or _Inter Black_
- White text + black outline
- Word-by-word highlight captions
- Color #F2CA50
- Background: #402C13

# Keybindings
Q: delete left
W: cut
E: delete right
**Editing** L 1x -> 2x. K: pause. J: reverse it. Shilf + L: small increment
Ctrl + B = corte
**Finish** Ctrl + Shift + E = eliminar espacios vacios
Shift + T transicion de audio a todos los audios
F9: insertar clip
Shift + del = eliminar clip y mover
alt + n = desactivar iman al cambiar corte del clip
Ctrl + Shift + mover clip = intercambiar clip de lugar
Alt + Z = cambiar zoom linea de tiempo

### Timeline
- Use a big audio track and a small video track to edit faster, its easier to see waveforms

### Shortcuts
- Delete: delete video (delete)
- Shift+delete: delete video and move timeline (ripple edit)
- Alt+wheel: timeline zoom
- Shift+wheel: track zoom
- Ctrl+Shift+< o > : suffle videos
- J-K-L: back, play, forward
- Ctrl+F: fullscreen
- Alt+drag middle click: move timeline

### Text
- Use Text+
- Use video transitions
- Alt+move: duplicate text

### Color
Remember to reset your eyes, your eyes get used to the images
Compare shots with a hero shot, don't correct one clip at the time
- Ctrl+middle click: copy color correction
- Ctrl+D: enable/disable color correction
- Video preview: grab still. Gallery: play still: compare shots

### Fairlight
- I + O: input and output to loop audio

#### Grouping
- Ad-hoc group: ctrl + click -> select channels. alt + click: change attributes
- VCA: independent and grouped channels at the same time
- Group: go to Groups in top tab

#### Routing
- Busses: custom signal chains (what path your audio takes). Allows to create sub-mixes. Got to Failight > Bus format > Create bus. Remember to set the bus output to master bus to have sound
- Bus sends: send a copy of the signal to a different bus. Allows to create a effects bus and send multiple signals from multiple tracks but alter the volume that being sent

- Sidechains: allows to one effect respond to a different track.

#### Compound meters
Blue: below. Yellow: good: Red: bad

#### Automation reset
Fairlight menu > Automation > Mix List.

#### Dialogue leveler
Allow wider: it doesn't affect the audio too much (for natural sounding audio)
Optimize moderate levels: recommended
More life:
Lift soft: when there's much diff between quiet and loud

Background reduction: only when it's absolutely necessary
**Three dots: bounce audio effect**
Instead of adding gain to the audio leveler, use audio normalization