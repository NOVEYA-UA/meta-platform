# Meta Platform Starter

Це базова структура репозиторію для проекту **UA‑NOVEYA Meta‑Platform**.

До неї входять мінімальні файли конфігурації CI/CD, шаблони завдань та інструкції,
щоб ви могли швидко розпочати розробку та публікацію матеріалів.

* `.github/workflows/markdown-lint.yml` - перевірка Markdown на відповідність стандартам.
* `.github/workflows/build-pdf.yml` — складання PDF-файлів з Markdown документів у папці `docs/`.
* `.github/workflows/notify.yml` — надсилання повідомлень у Discord/Teams про статус складання (використовує secrets).
* `scripts/compute_sha256.sh` - обчислення контрольних сум SHA-256 для файлів.
* `config/github_labels.yml` - набір базових міток для GitHub Issues.

Ви можете розширювати цей шаблон під ваші потреби.

# Meta Platform Starter

Это базовая структура репозитория для проекта **UA‑NOVEYA Meta‑Platform**. 

В неё входят минимальные файлы конфигурации CI/CD, шаблоны задач и инструкции, 
чтобы вы могли быстро начать разработку и публикацию материалов.  

* `.github/workflows/markdown-lint.yml` — проверка Markdown на соответствие стандардам.  
* `.github/workflows/build-pdf.yml` — сборка PDF-файлов из Markdown документов в папке `docs/`.  
* `.github/workflows/notify.yml` — отправка уведомлений в Discord/Teams о статусе сборки (использует secrets).  
* `scripts/compute_sha256.sh` — вычисление контрольных сумм SHA-256 для файлов.  
* `config/github_labels.yml` — набор базовых меток для GitHub Issues.  

Вы можете расширять этот шаблон под свои нужды.
