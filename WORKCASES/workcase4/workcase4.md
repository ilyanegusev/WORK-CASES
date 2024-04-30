# WORKCASE #4
**Дисципліна:** Операційні системи \
**Виконав:** студент КФКЗ групи БІКС-13 *Негусєв І.В.*

## 1. Пакети та репозиторії
**Пакет** — це архів, який містить в собі програмне забезпечення та інструменти для інсталяції певної програми.\
**Репозиторій** – це сховище програмного забезпечення, де зберігаються пакети для інсталяції певних програм та інформація про них.
**Менеджер пакетів** — це менеджер, який реалізує пошук та керування пакетами та репозиторіями на певних дистрибутивах Linux.
Кожен дистрибутив Linux має свій власний пакетний менеджер. Ось декілька з найпопулярніших:
1) APT (Advanced Package Tool): Використовується в Debian, Ubuntu та їхніх похідних дистрибутивах. Забезпечує швидке встановлення, оновлення та видалення пакетів, а також керування залежностями.
2) YUM (Yellowdog Updater Modified): Використовується в CentOS, Fedora та інших дистрибутивах, що базуються на Red Hat. Також забезпечує управління пакетами та їх залежностями.
3) DNF (Dandified YUM): Нова версія YUM, яка надає кращу продуктивність та додаткові функції.
4) Pacman: Використовується в Arch Linux та його похідних. Це простий та швидкий менеджер пакетів з простою схемою керування пакетами.
5) ZYpp (ZENworks YUM Package Manager): Використовується в openSUSE та SUSE Linux Enterprise. Надає схожий інтерфейс до YUM, але з іншою реалізацією.

## 2. Менеджер пакетів. Основні команди
Один із найпопулярніших, дистрибутив Ubuntu, похідний від Debian, використовує пакетний менеджер Advanced Package Tool (APT) — доволі швидкий і простий в використанні.\
Давайте розглянемо основні команди пакетного менеджера APT (команди, що стосуються встановлення, видалення та оновлення пакетів треба виконувати в режимі адміністратора):

1) Пошук пакетів:
   
   *apt-cache search <ім'я пакету>*
   
   ![Пошук пакетів](https://github.com/ilyanegusev/WORKCASES/blob/main/WORKCASES/workcase4/assets/workcase4_screen3.jpg)

2) Інсталяція пакетів:

   *apt-get install <ім'я пакету>*

   ![Інсталяція пакетів](https://github.com/ilyanegusev/WORKCASES/blob/main/WORKCASES/workcase4/assets/workcase4_screen5.jpg)

3) Інсталяція пакетів з сторонніх репозиторіїв:

   *add-apt-repository <ім'я репозиторія>*\
   *apt-get upgrade*\
   *apt-get install <ім'я пакету>*

   ![Пошук пакетів](https://github.com/ilyanegusev/WORKCASES/blob/main/WORKCASES/workcase4/assets/workcase4_screen6.jpg)

4) Перегляд інформації пакетів:

   *apt-cache policy <ім'я пакету>*

   ![Перегляд інформації пакетів](https://github.com/ilyanegusev/WORKCASES/blob/main/WORKCASES/workcase4/assets/workcase4_screen4.jpg)

5) Видалення пакетів:

   *apt-get remove <ім'я пакету>*

   ![Видалення пакетів](https://github.com/ilyanegusev/WORKCASES/blob/main/WORKCASES/workcase4/assets/workcase4_screen2.jpg)

6) Оновлення пакетів

   *apt-get upgrade*

   ![Пошук пакетів](https://github.com/ilyanegusev/WORKCASES/blob/main/WORKCASES/workcase4/assets/workcase4_screen1.jpg)
