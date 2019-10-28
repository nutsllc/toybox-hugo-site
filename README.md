# Toybox Hugo Site

## Getting Start

### STEP1: Clone this repository

```bash
$ git clone https://github.com/nutsllc/toybox-hugo-site.git
```

### STEP2: Copy .env file

Choose theme you want use your hugo site from ``themes/`` directory and then copy .env.* file into ``bin/`` directory.

When do it so, file name should be changed to ``.env`` 

```bash
$ cp themes/.env.hugo-theme-learn bin/.env
```

### STEP3: Run init script

```bash
sh bin/init
```

``site/`` directory that contains all of resources for your hugo site will be created after running ``bin/init`` script.

### Step4: Start Hugo server

```bash
cd site
docker-compose up -d
```

Open ``localhost:1313`` from your web browser.

enjyoy :-)

## Create New document

### Create new section
```bash
cd site
sh bin/section <section name>
```

### Create content
```bash
sh bin/post <section name>/<post name>.md
```

