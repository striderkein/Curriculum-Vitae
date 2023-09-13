# striderkein's resume

## Data

- GitHub Pages
  - [ja](https://striderkein.github.io/Curriculum-Vitae)
  - [en](https://striderkein.github.io/Curriculum-Vitae/en)
- PDF
  - [ja](https://github.com/striderkein/Curriculum-Vitae/releases/latest/download/Curriculum-Vitae.pdf)
  - [en](https://github.com/striderkein/Curriculum-Vitae/releases/latest/download/Curriculum-Vitae-en.pdf)
- File
  - [ja](https://github.com/striderkein/Curriculum-Vitae/blob/master/docs/README.md)
  - [en](https://github.com/striderkein/Curriculum-Vitae/blob/master/docs/en/README.md)

## Features

### 💅 Lint text

Automatic proofreading with [textlint](https://github.com/textlint/textlint).

```node
npm run lint --fix
```

It is also automatically executed when pre-commit by [husky](https://github.com/typicode/husky).  
proofreading rules are set with `.textlintrc`.

### 📝 Convert MD to PDF

You can generate PDF with [md-to-pdf](https://www.npmjs.com/package/md-to-pdf).

```node
npm run build:pdf
```

The output PDF can be styled as you like with CSS. Edit the `pdf-configs/style.css`.  

### 📆 Remind update

Automatically generate issues every three months with GitHub Actions Schedules triggers to prompt you to update your resume.

To change the duration or stop the job, edit `.github/workflows/create-issue.yml`.  
To change the issue contents, edit `.github/ISSUE_TEMPLATE.md`.
