# Oyester-DevOps

Existing Node/Express starter (`src/`, `package.json`, ESLint + Prettier) is kept as-is.
DevOps study tracks live alongside it:

- [linux/](./linux/) — commands, permissions, systemd, disks
- [bash/](./bash/) — scripting (`bash bash/example.sh`)
- [docker/](./docker/) — `Dockerfile.example` (multi-stage-ready Node)
- [docker-compose/](./docker-compose/) — `docker-compose.yml` (`docker compose config`)
- [github-actions/](./github-actions/) — `ci.yml` (copy to `.github/workflows/ci.yml`)
- [nginx/](./nginx/) — `nginx.conf` reverse proxy to `:3000`
- [networking/](./networking/) — DNS/TCP/HTTP/TLS, `ss`/`dig`/`curl`
- [kubernetes/](./kubernetes/) — `deployment.yaml` + Service
- [helm/](./helm/) — minimal chart (`Chart.yaml` + `values.yaml`)

## Dev

```bash
npm install
npm run lint
npm run format:check
npm run dev
```
