# ALKAstraverse.github.io

Portfolio của Nguyễn Quang Huy — copy từ `alkcv.pages.dev`.

- Live: https://huynguyen.is-a.dev (CNAME -> `alkastraverse.github.io`)
- Template gốc: Dimension by HTML5 UP (CCA 3.0)
- Deploy: GitHub Pages (branch `main` / root)

## Cấu trúc
```
index.html
CNAME  -> huynguyen.is-a.dev
.nojekyll
assets/css, assets/js, assets/webfonts
images/
```

## Deploy
```bash
git remote add origin https://github.com/ALKAstraverse/ALKAstraverse.github.io.git
git branch -M main
git add .
git commit -m "Copy alkcv.pages.dev to GitHub Pages"
git push -u origin main --force
```
Sau đó vào Settings > Pages > Custom domain = `huynguyen.is-a.dev` > Enforce HTTPS.

Domain `huynguyen.is-a.dev` đã đăng ký xong (is-a-dev/register `domains/huynguyen.json` -> CNAME `alkastraverse.github.io`), DNS đã trỏ đúng, không cần sửa thêm.
