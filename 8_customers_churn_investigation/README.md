# Прогнозирование оттока клиентов отеля
## Данные
В наличии были следующие данные о бронированиях в отеле:
* id — номер записи
* adults — количество взрослых постояльцев
* arrival_date_year — год заезда
* arrival_date_month — месяц заезда
* arrival_date_week_number — неделя заезда
* arrival_date_day_of_month — день заезда
* babies — количество младенцев
* booking_changes — количество изменений параметров заказа
* children — количество детей от 3 до 14 лет
* country — гражданство постояльца
* customer_type — тип заказчика
* days_in_waiting_list — сколько дней заказ ожидал подтверждения
* distribution_channel — канал дистрибуции заказа
* is_repeated_guest — признак того, что гость бронирует номер второй раз
* lead_time — количество дней между датой бронирования и датой прибытия
* meal — опции заказа
* previous_bookings_not_canceled — количество подтверждённых заказов у клиента
* previous_cancellations — количество отменённых заказов у клиента
* required_car_parking_spaces — необходимость места для автомобиля
* reserved_room_type — тип забронированной комнаты
* stays_in_weekend_nights — количество ночей в выходные дни
* stays_in_week_nights — количество ночей в будние дни
* total_nights — общее количество ночей
* total_of_special_requests — количество специальных отметок
* is_canceled — отмена заказа
## Задача
На основе данных спрогнозировать кто из клиентов откажется от брони и оценить возможную прибыль от внедрения модели.
## Используемые библиотеки
*pandas matplotlib seaborn sklearn*
