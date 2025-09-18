# ML-Pipeline
ml-mysql-pipeline/
├─ .github/
│  └─ workflows/ci.yml
├─ .gitignore
├─ config_example.env
├─ requirements.txt
├─ Dockerfile
├─ README.md
├─ artifacts/                     # saved models/metrics (git-ignored)
├─ src/
│  ├─ __init__.py
│  ├─ db.py
│  ├─ data.py
│  ├─ features.py
│  ├─ train.py
│  ├─ predict.py
│  └─ utils.py
└─ tests/
   └─ test_pipeline_smoke.py
