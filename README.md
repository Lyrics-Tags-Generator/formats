# Formats

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

