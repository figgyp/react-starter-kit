# React Starter Kit

### Technologies
- Typescript
- React
- Tailwind
- Vite
- ESLint
- Prettier

### Opinions
- env files in `/config` directory
- src directory gets `@/` import alias
- node strict engine check
- npm install exact dependencies

### Omitted
- routing
- CI/CD
- src directory structure

### Getting started

tl-dr; use this repo as the `Repository template` for your new project

From the web
- Visit https://github.com/figgyp/react-starter-kit
- On the top right, click the green button `Use this template`

From CLI
- Prereq: Ensure you have the [GitHub CLI](https://github.com/cli/cli) installed and authenticated with your GitHub account
- `gh repo create <new-repository-name> --template figgyp/react-starter-kit --clone --public`

Example:
```sh
 gh repo create foobar --template figgyp/react-starter-kit --clone --public                                                            (📦 v0.0.1)( v22.12.0)  11s
 ✓ Created repository figgyp/foobar on github.com
  https://github.com/figgyp/foobar
```
