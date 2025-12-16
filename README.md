# Formats

Our format string templates for all the supported formats.

## Lyrics

### (lyrics)::[default]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{artist} lyrics {title},{title} lyric video,{artist} lyrics,lyrics {artist},{title},{artist},{title} {artist},lyrics {title} {artist},lyrics {artist} {title},lyrics
```

### (lyrics)::[feature-1]:

```ssh
{firstFeature},{firstFeature} {title} lyrics,lyrics {firstFeature} {title},{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature}
```

### (lyrics)::includes[default]&&[feature-1]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{artist} lyrics {title},{title} lyric video,{artist} lyrics,lyrics {artist},{title},{artist},{title} {artist},lyrics {title} {artist},lyrics {artist} {title},lyrics,{firstFeature},{firstFeature} {title} lyrics,lyrics {firstFeature} {title},{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature}
```

### (lyrics)::[feature-2]:

```ssh
{secondFeature},{secondFeature} {title} lyrics,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (lyrics)::includes[default]&&[feature-1]&&[feature-2]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{artist} lyrics {title},{title} lyric video,{artist} lyrics,lyrics {artist},{title},{artist},{title} {artist},lyrics {title} {artist},lyrics {artist} {title},lyrics,{firstFeature},{firstFeature} {title} lyrics,lyrics {firstFeature} {title},{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature},{secondFeature},{secondFeature} {title} lyrics,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (lyrics)::[feature-3]:

```ssh
{thirdFeature},{thirdFeature} {title} lyrics,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (lyrics)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{artist} lyrics {title},{title} lyric video,{artist} lyrics,lyrics {artist},{title},{artist},{title} {artist},lyrics {title} {artist},lyrics {artist} {title},lyrics,{firstFeature},{firstFeature} {title} lyrics,lyrics {firstFeature} {title},{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature},{secondFeature},{secondFeature} {title} lyrics,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature},{thirdFeature},{thirdFeature} {title} lyrics,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (lyrics)::[@tiktok=true@]:

```ssh
tiktok,{title} tiktok,trending tiktok,tiktok songs
```

## Bass Boosted

### (bassboosted)::[default]

```ssh
{artist},{title},{title} bass boosted,{title} bass boosted {artist},{title} {artist},{title} {artist} bass boosted,{artist} {title} bass boosted,{artist} {title},{artist} - {title},{artist} - {title} bass boosted,{title} {artist} bass boost,{artist} bass boosted,{title} bass boost,bass boost,bass boosted,bass boosted car playlist,bass boost car playlist
```

### (bassboosted)::[feature-1]

```ssh
{firstFeature},{firstFeature} {title} bass boosted
```

### (bassboosted)::includes[default]&&[feature-1]

```ssh
{artist},{title},{title} bass boosted,{title} bass boosted {artist},{title} {artist},{title} {artist} bass boosted,{artist} {title} bass boosted,{artist} {title},{artist} - {title},{artist} - {title} bass boosted,{title} {artist} bass boost,{artist} bass boosted,{title} bass boost,bass boost,bass boosted,bass boosted car playlist,bass boost car playlist,{firstFeature},{firstFeature} {title} bass boosted
```

### (bassboosted)::[feature-2]

```ssh
{secondFeature},{secondFeature} {title} bass boosted
```

### (bassboosted)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist},{title},{title} bass boosted,{title} bass boosted {artist},{title} {artist},{title} {artist} bass boosted,{artist} {title} bass boosted,{artist} {title},{artist} - {title},{artist} - {title} bass boosted,{title} {artist} bass boost,{artist} bass boosted,{title} bass boost,bass boost,bass boosted,bass boosted car playlist,bass boost car playlist,{firstFeature},{firstFeature} {title} bass boosted,{secondFeature},{secondFeature} {title} bass boosted
```

### (bassboosted)::[feature-3]

```ssh
{thirdFeature},{thirdFeature} {title} bass boosted
```

### (bassboosted)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist},{title},{title} bass boosted,{title} bass boosted {artist},{title} {artist},{title} {artist} bass boosted,{artist} {title} bass boosted,{artist} {title},{artist} - {title},{artist} - {title} bass boosted,{title} {artist} bass boost,{artist} bass boosted,{title} bass boost,bass boost,bass boosted,bass boosted car playlist,bass boost car playlist,{firstFeature},{firstFeature} {title} bass boosted,{secondFeature},{secondFeature} {title} bass boosted,{thirdFeature},{thirdFeature} {title} bass boosted
```

