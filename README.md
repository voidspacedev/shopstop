# ---------- Environment / secrets ----------

.env
.env._
!.env.example
!.env.sample
_.pem
\*.key

# ---------- Python ----------

**pycache**/
_.py[cod]
_$py.class
_.so
.Python
build/
dist/
develop-eggs/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
share/python-wheels/
_.egg-info/
.installed.cfg
\*.egg
MANIFEST

# Virtual environments

venv/
.venv/
env/
ENV/
env.bak/
venv.bak/

# Test / coverage / type-check caches

.pytest*cache/
.tox/
.nox/
.coverage
.coverage.*
htmlcov/
coverage.xml
\_.cover
.hypothesis/
.mypy_cache/
.dmypy.json
.pyre/
.pytype/
.ruff_cache/

# Jupyter

.ipynb_checkpoints/

# Misc Python tooling

pip-log.txt
pip-delete-this-directory.txt
.python-version
celerybeat-schedule
celerybeat.pid

# ---------- Node ----------

node*modules/
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*
lerna-debug.log*
.pnpm-store/
.yarn/*
!.yarn/patches
!.yarn/plugins
!.yarn/releases
!.yarn/versions
.pnp.*
.npm/
.eslintcache
.stylelintcache
\_.tsbuildinfo
.node_repl_history
\*.tgz

# Framework / build output

.next/
.nuxt/
.svelte-kit/
.turbo/
.parcel-cache/
.cache/
out/
coverage/
.nyc_output/

# ---------- VS Code ----------

.vscode/_
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json
!.vscode/_.code-snippets
_.code-workspace
.history/
_.vsix

# ---------- OS / editor junk ----------

.DS*Store
Thumbs.db
Desktop.ini
*.swp
\_.swo
\*~

# ---------- Logs ----------

\*.log
logs/
