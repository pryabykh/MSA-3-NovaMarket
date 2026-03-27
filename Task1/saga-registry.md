| Этап | Тип события | Название |
| :--- | :--- | :--- |
| Инициализация заказа | domain | OrderCreated |
| Инициализация заказа | failure | OrderCreationFailed |
| Инициализация заказа | compensation | OrderCancelled |
| Резервирование товаров | domain | InventoryReserved |
| Резервирование товаров | failure | InventoryReservationFailed |
| Резервирование товаров | compensation | InventoryReleased |
| Обработка платежа | domain | PaymentProcessed |
| Обработка платежа | failure | PaymentFailed |
| Обработка платежа | compensation | PaymentRefunded |
| Организация доставки | domain | DeliveryRequested |
| Организация доставки | failure | DeliveryRequestFailed |
| Организация доставки | compensation | DeliveryCancelled |
| Завершение оформления | domain | OrderCompleted |
| Уведомление участников | domain | NotificationSent |