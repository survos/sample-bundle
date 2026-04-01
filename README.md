# sampleBundle

Symfony Bundle that provides some tools for interacting with Assamplema (assamplema.org)

```bash
composer req survos/sample-bundle
```

```bash
symfony new sample-demo --webapp --version=next && cd sample-demo
echo "DATABASE_URL=sqlite:///%kernel.project_dir%/var/data.db" > .env.local

