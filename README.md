### Initialize Git Repo

```bash
git init
```

### Install SASS

```bash
npm install -D sass
```

### Setup JSON Package

---

**ADD SCRIPT TO WATCH SASS**

    "scripts": {
    	"sass": "sass --watch ./app/sass/styles.scss:dist/styles.css"
    },

---

### Watch SASS

```bash
npm run sass
```