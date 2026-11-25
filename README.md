# devops-docs

Практическая работа № 9. Команды локальной проверки

    python -m pip install -r requirements-dev.txt
    python -m pylint src/status.py --score=no
    python -m mkdocs build --strict --site-dir site

В репозитории GitHub выберите Pages → Source → GitHub Actions.
После первого успешного CI создайте правило protect-main и потребуйте
Pull Request и проверку pylint. Опубликованный артефакт берётся из site/.
