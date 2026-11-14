# Phobos Planner service

Hosting copy of the planner web service from the Phobos Phantoms OG 7.66 project (NASA Space Apps Challenge 2026). Source of truth: the project repository (pipeline/, contracts/, terrain/out/); this copy is made by pipeline/render/make_render.ps1.

Render: build `pip install -r requirements.txt`, start `uvicorn pipeline.api:app --host 0.0.0.0 --port $PORT`, env PYTHON_VERSION=3.12.7 and CORS_ALLOW_ORIGINS.
