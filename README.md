# auto-editor
edit videos fast


```
pip install auto-editor
```


# Remove non moving parts

```
auto-editor example.mp4 --edit motion:threshold=0.02 --export premiere
```
# Remove silent parts

```
auto-editor example.mp4 --export premiere
```

Auto-Editor can also export to:

DaVinci Resolve with --export resolve
Final Cut Pro with --export final-cut-pro
ShotCut with --export shotcut
Individual media clips with --export clip-sequence

