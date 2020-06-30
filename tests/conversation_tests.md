#### This file contains tests to evaluate that your bot behaves as expected.
#### If you want to learn more, please see the docs: https://rasa.com/docs/rasa/user-guide/testing-your-assistant/

## general leave long path
* greet: مرحبا
  - utter_greet
  - utter_introduction
* bot_challenge: عرفني بنفسك
  - utter_introduction
* leaves_general: ما هو قانون الاجازات؟
  - utter_leaves_general
* annual_leave: اخبرني عن الاجازات السنوية
  - utter_annual_leave
  - utter_user_id
* official_holidays: ما هي العطلات الرسمية؟
  - utter_official_holidays
* unpaid_leave: ما هو النظام المتبع بما يتعلق بالاجازة بدون راتب؟
  - utter_unpaid_leave
* emergency_leave: ما هي خطة الاجازات الطارئة؟
  - utter_emergency_leave
* sick_leave: ما هو الحد اﻷقصى للاجازة المرضية؟
  - utter_sick_leave
* special_leave: اخبرني عن الاجازة الخاصة
  - utter_special_leave
* working_hours: ما هي ساعات العمل؟
  - utter_working_hours
* wages: ما هو الراتب الشهري المستحق؟
  - utter_wages
* affirm: ممتاز
  - utter_happy
* thanks: اشكرك
  - utter_thanks
* goodbye: حياك الله
  - utter_goodbye
