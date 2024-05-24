# tz3
## Описание продукта 
Я выполнила построение 5 UML диаграмм для сервиса по доставке еды Rush Delivery (вымышленное название). Главная функция сервиса — обеспечение взаимодействия пользователя с несколькими ресторанами, которые сотрудничают с сервисом.  Этот сервис предусматривает создание аккаунта для пользователя, чтобы можно было сохранить его данные и не вводить их при каждом заказе. Пользователь может заказывать еду сразу из нескольких ресторанов, заказ из которых в дальнейшем заберет и доставит до выбранного адреса курьер. В основном сервис отвечает за логистические договоренности между пользователями, ресторанами и курьерами, контролирует этот процесс. Сервис предлагает два варианта оплаты: картой во время оформления заказа или наличными при получении заказа.    
Пользовательский сценарий таков: клиент открывает приложение, фильтрует интересующие его позиции в соответствии со своими предпочтениями, а затем переходит в корзину, вводит (или выбирает нужные, если это не его первый заказ) данные об адресе и способе оплаты, сервис производит проверку оплаты в случае онлайн-оплаты, предварительно проверив наличие интересующих пользователя позиций. После этого заказ передается на кухни соответствующих ресторанов, где производится приготовление заказов. Пользователю отправляется уведомление о начале процесса готовки. После окончания приготовления к ресторану подъезжает курьер, тому передается заказ, пользователю высылается уведомление о передаче в доставку его заказа. После получения сервис может выдать купон при задержке доставки, а также принять фидбэк о качестве обслуживания.   
## Диаграмма вариантов использования
![Image alt](https://github.com/Daryakeke/tz3/raw/main/use_cases_diagram.png)
\
\
## Диаграмма последовательности для процесса заказа еды через приложение
![Image alt](https://github.com/Daryakeke/tz3/raw/main/sequence_diagram.png)
\
\
## Диаграмма состояний для заказа \
![Image alt](https://github.com/Daryakeke/tz3/raw/main/state_diagram.png)
\
\
## Диаграмма деятельности для описания процесса обработки заказа системой
![Image alt](https://github.com/Daryakeke/tz3/raw/main/activity_diagram.png)
\
\
## Диаграмма классов для системы.
![Image alt](https://github.com/Daryakeke/tz3/raw/main/classes_diagram.png)
