# Install and run ChatWoot

## Step 1
```bash
git clone https://github.com/mhdhaidarah/ChatWoot.git
cd ChatWoot/
```
## Step 2
```bash
docker compose up -d
```

## Step 3
```bash
docker compose run --rm rails bundle exec rails db:chatwoot_prepare
```
## Step 4
```bash
docker compose run --rm rails bundle exec rails chatwoot:setup
```
