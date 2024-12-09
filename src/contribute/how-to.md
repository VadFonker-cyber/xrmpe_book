# Помощь книжке

___

## Первый способ помочь книжке

Вы можете отредактировать книжку, нажав справа по значку с ручкой.

![suggest an edit centered](../images/suggest-an-edit.png#center)

___

## Второй способ помочь книжке

Эта книга была написана с использованием [mdBook](https://github.com/rust-lang/mdBook). Чтобы помочь книге, вам нужны следующие вещи:

1. [mdBook](https://github.com/rust-lang/mdBook)
2. [git](https://gitforwindows.org/)
3. [GitHub](https://github.com/) аккаунт
4. (Или как вариант) [VSCodium](https://vscodium.com/)

Реккомендуется использовать VSCodium или VSCode, но можно и NotePad++ или даже Блокнот.

*__Теперь нужно установить VSCode и Git__*.

## Создание форка от репозитория

Содействие по книжке производится через систему пулл реквестов ("Pull Request") workflow. Это означает, что для изменения книги, необохдимо что ваш PR одобрили мейнтейнеры репозитория.

Здесь описаны шаги для создания пулл реквеста:

1. Скопируйте (сделав "fork") репозиторий
2. Скачайте свою копию репозитория
3. Добавьте какие-либо изменения в репозиторий
4. Залейте свои правки на свой репозиторий
5. Создайте пулл реквест ("Pull request") в вашем репозитории, сделав ссылку на основной (target)

Чтож, надеюсь не сложно.

### Копирование (Создание Forkа)

1. Идите в [основной репозиторий](https://github.com/VadFonker-cyber/xrmpe_book)
2. Нажмите кнопку Fork

    ![centered](../images/fork.png#center)

3. Создайте Fork проекта

    ![centered](../images/create-fork.png#center)

4. У вас появилась копия проекта

#### Скачивание своего репозитория

1. Откройте/Создайте папку в VSCodium, в которую вы скачаете репозиторий.

    ![centered](../images/folder-download.png#center)

2. Откройте сессию в PowerShell или GitBash
3. Скопируйте ссылку на репозиторий.

    ![centered](../images/https-git.png#center)

4. Вызовите команду на вашем компьютере, вставив ссылку вместо LINK.

    ```git
    git clone LINK
    ```

#### Запуск локальной копии

Запустите `start.bat`. Если книга не открылась сама, откройте [localhost:3000](localhost:3000) в вашем браузере.
Если вы используете любой дистрибутив Linuxa, вам нужно использовать другие бинарные файлы из [репозитория mdBook](https://github.com/rust-lang/mdBook/releases)

#### Загрузка изменений на репозиторий

1. Подготовьте систему контроля версий (Git), [гайд](https://docs.github.com/ru/get-started/getting-started-with-git/set-up-git)

2. Добавьте изменения в отслеживаемые в разделе Git VSCodium. Откройте вкладку с Gitом, наведитесь над линией "Changes" и нажмите "+".

    ![centered](../images/git-add.png#center)

3. Добавьте коментарий и нажмите "✔" чтобы зафиксировать ("commit") изменения

    ![centered](../images/git-commit.png#center)

4. После этого у вас появится возможнорсть опубликовать изменения

    ![centered](../images/git-push.png#center)

## Создание пулл реквеста

1. В основном репозитории, откройте вкладку "Pull Requests" и нажмите "New pull request"

    ![centered](../images/github-pull-request.png#center)

2. Нажмите "compare across forks". Выберите репозиторий и нажмите "Create pull request".

3. Ждите аппрува от стороны команды книжки.

4. Готово. Ваши изменения теперь находятся в общей книге.

___

### P.S

Если вы будете использовать VSCodium или VSCode, реккомендуется использовать расширения под Markdown чтобы соотвествовать общему стилю.

Например:

- [Markdown Link Updater](https://open-vsx.org/extension/mathiassoeholm/markdown-link-updater) - Автоматически обновляет ссылки в Markdown документе, если они были обновлены.
- [markdownlint](https://open-vsx.org/extension/DavidAnson/vscode-markdownlint) - Позволяет привести документы к общему стилю Markdown документов.
