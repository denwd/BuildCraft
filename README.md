## Welcome to Buildcraft-MCPC on GitHub

### Compiling and packaging Buildcraft
1. Ensure that `Apache Ant` (found [here](http://ant.apache.org/)) is installed correctly on your system.
 * Linux users will need the latest version of astyle installed as well.
1. Create a base directory for the build
1. Clone the Buildcraft repository into `basedir/BuildCraft/`
1. Copy the minecraft bin dir and minecraft_server.jar into `basedir/jars/`
1. Copy the latest MCPC+ build into basedir\BuildCraft\build\forge\mcp\lib (can found here: http://ci.md-5.net/job/MCPC-Plus-Legacy/)
1. Navigate to basedir/Buildcraft in a shell and run `ant` (this will take 2-5 minutes)
1. The compiled and obfuscated jar will be in basedir/build/dist

Your directory structure should look like this:
***

    basedir
    \- jars
     |- minecraft_server.jar
     \- bin
      |- minecraft.jar
      |- ...
    \- BuildCraft
     |- buildcraft_resources
     |- common
     |- ...

***

### Для русскоговорящих пользователей

Это НЕОФИЦИАЛЬНЫЙ репозиторий BuildCraft с bukkit events, призванный исправить некоторые ошибки, допущенные в оригинальном релизе.
Так же в этот репозиторий вносятся исправления от новых версий BuildCraft.

### Компиляция мода
1. Убедитесь что `Apache Ant` ([получить его можно здесь](http://ant.apache.org/)) корректно установлен в вашу систему.
 * Пользователи Unix систем должны установить astyle.
1. Создайте базовую директорию (в примере это basedir)
1. Скопируйте этот репозиторий в `basedir/BuildCraft/`
1. Скопируйте папки bin and minecraft_server.jar в `basedir/jars/`
1. Скопируйте последний билд MCPC+ в basedir\BuildCraft\build\forge\mcp\lib ([получить его можно здесь](http://ci.md-5.net/job/MCPC-Plus-Legacy/))
1. Перейдите в директорию basedir/BuildCraft/ при помощи команды cd и запустите компиляцию командой ant
1. Скомпилированный и обфусцированный jar файл будет находится в basedir/build/dist

Структура вашей директории должна иметь такой вид:
***

    basedir
    \- jars
     |- minecraft_server.jar
     \- bin
      |- minecraft.jar
      |- ...
    \- BuildCraft
     |- buildcraft_resources
     |- common
     |- ...

***