### (bassboosted)::[@tiktok=true@]

```ssh
tiktok,{title} tiktok,trending tiktok,tiktok songs
```

## Nightcore/Sped Up

### (nightcore)::[default]

```ssh
{artist},{title},{title} nightcore,{title} sped up,{title} sped up {artist},{artist} {title},{artist} {title} sped up,{artist} nightcore,{artist} sped up,nightcore
```

### (nightcore)::[feature-1]

```ssh
{firstFeature},{artist} {firstFeature},{firstFeature} {title},title {firstFeature}
```

### (nightcore)::includes[default]&&[feature-1]

```ssh
{artist},{title},{title} nightcore,{title} sped up,{title} sped up {artist},{artist} {title},{artist} {title} sped up,{artist} nightcore,{artist} sped up,nightcore,{firstFeature},{artist} {firstFeature},{firstFeature} {title},title {firstFeature}
```

### (nightcore)::[feature-2]

```ssh
{secondFeature},{artist} {secondFeature},{secondFeature} {title},title {secondFeature}
```

### (nightcore)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist},{title},{title} nightcore,{title} sped up,{title} sped up {artist},{artist} {title},{artist} {title} sped up,{artist} nightcore,{artist} sped up,nightcore,{firstFeature},{artist} {firstFeature},{firstFeature} {title},title {firstFeature},{secondFeature},{artist} {secondFeature},{secondFeature} {title},title {secondFeature}
```

### (nightcore)::[feature-3]

```ssh
{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},title {thirdFeature}
```

### (nightcore)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist},{title},{title} nightcore,{title} sped up,{title} sped up {artist},{artist} {title},{artist} {title} sped up,{artist} nightcore,{artist} sped up,nightcore,{firstFeature},{artist} {firstFeature},{firstFeature} {title},title {firstFeature},{secondFeature},{artist} {secondFeature},{secondFeature} {title},title {secondFeature},{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},title {thirdFeature}
```

### (nightcore)::[@tiktok=true@]

```ssh
{artist} {title} sped up tiktok remix,{title} sped up tiktok version
```

## Slowed & Reverb

### (slowed)::[default]

```ssh
{artist},{title},{artist} {title},{artist} {title} slowed,{artist} {title} slowed reverb,{artist} {title} slowed to perfection,{title} {artist},{title} slowed,{artist} - {title},{artist} - {title} slowed,{artist} - {title} slowed reverb,{title} slowed to perfection,{artist} {title} slowed and reverb,slowed and reverb songs
```

### (slowed)::[feature-1]

```ssh
{firstFeature} {title} slowed,{artist} {firstFeature} {title} slowed,{firstFeature}
```

### (slowed)::includes[default]&&[feature-1]

```ssh
{artist},{title},{artist} {title},{artist} {title} slowed,{artist} {title} slowed reverb,{artist} {title} slowed to perfection,{title} {artist},{title} slowed,{artist} - {title},{artist} - {title} slowed,{artist} - {title} slowed reverb,{title} slowed to perfection,{artist} {title} slowed and reverb,slowed and reverb songs,{firstFeature} {title} slowed,{artist} {firstFeature} {title} slowed,{firstFeature}
```

### (slowed)::[feature-2]

```ssh
{secondFeature},{artist} {secondFeature},{secondFeature} {title},title {secondFeature}
```

