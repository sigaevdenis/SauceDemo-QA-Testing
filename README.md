# 🧪 Тестирование Swag Labs (SauceDemo)

[![Status](https://img.shields.io/badge/Status-Завершён-brightgreen?style=flat-square)]()
[![Test Cases](https://img.shields.io/badge/Test%20Cases-45-blue?style=flat-square)]()
[![Bugs](https://img.shields.io/badge/Bugs%20Found-10-red?style=flat-square)]()
[![Critical](https://img.shields.io/badge/Critical-3-orange?style=flat-square)]()

**Pet-проект Junior QA Engineer**
**Денис Сигаев** · Май 2026

---

## О проекте

Комплексное функциональное тестирование демо-приложения **Swag Labs** — интернет-магазина с несколькими типами пользователей, включая намеренно «сломанные» аккаунты для тренировки поиска багов.

**Цели проекта:**
- отработать полный цикл ручного тестирования — от плана до баг-репортов;
- потренироваться в составлении тестовой документации по стандартам индустрии;
- найти и грамотно задокументировать реальные дефекты приложения;

---

## Что сделано

| | |
|---|---|
| 📋 **Test Plan** | Составлен план тестирования с областью покрытия и подходом |
| ✅ **45 тест-кейсов** | Login, Inventory, Cart, Checkout, Menu, Logout, спецпользователи |
| 🐞 **10 баг-репортов** | Из них 3 — Critical, с шагами воспроизведения и severity/priority |
| 🔁 **Виды тестирования** | Smoke, Functional, Regression, Negative, Boundary |
| ☑️ **Чек-листы** | Для быстрой smoke/регрессионной проверки перед релизом |
| 👥 **6 пользователей** | standard_user, problem_user, error_user, visual_user, performance_glitch_user, locked_out_user |

---

## Технологии и инструменты

`Manual Testing` · `Test Case Design` · `Bug Reporting` · `Chrome DevTools` · `Markdown / Google Sheets`

---

## Результаты

Обнаружено **10 дефектов**, из них **3 критичных**, блокирующих оформление заказа или добавление товара в корзину для отдельных сегментов пользователей — то есть реальные баги, которые в проде остановили бы часть покупателей на пути к оплате.

---

## Документация проекта

- 📋 [Test Plan](Testplan.md)
- ✅ [Test Cases (45)](https://github.com/sigaevdenis/SauceDemo-QA-Testing/blob/main/Test%20Cases/%D0%A2%D0%B5%D1%81%D1%82-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B_SwagLabs.md)
- 🐞 [Bug Reports (10)](https://github.com/sigaevdenis/SauceDemo-QA-Testing/blob/main/Bug%20Reports/%D0%91%D0%B0%D0%B3-%D1%80%D0%B5%D0%BF%D0%BE%D1%80%D1%82%D1%8B.md)
- ☑️ [Чек-листы](https://github.com/sigaevdenis/SauceDemo-QA-Testing/tree/main/Checklists)
