# SkillTrace prototype

This is a private, browser-only dashboard prototype. It starts with demo data so the presentation works immediately.

## Add your own data

1. In Excel, open the sheet that contains trainee or learner outcomes.
2. Remove direct personal details such as name, phone number, email address, Aadhaar number, and full salary.
3. Save the sheet as **CSV UTF-8 (Comma delimited) (*.csv)**.
4. Open `index.html` in a web browser.
5. Select **Upload outcome CSV**.
6. In **Map your data columns**, choose the column that matches each requested field, then select **Build dashboard**.

The important learner-outcome columns are:

| What the dashboard needs | Example column name |
| --- | --- |
| Learner ID | `learner_id` |
| District | `district` |
| Institute | `institute_name` |
| Course | `course_name` |
| Learner skills | `skills` |
| Completion status | `completion_status` |
| Placement status | `placement_status` |
| Retention status, optional | `retention_status` |

If you also have employer data, save it as a second CSV and select **Add employer demand CSV**. Useful columns are `district`, `job_role`, `required_skills`, and `vacancies`.

The dashboard does not send uploaded files anywhere. It processes them only in the open browser tab.
