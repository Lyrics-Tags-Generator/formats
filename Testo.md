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
