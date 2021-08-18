#Отчёт о тестировании "Precision"

##Краткое описание

18.08.2021 - 18.08.2021 было проведено модульное, регрессионное тестирование приложения "Precision".

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

- [Неверный расчет переменной totalBonus](https://github.com/Ksuschka/Precision/issues/1)

##Описание процесса тестирования

В качестве тестовых данных использовался предоставленный программистами код:

```public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```
Ожидаемый результат: 
```"C:\Program Files\Eclipse Foundation\jdk-11.0.12.7-hotspot\bin\java.exe" -javaagent:C:\Users\anisimova.om\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\212.4746.92\lib\idea_rt.jar=49910:C:\Users\anisimova.om\AppData\Local\JetBrains\Toolbox\apps\IDEA-C\ch-0\212.4746.92\bin -Dfile.encoding=UTF-8 -classpath D:\Precision\out\production\Precision Main
0.9

Process finished with exit code 0
```

Тестирование производилось в следующем окружении:

Windows 7 (64 бит)

Java version 11.0.12+7 (64 бит)

IntelliJ IDEA Community Edition