# Setup Guide

## 1. Create the special GitHub profile repository

Create a **public** repository named exactly:

```text
Wethmal
```

Because your GitHub username is `Wethmal`, a repository named `Wethmal/Wethmal` becomes your profile README repository.

## 2. Upload this package

Upload these items to the repository root:

```text
README.md
assets/
.github/workflows/snake.yml
```

Commit the files to the `main` branch.

## 3. Enable the snake workflow

Open the repository's **Actions** tab and run **Generate Contribution Snake** manually once. The workflow also refreshes automatically every 12 hours.

In **Settings → Actions → General → Workflow permissions**, select:

```text
Read and write permissions
```

Then save the setting and run the workflow again if the output branch was not created.

## 4. Check your links

The README currently uses:

- GitHub: `https://github.com/Wethmal`
- Portfolio: `https://www.kisanduwethmal.me/`
- LinkedIn: `https://www.linkedin.com/in/kisandu-wethmal-9ba67633b/`
- Email: `kisanduofficially@gmail.com`

## 5. Recommended repository settings

- Keep the profile repository public.
- Pin your five strongest project repositories.
- Add project screenshots and clear project READMEs.
- Enable private contribution visibility from profile settings if appropriate.

## Notes

- GitHub does not allow arbitrary CSS directly inside a profile README. The glass, 3D and animation effects are implemented through SVG artwork, supported Markdown/HTML and dynamic cards.
- Some statistics cards depend on third-party public services. The main profile content and custom SVG artwork remain functional if one of those services is temporarily unavailable.
