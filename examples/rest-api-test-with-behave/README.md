<https://testmanager.tistory.com/332>

# run tests

```sh
$ poetry install 
$ poetry run behave
```

# allure

```sh
$ brew install allure
```

generate and view reporsts

```sh
$ pip install allure-behave
$ behave -f allure_behave.formatter:AllureFormatter -o $RESULT_FOLDER ./features
$ allure serve $RESULT_FOLDER
```