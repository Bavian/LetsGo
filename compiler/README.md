## Установка компилятора

Для разработки нужно установить компилятор Go.

Для этого можно перейти на [golang.org](https://golang.org/doc/install) и следовать инструкции.

В репозитории Ubuntu есть пакет `golang`.
Поэтому на этой системе и производных Go можно установить с помощью команды:

```bash
sudo apt-get install golang
```

## Компиляция

Рассмотрим компиляцию на примере классики [Hello, World!](hello_world.go):

Для компиляции единственного исходного файла `hello_world.go` необходимо выполнить команду:

```bash
go build hello_world.go
```

А затем запустить:

```bash
./hello_world
```

