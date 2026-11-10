# Day 3: Containerized Infrastructure

## Morning: Intermediate Git & GitHub

* 9:00 – 10:30 AM — Code Drift Prevention
  * Branches and how they work.
  * Synchronizing local forks with multiple active upstream repositories (`git fetch upstream`, `git merge upstream/master`, `git pull --rebase`).
* 10:30 AM – 12:00 PM — Conflict Resolution
  * Resolving Git merge conflicts without deleting and re-cloning a repository.

## Lunch: 12 - 1pm

## Afternoon: Containers & Services

dev containers / docker -- installing IRDM and UV locally

* Afternoon: Dev Containers & Docker for InvenioRDM
  * Containerized Architecture: Understanding multi-service web architecture in Docker (Flask application, PostgreSQL database, OpenSearch, Redis cache).
  * Local Setup Execution: Running `invenio-cli install`, `invenio-cli services setup`, and `invenio-cli run` for local development versus containerized preview modes.
  * Modern Toolchain Integration: Overview of InvenioRDM v14 build tooling, including `uv` for Python, `pnpm` for JavaScript, and `Rspack` for fast asset bundling.

* 1:00 – 2:00 PM — Multi-Service Container Architecture
  * Understanding InvenioRDM containerization architecture in Docker: Flask application server, PostgreSQL relational database, OpenSearch indexing node, and Redis key-value cache.
* 2:00 – 3:15 PM — InvenioRDM Local Build & Execution
  * Executing `invenio-cli install` (Python/JS dependencies), `invenio-cli services setup` (Docker backend initialization), and `invenio-cli run` (local Flask development server).
  * Navigating local instance verification (`https://127.0.0.1:5000`) and handling self-signed SSL certificates (`thisisunsafe`).
* 3:00 - 3:30 — Coffee/tea break.
* 3:15 – 4:00 PM — Modern Frontend Asset Pipeline
  * Exploring InvenioRDM v14 frontend infrastructure upgrades: fast Rust-based asset bundling via `Rspack`, JS package management via `pnpm`, and custom UI component overriding.
