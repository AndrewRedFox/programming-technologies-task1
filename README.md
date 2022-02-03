# Шаблон репозитория для курсов по программированию

## Инструкция
1. Сделайте [fork](https://github.com/DaniilStepanov/programming-technologies-task1) репозитория
2. Используйте этот репозиторий в процессе работы над своей задачей. Весь код и необходимые артефакты
должны быть в репозитории на момент сдачи. **Обязательное условие**: ваше решение должно содержать тесты,
которые должны **успешно проходить**.
   * Перед сдачей своего решения убедитесь, что при запуске команды `./gradlew test`
   * в папке `build/test-results/test` генерируется xml файл с отчетом о выполненных тестах. 
   * Пример успешного выполнения команды `./gradlew build`:
   ```shell
   BUILD SUCCESSFUL in 7s
   7 actionable tasks: 7 executed
   ```
   В той же директории, в которой у вас находится файл `build.gradle` (или `build.gradle.kts`), должна появиться директория `build`.
   В результате выполнения команды `./gradlew build` должен сгенерироваться файл с именем `build/test-results/test/TEST-myapp.test.Test.xml`,
   где `myapp.test.Test` -- имя вашего тестового класса. Если тестовых классов несколько, то для каждого из них генерируется отдельный отчет.
3. Чтобы сдать задание откройте [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
    * В качестве `base repository` выберите этот (базовый) репозиторий. В качестве ветки `base` выберите ветку `main`
    * В качестве `head repository` выберите ваш репозиторий (fork). В качестве ветки `compare` выберите ветку 'main'
    * В заголовке PR укажите ваше имя, название задания, и номер группы
      * например, "Иванов И.И., 'Шашки рэндзю', гр. 3530901/00006" 