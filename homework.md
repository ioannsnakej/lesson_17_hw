Задание 1:
  Вводные данные
  
  Есть таблица анализов Analysis:
  
  ● an_id — ID анализа;
  
  ● an_name — название анализа;
  
  ● an_cost — себестоимость анализа;
  
  ● an_price — розничная цена анализа;
  
  ● an_group — группа анализов.
  
  Есть таблица групп анализов Groups:
  
  ● gr_id — ID группы;

  ● gr_name — название группы;
  
  ● gr_temp — температурный режим хранения.
  
  Есть таблица заказов Orders:
  
  ● ord_id — ID заказа;
  
  ● ord_datetime — дата и время заказа;
  
  ● ord_an — ID анализа.
  
  Формулировка: вывести название и цену для всех анализов, которые
  продавались 5 февраля 2020 и всю следующую неделю

  Устанавливаю mariadb:
  
    sudo apt update && sudo apt install -y mariadb-server

  устанавливаю mysql secure:

    sudo mysql_secure_installation

  и устанавливаю пароль для root

  <img width="801" height="269" alt="image" src="https://github.com/user-attachments/assets/2f0742fe-be48-4dd8-934f-f3ad559ed82e" />

  подключаюсь к mysql:

  <img width="824" height="279" alt="image" src="https://github.com/user-attachments/assets/46c16643-14a1-4c76-a507-dfdfa8e2e5ad" />

  создаю базу данных и подключаюсь:

  <img width="481" height="165" alt="image" src="https://github.com/user-attachments/assets/ce08c047-6ff0-4f67-aca1-b351b2e8f8a8" />

  создаю таблицы:

  <img width="911" height="398" alt="image" src="https://github.com/user-attachments/assets/9b031b1c-4ab6-4193-bf56-fdb5b3fa1a04" />

  Добавляю значения в таблицы:

  <img width="909" height="265" alt="image" src="https://github.com/user-attachments/assets/52bc0e24-f059-43cf-9f95-5e709c11d5fa" />

  <img width="913" height="460" alt="image" src="https://github.com/user-attachments/assets/27198031-f155-46db-829e-60a25c8ec0f3" />

  пишу селект:

  <img width="908" height="754" alt="image" src="https://github.com/user-attachments/assets/6a356c03-e653-4587-929e-e14dcfe7dda6" />








