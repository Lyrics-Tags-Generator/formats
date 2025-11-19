# Nightcore/Sped Up

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
