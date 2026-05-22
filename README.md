# DevOps bootcamp (GitLab.com + macOS)

Навчальний репозиторій: GitLab CI/CD, Docker, Kubernetes — з нуля.

**Проєкт на GitLab:** `liana-group/liana-project`  
**SSH remote:** `git@gitlab.com:liana-group/liana-project.git`

## Що вже зроблено в цьому старті (Дні 1–5)

- Базовий `.gitlab-ci.yml`: stages, jobs на `alpine`, артефакт `build/build-info.txt`.
- Різна поведінка пайплайна для **Merge Request** і для гілки **`main`**.
- Скрипт `scripts/hello.sh`, який запускається в CI.
- Шаблон MR: `.gitlab/merge_request_templates/Default.md`.
- test

## Швидкий старт (якщо клонуєш на нову машину)

```bash
git clone git@gitlab.com:liana-group/liana-project.git
cd liana-project
```

## Як перевіряти локально (без GitLab)

```bash
sh scripts/hello.sh
```

## Наступні кроки навчання

Після зеленого пайплайну на `main` переходь до **Дня 6** плану: CI/CD Variables, cache, `needs:` — див. `docs/plan-60-days.md`.
