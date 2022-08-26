# Enlighten Open Api documentation

## Install Packages

```bash
npm install @redocly/cli -g

npm install -g redoc-cli
```

## Run preview

```bash
redocly preview-docs full_doc.yaml
```

## Create index.html

```bash
redoc-cli build -o index.html full_doc.yaml
```