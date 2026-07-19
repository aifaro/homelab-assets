# homelab-assets
External assets for home lab

Repo público solo para assets sin nada sensible (imágenes de branding, etc.), pensado para servirse vía CDN sin ocupar espacio en la Pi.

## branding/
Logo, favicon y fondo usados en el login de authentik (System → Brands en `https://auth.nephei.org/if/admin/`).

## URLs (jsDelivr)
```
https://cdn.jsdelivr.net/gh/aifaro/homelab-assets@main/branding/<archivo>
```
jsDelivr cachea ~7 días. Si actualizas un archivo y no ves el cambio, purga la cache:
```
https://purge.jsdelivr.net/gh/aifaro/homelab-assets@main/branding/<archivo>
```

