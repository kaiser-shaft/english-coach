# FRAMES.md — БАНК ШАБЛОНОВ: МОДУЛЬ 1

# Фокус: Present Perfect, Past Simple, Duration (Since/For), IT Incidents & Travel

---

## 1. СТАТУСЫ ЗАДАЧ И РЕЗУЛЬТАТ (Present Perfect vs Past Simple)

### Template 01

- **Каркас:** `I have already [V3] [Object], but I haven't [V3] [Object] yet.`
- **Значение:** Я уже сделал X, но еще не сделал Y к текущему моменту.
- **Примеры:**
  - _IT:_ I have already deployed the hotfix, but I haven't verified the logs yet.
  - _Travel:_ I have already checked in online, but I haven't printed the boarding pass yet.

### Template 02

- **Каркас:** `We [V2] [Object] [Time Marker: yesterday / an hour ago / on Monday], so now [Current Status].`
- **Значение:** Действие завершилось в конкретный момент в прошлом, и вот каков результат сейчас.
- **Примеры:**
  - _IT:_ We merged the pull request an hour ago, so now the build is running on staging.
  - _Travel:_ We landed in Munich two hours ago, so now we are heading to the train station.

### Template 03

- **Каркас:** `Have you had a chance to [Infinitive] [Object] yet?`
- **Значение:** У тебя уже появилось время / была возможность сделать X? (вежливый пинг).
- **Примеры:**
  - _IT:_ Have you had a chance to review my pull request yet?
  - _Travel:_ Have you had a chance to check the museum opening hours yet?

### Template 04

- **Каркас:** `I haven't been able to [Infinitive] because [Reason / Blocked by].`
- **Значение:** У меня пока не получилось сделать X, потому что возник блокер.
- **Примеры:**
  - _IT:_ I haven't been able to reproduce this bug because the staging environment is down.
  - _Travel:_ I haven't been able to reach the host because my roaming is not working.

### Template 05

- **Каркас:** `We noticed that [Subject] [V2] when we [V2].`
- **Значение:** Мы заметили, что произошло X, когда выполнили Y в прошлом.
- **Примеры:**
  - _IT:_ We noticed that the database latency increased when we started the migration.
  - _Travel:_ We noticed that the ticket office closed when we arrived at the platform.

### Template 06

- **Каркас:** `Have you ever encountered [Noun / Error / Issue] before?`
- **Значение:** Ты когда-либо в своем опыте сталкивался с такой проблемой/ошибкой?
- **Примеры:**
  - _IT:_ Have you ever encountered this "CORS policy" error with this framework before?
  - _Travel:_ Have you ever encountered an overbooking issue with this airline before?

---

## 2. IT-ИНЦИДЕНТЫ, БАГ-РЕПОРТЫ И ХРОНОЛОГИЯ (Past Sequences)

### Template 07

- **Каркас:** `The system [V2: crashed / stopped responding] right after we [V2].`
- **Значение:** Система упала/зависла сразу после того, как произошло конкретное действие.
- **Примеры:**
  - _IT:_ The API stopped responding right after we pushed the new container image.
  - _Travel:_ The taxi app stopped responding right after I confirmed the payment.

### Template 08

- **Каркас:** `I checked the [Source: logs / dashboard / display] and found that [Subject] [V2].`
- **Значение:** Я проверил источник данных и обнаружил произошедшее событие.
- **Примеры:**
  - _IT:_ I checked the server logs and found that the background worker ran out of memory.
  - _Travel:_ I checked the airport display and found that our gate changed to B14.

### Template 09

- **Каркас:** `To reproduce the issue: first, [V1]; then, [V1]; finally, [V1].`
- **Значение:** Пошаговый сценарий воспроизведения проблемы (Steps to Reproduce).
- **Примеры:**
  - _IT:_ To reproduce the issue: first, log out; then, clear cookies; finally, submit the form again.
  - _Travel:_ To find the terminal: first, exit baggage claim; then, turn right; finally, take the elevator.

### Template 10

- **Каркас:** `We have temporarily rolled back to [Version / Commit] while we investigate [Problem].`
- **Значение:** Временное действие в настоящем с привязкой к продолжающемуся расследованию.
- **Примеры:**
  - _IT:_ We have temporarily rolled back to commit `a8f3d` while we investigate the CPU spike.
  - _Travel:_ We have temporarily stayed at the station cafe while we look for another hotel.

### Template 11

- **Каркас:** `The root cause was [Noun / V-ing], but we have already resolved it.`
- **Значение:** Первопричина была в прошлом, но проблема уже устранена к настоящему моменту.
- **Примеры:**
  - _IT:_ The root cause was an unindexed database query, but we have already resolved it.
  - _Travel:_ The issue was an incorrect terminal number on the ticket, but we have already fixed our route.

### Template 12

- **Каркас:** `Initially, we assumed that [Subject] [V2], but actually [Subject] [V2].`
- **Значение:** Описание ложной гипотезы против реальной причины инцидента.
- **Примеры:**
  - _IT:_ Initially, we assumed that the network failed, but actually the authentication token expired.
  - _Travel:_ Initially, we assumed that the train was delayed, but actually it departed from platform 3.

---

## 3. ДЛИТЕЛЬНОСТЬ И ТЕКУЩИЕ СОСТОЯНИЯ (Since / For / Duration)

### Template 13

