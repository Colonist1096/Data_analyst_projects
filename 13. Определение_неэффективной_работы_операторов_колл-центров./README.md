# Описание проекта "Определение неэффективной работы операторов колл-центров."

Телеком провайдер «Нупозвони» решил запустить новый сервис «Нупозвони мне, нупозвони!» для своих клиентов − колл-центров, который заключается в регулярном мониторинге эффективности работы операторов.

## Задача:
Нужно провести анализ эффективности работы операторов, определить критерии оценки. Информация необходима менеджерам, которые будут заниматься внедрением этого сервиса.

## Описание данных:

Данные содержатся в датасете telecom_dataset.csv, который описывает использование услуг «Нупозвони» — провайдера виртуальный телефонии. Его клиенты — колл-центры, которые:

распределяют входящие вызовы на операторов,
совершают исходящие вызовы силами операторов.
Также операторы могут делать внутренние вызовы — вызовы друг между другом внутри сети виртуальной телефонии.

telecom_dataset.csv:

- user_id — Идентификатор клиентского аккаунта колл-центра в сервисе.
- date — Дата статистики.
- direction — Направление вызовов (out - исходящий вызов, in — входящий вызов).
- internal — Является ли звонок внутренним звонком между операторами клиента.
- operator_id — Идентификатор оператора.
- is_missed_call — Является ли звонок пропущенным.
- calls_count — Количество звонков.
- call_duration — Длительность звонка (без учета времени ожидания).
- total_call_duration — Длительность звонка (с учетом времени ожидания).
