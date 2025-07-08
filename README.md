<h1 align="center" style="font-weight: bold; font-size:2.5rem;">ppt-generator: Team collaboration guide</h1>
<div align="center">

</div>

<p align="center">
 <a href="#started">Getting Started</a>  •
 <a href="#branching">Branching rules</a>  •
 <a href="#workflow">Development Workflow</a> 
</p>

<h2 id="started">🚀 Getting started</h2>

<h3>Clone the repository</h3>

```bash
git clone https://github.com/goldenAge-Interns/ppt-generator.git

cd ppt-generator
```

<h2 id="branching">📍 Branching Rules</h2>

| Branch Type        | Naming Convention    | Example               |
| ------------------ | -------------------- | --------------------- |
| <kbd>Main</kbd>    | `main`               | Production-ready code |
| <kbd>Develop</kbd> | `develop`            | Integration branch    |
| <kbd>Feature</kbd> | `feat/[description]` | `feat/user-auth`      |
| <kbd>Bugfix</kbd>  | `fix/[description]`  | `fix/login-error`     |
| <kbd>doc</kbd>     | `doc/[description]`  | `doc/edited-readme`   |

<h2 id="workflow">📍 Development Workflow</h2>
<p style='font-size:1.2rem;font-weight:700;'>
    1, Always start from <i><u>develop</u></i> :
</p>

```bash
git checkout develop
git pull origin develop
```

<p style='font-size:1.2rem;font-weight:700;'>
    2, create a new branch :
</p>

```bash
git checkout -b feat/your-feature
```

<p style='font-size:1.2rem;font-weight:700;'>
    3, Commit messages, use conventional commits:
</p>

```bash
git commit -m "feat: add user login endpoint"
git commit -m "fix: resolve null pointer in auth"
```

<p style='font-size:1.2rem;font-weight:700;'>
    4, push to remote:
</p>

```bash
git push -u origin feat/your-feature
```

<p style='font-size:1.2rem;font-weight:700;'>
    5, open a pull request:
</p>

```bash
-> target: develop

-> describe changes
```

<p style='font-size:1.2rem;font-weight:700;'>
    6, After approval:
</p>

```bash

-> squash and merge

-> delete branch
```

