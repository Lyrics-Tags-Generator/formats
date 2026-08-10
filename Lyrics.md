# Lyrics

### (lyrics)::[default]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{title},{artist},{title} {artist},lyrics
```

### (lyrics)::[feature-1]:

```ssh
{firstFeature},{firstFeature} {title} lyrics,{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature}
```

### (lyrics)::includes[default]&&[feature-1]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{title},{artist},{title} {artist},lyrics,{firstFeature},{firstFeature} {title} lyrics,{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature}
```

### (lyrics)::[feature-2]:

```ssh
{secondFeature},{secondFeature} {title} lyrics,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (lyrics)::includes[default]&&[feature-1]&&[feature-2]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{title},{artist},{title} {artist},lyrics,{firstFeature},{firstFeature} {title} lyrics,{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature},{secondFeature},{secondFeature} {title} lyrics,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature}
```

### (lyrics)::[feature-3]:

```ssh
{thirdFeature},{thirdFeature} {title} lyrics,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (lyrics)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]:

```ssh
{artist} {title},{artist} {title} lyrics,{title} lyrics,{title} {artist} lyrics,lyrics {title},{title},{artist},{title} {artist},lyrics,{firstFeature},{firstFeature} {title} lyrics,{firstFeature} lyrics,{firstFeature} {title},{artist} {firstFeature},{title} {firstFeature},{secondFeature},{secondFeature} {title} lyrics,{secondFeature} {title},{artist} {secondFeature},{title} {secondFeature},{thirdFeature},{thirdFeature} {title} lyrics,{thirdFeature} {title},{artist} {thirdFeature},{title} {thirdFeature}
```

### (lyrics)::[@tiktok=true@]:

```ssh
tiktok,{title} tiktok,trending tiktok,tiktok songs
```
