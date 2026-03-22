# ALP landing pages

Seven static landing pages—one folder per brand/domain. Each folder is a complete site: set your host’s **publish directory** to that folder name.

## Brands → folders

| Brand | Folder (deploy root) |
|-------|----------------------|
| Supreme Assets | `supremeassets` |
| MIBS | `mibs` |
| Sepharma | `sepharma` |
| Amber Energy | `amber-energy` |
| Amber Invest | `amber-invest` |
| Amber Swiss Holding | `amberswissholding` |
| Amber Trading | `amber-trading` |

## GitHub

Remote: [github.com/okok6858/alp-websites](https://github.com/okok6858/alp-websites)

```bash
git push -u origin main
```

## Customize

Each site is a white, minimal landing page: **header** (logo + nav), **hero**, **about**, **contact**, **footer**. Edit `index.html` for copy; swap `contact@example.com`, phone (`—`), and office lines. Shared layout styles live in each folder’s `styles.css` (copies of the same file).
