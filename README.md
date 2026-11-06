# DaddyRP harita karoları

GTA V haritası, 256 px karolar: `<stil>/<z>/<x>/<y>.jpg`.

| Stil | Klasör | Zoom |
|---|---|---|
| Atlas | `atlas/` | 0–5 |
| Uydu | `satellite/` | 0–4 |

jsDelivr üzerinden kullanılır:

```
https://cdn.jsdelivr.net/gh/can9work/daddy_gang_maps@main/atlas/{z}/{x}/{y}.jpg
```

Koordinat dönüşümü (zoom 0, tüm harita tek bir 256 px karo; her zoom adımı ikiye katlar):

```
px = 0.02072 * x + 117.3
py = -0.0205 * y + 172.8
```
