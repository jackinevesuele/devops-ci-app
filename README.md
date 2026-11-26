# devops-ci-app

Учебное Flask-приложение Босарева Евгения, ЭФБО-11-24, практическая работа №10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.
Публикация выполняется только из `main`. В PR выполняются проверки без push.

- health: `/health`;
- образ: `ghcr.io/jackinevesuele/devops-ci-app`;
- workflow: `.github/workflows/ci.yml`.
