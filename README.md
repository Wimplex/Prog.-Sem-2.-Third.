_Логунов Алексей, группа Р3175.
Университет ИТМО.
Февраль 2017 г._

Программа проверяет на столкновение два полигона.
Каждый полигон задается вектором - центром полигона, и списком векторов - вершинами в локальных координатах. 
Причем вершины перечисляются в списке по часовой стрелке - слева направо и сверху вниз.

    Локальные координаты - координаты в локальной системе отсчета (от центра каждого полигона).  
    * Центр полигона находится на точке (10, 10).
    * Вершина полигона в локальной точке (10, 10).
    * В абсолютных координатах значение вершины будет (20, 20)

В основе программе лежит реализация теоремы о разделяющей оси (ТРО).
Ссылка на подробное ее описание: <http://noregret.org/tutor/n/collision/>

В программе испольхуются такие характерные черты языка Python, как _декораторы_ и _генераторы_.
