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
