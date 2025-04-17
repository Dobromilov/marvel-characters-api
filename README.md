# **Marvel Characters Gallery - JavaScript Lab Project**  

🚀 **Проект:** Веб-приложение для отображения персонажей Marvel с использованием API.  
🔹 **Цель:** Получение данных с API, рендеринг карточек персонажей и модальных окон.  
🔹 **Технологии:** JavaScript (Fetch API), HTML5, Bootstrap 5.  

---

## **📌 Описание проекта**  
Этот проект представляет собой интерактивную галерею персонажей Marvel, которая:  
✔ Загружает данные с публичного API (`jsfree-les-3-api.onrender.com`).  
✔ Отображает персонажей в виде карточек с изображениями и именами.  
✔ Позволяет открывать модальные окна с подробной информацией (описание, дата изменения).  
✔ Обрабатывает ошибки загрузки данных.  

---

## **🛠 Функционал**  
### **1. `index.js`**  
📌 **`fetchCharacters()`**  
- Делает запрос к API Marvel.  
- Обрабатывает ответ и ошибки.  
- Рендерит карточки (`getCharacterCards`) и модальные окна (`getCharacterModals`).  

📌 **`getCharacterCard(character)`**  
- Генерирует HTML-карточку персонажа (изображение, имя, кнопка "Подробнее").  

📌 **`getCharacterModal(character)`**  
- Создает модальное окно с детальной информацией (описание, дата изменения).  

### **2. `index.html`**  
- Базовая структура с Bootstrap 5.  
- Контейнеры для карточек (`character-card-box`) и модальных окон (`character-modal-box`).  

---

## **🚀 Как запустить проект?**  
1. **Склонируйте репозиторий:**  
   ```sh
   git clone https://github.com/ваш-логин/marvel-characters-api.git
   ```
2. **Откройте `index.html` в браузере.**  
3. **Или запустите на Replit:**  
   - [Шаблон для Replit](https://replit.com/@5t0dgm/Lab13JS-les-3-start-template)  

---

## **🔧 Возможные улучшения**  
- Добавить поиск по имени.  
- Реализовать пагинацию (если API поддерживает).  
- Добавить фильтрацию по комиксам/сериям.  

---

### **🔗 Ссылки**  
🌐 **GitHub:** [https://github.com/ваш-логин/marvel-characters-api](https://github.com/ваш-логин/marvel-characters-api](https://dobromilov.github.io/marvel-characters-api/)  
🛠 **API:** [https://jsfree-les-3-api.onrender.com/characters](https://jsfree-les-3-api.onrender.com/characters)  

---

**🎯 Итог:**  
Этот проект демонстрирует работу с API, асинхронными запросами (`fetch`) и динамическим рендерингом данных в веб-интерфейсе. Отлично подходит для учебных целей и портфолио!  

--- 
