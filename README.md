# AppliedCalculationsLab4<br>Andrey Ryabov

## Процесс виконання

Відкриття діалогового вікна графічного інтерфейсу System Identification

> ident

![image](https://user-images.githubusercontent.com/43186510/213918924-4f1b4cd9-c0f9-492d-a793-0763f525509b.png)

У режимі командного рядку вводимо команду 

> load dryer2

Вікно імпорту даних

![image](https://user-images.githubusercontent.com/43186510/213919311-396e9475-dde4-4f03-8ad3-af2211cea87f.png)

![image](https://user-images.githubusercontent.com/43186510/213919347-207ab161-940e-4ffb-9e9e-41750413a95d.png)

Вікно імпорту даних прикладу

![image](https://user-images.githubusercontent.com/43186510/213919439-236deba1-e90c-4685-aa68-b630490496e0.png)

![image](https://user-images.githubusercontent.com/43186510/213919494-2a2d5af5-566f-40d1-9d27-79ad6ae5ea51.png)

Виставимо TimePlot

![image](https://user-images.githubusercontent.com/43186510/213919544-f6967ac8-b41e-4bb0-bc54-8a66b36e0384.png)

Активізуємо розкривається Preprocess (Попередня обробка) і виберемо в ньому опцію Remove means (Видалити середнє)

![image](https://user-images.githubusercontent.com/43186510/213919649-82a602cf-3c90-4292-b4f4-b6041d340e06.png)

### Побудова моделі

В якості даних для побудови моделі приймаємо дані Fend. Перетягнемо їх мишею в область Working Data (в центрі вікна інтерфейсу). Задаємо діапазон зміни даних. Для цього активізуємо опцію Select Range (Вибір діапазону) зі списку Preprocess.

![image](https://user-images.githubusercontent.com/43186510/213919835-47626496-858d-4436-b01c-f41a00715d41.png)

Діапазон можна задати в текстовому віконці Time span або за допомогою миші, виділяючи прямокутну область. Будь-яким з цих способів вказуємо діапазон від 1 до 50 з і натиснемо кнопку Insert.

![image](https://user-images.githubusercontent.com/43186510/213920010-f4faa09a-f687-4d59-9112-f37a3958b9dd.png)

### Оцінка моделі

Графік перехідної функції, знайдені кореляційним методом

![image](https://user-images.githubusercontent.com/43186510/213920155-5b5318e0-0026-4a9f-a614-d28e10966130.png)

Амплітудна і фазова частотні характеристики

![image](https://user-images.githubusercontent.com/43186510/213920225-92fd6718-c321-448c-a52e-fc19d069b288.png)

Результат ARX моделей

![image](https://user-images.githubusercontent.com/43186510/213920494-a3ff0d7e-2763-4d71-9c80-901ddb475c5a.png)

