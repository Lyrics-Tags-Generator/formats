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