### (slowed)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist},{title},{artist} {title},{artist} {title} slowed,{artist} {title} slowed reverb,{artist} {title} slowed to perfection,{title} {artist},{title} slowed,{artist} - {title},{artist} - {title} slowed,{artist} - {title} slowed reverb,{title} slowed to perfection,{artist} {title} slowed and reverb,slowed and reverb songs,{firstFeature} {title} slowed,{artist} {firstFeature} {title} slowed,{firstFeature},{secondFeature},{artist} {secondFeature},{secondFeature} {title},title {secondFeature}
```

### (slowed)::[feature-3]

```ssh
{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},title {thirdFeature}
```

### (slowed)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist},{title},{artist} {title},{artist} {title} slowed,{artist} {title} slowed reverb,{artist} {title} slowed to perfection,{title} {artist},{title} slowed,{artist} - {title},{artist} - {title} slowed,{artist} - {title} slowed reverb,{title} slowed to perfection,{artist} {title} slowed and reverb,slowed and reverb songs,{firstFeature} {title} slowed,{artist} {firstFeature} {title} slowed,{firstFeature},{secondFeature},{artist} {secondFeature},{secondFeature} {title},title {secondFeature},{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},title {thirdFeature}
```

### (slowed)::[@tiktok=true@]

```ssh
slowed tiktok songs,{title} slowed down tiktok version
```

## Letra

### (letra)::[default]

```ssh
{artist},{title},{artist} {title} letra,{artist} {title},{title} {artist},{title} letra,letra {title},letra {title} {artist},{artist} letra,{artist} letra {title},{title} letra {artist},letra {artist},{artist} - {title},{artist} - {title}
```

### (letra)::[feature-1]

```ssh
{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} letra,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature}
```

### (letra)::includes[default]&&[feature-1]

```ssh
{artist},{title},{artist} {title} letra,{artist} {title},{title} {artist},{title} letra,letra {title},letra {title} {artist},{artist} letra,{artist} letra {title},{title} letra {artist},letra {artist},{artist} - {title},{artist} - {title},{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} letra,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature}
```

### (letra)::[feature-2]

```ssh
{secondFeature},{secondFeature} {title} letra,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (letra)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist},{title},{artist} {title} letra,{artist} {title},{title} {artist},{title} letra,letra {title},letra {title} {artist},{artist} letra,{artist} letra {title},{title} letra {artist},letra {artist},{artist} - {title},{artist} - {title},{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} letra,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature},{secondFeature},{secondFeature} {title} letra,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (letra)::[feature-3]

```ssh
{thirdFeature},{thirdFeature} {title} letra,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (letra)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist},{title},{artist} {title} letra,{artist} {title},{title} {artist},{title} letra,letra {title},letra {title} {artist},{artist} letra,{artist} letra {title},{title} letra {artist},letra {artist},{artist} - {title},{artist} - {title},{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} letra,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature},{secondFeature},{secondFeature} {title} letra,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature},{thirdFeature},{thirdFeature} {title} letra,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (letra)::[@tiktok=true@]

```ssh
{title} tiktok,{artist} tiktok,latin tiktok
```

## Testo

### (testo)::[default]

```ssh
{artist},{title},{artist} {title} testo,{artist} {title},{title} {artist},{title} testo,testo {title},testo {title} {artist},{artist} testo,{artist} testo {title},{title} testo {artist},testo {artist},{artist} - {title},{artist} - {title} testo,testo
```

### (testo)::[feature-1]

```ssh
{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} testo,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature}
```

### (testo)::includes[default]&&[feature-1]

```ssh
{artist},{title},{artist} {title} testo,{artist} {title},{title} {artist},{title} testo,testo {title},testo {title} {artist},{artist} testo,{artist} testo {title},{title} testo {artist},testo {artist},{artist} - {title},{artist} - {title} testo,testo,{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} testo,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature}
```

### (testo)::[feature-2]

