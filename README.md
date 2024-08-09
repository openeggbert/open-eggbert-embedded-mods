# open-eggbert-embedded-mods

```
for i in *.BLP; do convert ${i} ${i%BLP}PNG; done
for i in *.BLP; do mv ${i} ${i%BLP}MID; done
for i in *.BLP; do mv ${i} ${i%BLP}WAV; done

for i in *.blp; do convert ${i} ${i%blp}png; done
for i in *.blp; do mv ${i} ${i%blp}mid; done
for i in *.blp; do mv ${i} ${i%blp}wav; done
```
