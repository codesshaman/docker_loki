# Docker grafana on alpine

Grafana build in Alpine 3.16

## Install

### Step 1: Build configuration

Install make in your host machine.

Build configuraion with command ``make build``.

## Step 2: Configure and manage

Use ``make help`` for display all supported commands.

## Step 3: Install 

```
docker run -d --name=grafana -p 3000:3000 grafana/grafana
```
