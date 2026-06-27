# Setup

This folder is for the special GitHub profile repository:

```text
srohitsuryaa21/srohitsuryaa21
```

GitHub displays `README.md` from that exact repository on the profile page.

## Steps

1. Create a public GitHub repository named exactly:

```text
srohitsuryaa21
```

2. Upload these files to that repository:

```text
README.md
.github/workflows/snake.yml
```

3. After the first push, open the repository Actions tab and run:

```text
Generate contribution snake
```

4. The workflow creates an `output` branch with the animated SVG files used by the README.

## Optional

If you authenticate GitHub CLI locally:

```powershell
gh auth login
```

Then this can be pushed automatically from the command line.
