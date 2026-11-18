<img src="https://raw.githubusercontent.com/osnova-kit/osnova_backend/main/.github/logo.svg" alt="" width="72" height="72">

# Osnova

**The full-stack template that grows with your project.**

From a simple site to several replicas, on FastAPI and React. Remove what you don't need.

## Repositories

| Repository | Purpose |
|---|---|
| [**osnova_backend**](https://github.com/osnova-kit/osnova_backend) | API, data and infrastructure. **Start here** |
| [**osnova_frontend**](https://github.com/osnova-kit/osnova_frontend) | Web interface |

## Quick start

Requirements: Docker with the Compose plugin, `git`, `make`, `python3`.

```bash
git clone https://github.com/osnova-kit/osnova_backend.git
git clone https://github.com/osnova-kit/osnova_frontend.git
cd osnova_backend
make init
make up-standard
make createroot
```

Open `http://localhost:8080`, sign in, and the admin is at `/admin`.

## Documentation

- [Backend documentation](https://github.com/osnova-kit/osnova_backend/blob/main/DOCUMENTATION.md): profiles, modules, configuration, deployment
- [Frontend documentation](https://github.com/osnova-kit/osnova_frontend/blob/mai
