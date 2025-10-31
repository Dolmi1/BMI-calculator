# BMI-calculator

## Vendored submodule

This repository includes the Official Joke API as a git submodule at `vendor/official_joke_api`.

To initialize or update the submodule after cloning this repo, run:

```bash
git submodule update --init --recursive
```

To pull upstream changes in the submodule:

```bash
cd vendor/official_joke_api
git pull origin main
cd ../..
git add vendor/official_joke_api
git commit -m "Update official_joke_api submodule"
```

This keeps the external API code tracked while keeping the main project separate.