- **Каркас:** `This error has been occurring since [Specific Point: 10 AM / the last deployment].`
- **Значение:** Ошибка повторяется непрерывно, начиная с определенного момента в прошлом.
- **Примеры:**
  - _IT:_ This 504 error has been occurring since the morning cluster upgrade.
  - _Travel:_ The flight has been delayed since 9 AM due to heavy fog.

### Template 14

- **Каркас:** `The service has been running smoothly for [Duration: 24 hours / three weeks].`
- **Значение:** Процесс стабильно длится на протяжении определенного периода времени.
- **Примеры:**
  - _IT:_ The new authentication microservice has been running smoothly for two weeks.
  - _Travel:_ The local transport pass has been valid for five days.

### Template 15

- **Каркас:** `I have been trying to [Infinitive] for [Duration], but it keeps [V-ing].`
- **Значение:** Я пытаюсь сделать что-то на протяжении X времени, но система продолжает сбоить.
- **Примеры:**
  - _IT:_ I have been trying to build this Docker container for 40 minutes, but it keeps failing at step 6.
  - _Travel:_ I have been trying to complete the online check-in for an hour, but the website keeps crashing.

### Template 16

- **Каркас:** `How long has this [Subject] been [V-ing: failing / throwing errors / pending]?`
- **Значение:** Вопрос о длительности продолжающейся проблемы.
- **Примеры:**
  - _IT:_ How long has this CI pipeline been hanging on the test stage?
  - _Travel:_ How long has this luggage carousel been stopped?

### Template 17

- **Каркас:** `We have had this [Noun: issue / limitation / contract] since we [V2: upgraded / switched to].`
- **Значение:** У нас сохраняется состояние с тех пор, как произошло разовое действие.
- **Примеры:**
  - _IT:_ We have had this memory leak issue since we upgraded to Node 20.
  - _Travel:_ We have had no hot water in the apartment since we checked in yesterday.

---

## 4. БЫТОВЫЕ СИТУАЦИИ И НАВИГАЦИЯ В ПОЕЗДКАХ (Travel Logistics)

### Template 18

- **Каркас:** `I have a reservation under the name of [Last Name] for [Number] nights.`
- **Значение:** Регистрация бронирования в отеле или апартаментах.
- **Примеры:**
  - _Travel:_ I have a reservation under the name of Petrov for four nights, starting today.
  - _Coworking:_ I have a desk reservation under the name of Alex for two days.

### Template 19

- **Каркас:** `Could you please tell me how to get to [Location / Terminal / Platform]?`
- **Значение:** Вежливый запрос маршрута на транспортном узле или в городе.
- **Примеры:**
  - _Travel:_ Could you please tell me how to get to the express train to the city center?
  - _Conference:_ Could you please tell me how to get to Workshop Room B?

### Template 20

- **Каркас:** `My key card has stopped working; could you please [reactivate / replace] it?`
- **Значение:** Сообщение о внезапно переставшем работать электронном ключе/пропуске.
- **Примеры:**
  - _Travel:_ My key card has stopped working; could you please reactivate it for room 412?
  - _Office:_ My badge has stopped working; could you please check my access permissions?

### Template 21

- **Каркас:** `We arrived at [Time], but [Service / Room / Ride] isn't [Adjective / Ready] yet.`
- **Значение:** Фиксация факта прибытия и неготовности услуги.
- **Примеры:**
  - _Travel:_ We arrived at 3 PM, but our room isn't ready yet. Is there a place to leave our bags?
  - _Office:_ I arrived at the meeting room on time, but the video conference link isn't active yet.

---

## 5. ФОРС-МАЖОРЫ И ЭСКАЛАЦИИ В ПОЕЗДКАХ (Travel Emergencies)

### Template 22

- **Каркас:** `My flight has just been [delayed / cancelled]; what are my alternative options?`
- **Значение:** Запрос решения при внезапной отмене или переносе рейса.
- **Примеры:**
  - _Travel:_ My flight has just been cancelled; what are my alternative options to reach London today?
  - _IT (Metaphor):_ The upstream vendor has just deprecated this API; what are our fallback options?

### Template 23

- **Каркас:** `I left my [Item] on the [Vehicle: plane / train / bus]; has anyone turned it in?`
- **Значение:** Обращение в бюро находок или на стойку информации о забытой вещи.
- **Примеры:**
  - _Travel:_ I left my black backpack on train ICE 721; has anyone turned it in to lost and found?
  - _Conference:_ I left my charger in the main presentation hall; did anyone find it?

### Template 24

- **Каркас:** `I have been waiting at [Gate / Carousel] for [Duration], but my [Baggage / Transfer] hasn't arrived.`
- **Значение:** Претензия по поводу длительного ожидания багажа или трансфера.
- **Примеры:**
  - _Travel:_ I have been waiting at carousel 3 for 50 minutes, but my checked luggage hasn't arrived yet.
  - _IT:_ I have been waiting for the build to finish for 30 minutes, but the artifact hasn't been uploaded yet.

### Template 25

- **Каркас:** `There seems to be an error in this bill; I didn't [V1: order / use / request] [Item].`
- **Значение:** Вежливое оспаривание лишних списаний или строк в чеке/инвойсе.
- **Примеры:**
  - _Travel:_ There seems to be an error in this hotel invoice; I didn't use the minibar on Tuesday.
  - _SaaS/Cloud:_ There seems to be an unexpected charge on this AWS bill; we didn't run this GPU instance.
