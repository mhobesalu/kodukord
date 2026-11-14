# Kodukord

Home cleaning checklist for our family (English + Estonian). Daily list, one focus area per day, monthly and quarterly jobs, kids' helper jobs.

Live: https://mhobesalu.github.io/kodukord/

Family sync uses Firebase Realtime Database. Settings live in `config.js`; the database rules are in `database.rules.json`.

## Pesa – family hub (`/pesa/`)

Live: https://mhobesalu.github.io/kodukord/pesa/

Family hub for schedules, to-dos and must-dos, dreams, house and car care (last done / next time), birthdays, insurance and seasonal dates. English + Estonian, works on phone, laptop and a wall screen (Settings > Keep screen on).

Everything you type is saved only on the device (localStorage). No family data is stored in this repository. Sync between devices will use the same Firebase project as Kodukord (`pesa/{code}`), behind a family login, once it is set up.
