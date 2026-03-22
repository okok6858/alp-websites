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

```bash
git remote add origin https://github.com/okok6858/REPO_NAME.git
git push -u origin main
```

Or create and push with GitHub CLI (from this directory):

```bash
gh repo create REPO_NAME --public --source=. --remote=origin --push
```

## Customize

Edit `index.html` and `styles.css` in each folder. Point the **Get in touch** link (`href`) to mail, a form, or your main site.
