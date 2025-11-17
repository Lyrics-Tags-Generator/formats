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



