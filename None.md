## None

### (none)::[default]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio,{title} full song,{artist} {title} full song,{title} official
```

### (none)::[feature-1]

```ssh
{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{artist} {firstFeature} {title} official audio,{artist} {firstFeature} {title} track,{artist} {firstFeature} {title} song
```

### (none)::includes[default]&&[feature-1]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio,{title} full song,{artist} {title} full song,{title} official,{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{artist} {firstFeature} {title} official audio,{artist} {firstFeature} {title} track,{artist} {firstFeature} {title} song
```

### (none)::[feature-2]

```ssh
{secondFeature},{artist} {secondFeature},{secondFeature} {title},{artist} {secondFeature} {title},{artist} {secondFeature} {title} official audio,{artist} {secondFeature} {title} track
```

### (none)::includes[default]&&[feature-1]&&[feature-2]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio,{title} full song,{artist} {title} full song,{title} official,{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{artist} {firstFeature} {title} official audio,{artist} {firstFeature} {title} track,{artist} {firstFeature} {title} song,{secondFeature},{artist} {secondFeature},{secondFeature} {title},{artist} {secondFeature} {title},{artist} {secondFeature} {title} official audio,{artist} {secondFeature} {title} track
```

### (none)::[feature-3]

```ssh
{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},{artist} {thirdFeature} {title},{artist} {thirdFeature} {title} official audio
```

### (none)::includes[default]&&[feature-1]&&[feature-2]&&[feature-3]

```ssh
{artist} {title},{artist},{title},{title} {artist},{artist} - {title},{title} official audio,{artist} new song,{artist} music,{artist} {title} official audio,{artist} {title} song,{title} {artist} audio,{title} full song,{artist} {title} full song,{title} official,{firstFeature},{artist} {firstFeature},{firstFeature} {title},{artist} {firstFeature} {title},{artist} {firstFeature} {title} official audio,{artist} {firstFeature} {title} track,{artist} {firstFeature} {title} song,{secondFeature},{artist} {secondFeature},{secondFeature} {title},{artist} {secondFeature} {title},{artist} {secondFeature} {title} official audio,{artist} {secondFeature} {title} track,{thirdFeature},{artist} {thirdFeature},{thirdFeature} {title},{artist} {thirdFeature} {title},{artist} {thirdFeature} {title} official audio
```

### (none)::[@tiktok=true@]

```ssh
tiktok,{title} tiktok,trending tiktok,tiktok songs
```