```ssh
{secondFeature},{secondFeature} {title} testo,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (testo)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist},{title},{artist} {title} testo,{artist} {title},{title} {artist},{title} testo,testo {title},testo {title} {artist},{artist} testo,{artist} testo {title},{title} testo {artist},testo {artist},{artist} - {title},{artist} - {title} testo,testo,{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} testo,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature},{secondFeature},{secondFeature} {title} testo,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (testo)::[feature-3]

```ssh
{thirdFeature},{thirdFeature} {title} testo,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (testo)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist},{title},{artist} {title} testo,{artist} {title},{title} {artist},{title} testo,testo {title},testo {title} {artist},{artist} testo,{artist} testo {title},{title} testo {artist},testo {artist},{artist} - {title},{artist} - {title} testo,testo,{firstFeature} {title},{artist} {firstFeature} {title},{firstFeature} {title} testo,{title} {firstFeature},{artist} {firstFeature},{firstFeature} {artist},{firstFeature},{secondFeature},{secondFeature} {title} testo,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature},{thirdFeature},{thirdFeature} {title} testo,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (testo)::[@tiktok=true@]

```ssh
{title} tiktok,{artist} tiktok, testo tiktok, italian tiktok
```

## Phonk

### (phonk)::[default]

```ssh
{artist},{title},{artist} {title},{title} {artist},{title} phonk,{artist} {title} phonk,{title} {artist} phonk,{artist} phonk,brazilian phonk,tiktok phonk,hard phonk,{title} funk,{artist} funk,{artist} {title} funk
```

### (phonk)::[feature-1]

```ssh
{firstFeature},{firstFeature} {title},{artist} {firstFeature} {title}
```

### (phonk)::includes[default]&&[feature-1]

```ssh
{artist},{title},{artist} {title},{title} {artist},{title} phonk,{artist} {title} phonk,{title} {artist} phonk,{artist} phonk,brazilian phonk,tiktok phonk,hard phonk,{title} funk,{artist} funk,{artist} {title} funk,{firstFeature},{firstFeature} {title},{artist} {firstFeature} {title}
```

### (phonk)::[feature-2]

```ssh
{secondFeature},{secondFeature} {title} phonk,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (phonk)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist},{title},{artist} {title},{title} {artist},{title} phonk,{artist} {title} phonk,{title} {artist} phonk,{artist} phonk,brazilian phonk,tiktok phonk,hard phonk,{title} funk,{artist} funk,{artist} {title} funk,{firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{secondFeature},{secondFeature} {title} phonk,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (phonk)::[feature-3]

```ssh
{thirdFeature},{thirdFeature} {title} phonk,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (phonk)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist},{title},{artist} {title},{title} {artist},{title} phonk,{artist} {title} phonk,{title} {artist} phonk,{artist} phonk,brazilian phonk,tiktok phonk,hard phonk,{title} funk,{artist} funk,{artist} {title} funk,{firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{secondFeature},{secondFeature} {title} phonk,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature},{thirdFeature},{thirdFeature} {title} phonk,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (phonk)::[@tiktok=true@]

```ssh
tiktok,{title} tiktok,trending tiktok,tiktok songs,phonk tiktok,trending phonk
```

## None

### (none)::[default]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio
```

### (none)::[feature-1]

```ssh
{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title}
```

### (none)::includes[default]&&[feature-1]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio,{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title}
```

### (none)::[feature-2]

```ssh
{secondFeature},{artist} {secondFeature},{secondFeature} {title},{artist} {secondFeature} {title}
```

### (none)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio,{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{secondFeature},{artist} {secondFeature},{secondFeature} {title},{artist} {secondFeature} {title}
```

### (none)::[feature-3]

```ssh
{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},{artist} {thirdFeature} {title}
```

### (none)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio,{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{secondFeature},{artist} {secondFeature},{secondFeature} {title},{artist} {secondFeature} {title},{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},{artist} {thirdFeature} {title}
```

### (none)::[@tiktok=true@]

```ssh
tiktok,{title} tiktok,trending tiktok,tiktok songs
```
