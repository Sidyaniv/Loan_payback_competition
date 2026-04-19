1. Основные данные

- age (int64) – Возраст (in years).

- gender (category) – пол (Male/Female).

- marital_status (category) – семейное положение (Single, Married, Divorced).

- education_level (category) – Уровень образования (High School, Bachelor, Master, PhD).

2. Финансовая информация.

- annual_income (float64) – Годовой доход.

- monthly_income (float64) – Месячный доход.

- employment_status (category) – Тип занятости [Работает, Самозанятый, Безработный] (Employed, Self-Employed, Unemployed).

- debt_to_income_ratio (float64) – Отношение долга заемщика к его доходу . Lower = better.

- credit_score (int64) – Скор заёмщика. Higher = less risky.

3. Информациия по кредиту.

- loan_amount (float64) – Сумма кредита.

- loan_purpose (category) – Цель кредита (Car, Education, Home, Medical, etc.).

- interest_rate (float64) – Номинальная годовая процентная ставка по кредиту (%).

- loan_term (int64) – Срок погашения кредита (months, e.g., 36 or 60).

- installment (float64) – Ежемесячный взнос .

- grade_subgrade (category) – Категория риска, присвоенная кредиту (A1, B2, etc.).

4. Кредитная история.

- num_of_open_accounts (int64) – Всего кредитных счетов.

- total_credit_limit (float64) – Общий доступный кредитный лимит.

- current_balance (float64) – Непогашенный остаток по кредиту(loan + credit card).

- delinquency_history (int64) – Количество просроченных платежей за всю историю.

- public_records (int64) – Дополнительные отрицательные сведения (e.g., банкротсво, судебные иски).

- num_of_delinquencies (int64) – Общая сумма просрочек (missed payments).

5. Целевая переменная

- loan_paid_back (int64) – Вернул ли кредит человек:

1 → Вернул полностью.

0 → Не вернул весь долг