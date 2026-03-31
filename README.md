# Health — repository map (for humans & LLMs)

**Start here for medical context:** [`MEDICAL_FOCUS_DASHBOARD_2026.md`](MEDICAL_FOCUS_DASHBOARD_2026.md)

---

## Folder layout

| Path | Contents |
|------|----------|
| **`MEDICAL_FOCUS_DASHBOARD_2026.md`** | Priorities, lab trends, imaging summary, wearable snapshot, goal realism |
| **`docs/plans/`** | Training & nutrition plans (Markdown + printable week HTML) |
| **`analyses/`** | Medical records: labs (PDF), imaging, gynaecology notes, ultrasound, etc. *(same folder as `Analyses` on case-insensitive disks)* |
| **`data/whoop/`** | Wearable exports (CSV), e.g. `my_whoop_data_2026_03_22/` |
| **`data/training/`** | Historical running plan spreadsheets |
| **`.pdf_tools/`** | Local Python deps for PDF text extraction (optional; safe to delete) |

---

## Plans (operational)

| File | Purpose |
|------|---------|
| [`docs/plans/ACTION_PLAN.md`](docs/plans/ACTION_PLAN.md) | Body-composition & training philosophy |
| [`docs/plans/MEAL_PLAN_WEEK.md`](docs/plans/MEAL_PLAN_WEEK.md) | Weekly meals, calories, evidence notes |
| [`docs/plans/NUTRITION_PLAN_7D_FLEX_OFFICE.md`](docs/plans/NUTRITION_PLAN_7D_FLEX_OFFICE.md) | Flexible 7-day nutrition plan with grams and swaps (office + run commute) |
| [`docs/plans/DAILY_ACTIVITY_GUIDE.md`](docs/plans/DAILY_ACTIVITY_GUIDE.md) | Gym, running, daily routine, supplements |
| [`docs/plans/DAILY_OFFICE_WEIGHTLOSS_PLAN.md`](docs/plans/DAILY_OFFICE_WEIGHTLOSS_PLAN.md) | Daily office schedule templates (run-to-office / run-from-office / strength day) |
| [`docs/plans/RUNNING_PLAN_WEEK.md`](docs/plans/RUNNING_PLAN_WEEK.md) | Running week Mon→Sun |
| [`docs/plans/WEEKLY_TRACKER_PRINT.md`](docs/plans/WEEKLY_TRACKER_PRINT.md) | Printable checklist |
| [`docs/plans/WEEKLY_PLAN_FRIDGE.html`](docs/plans/WEEKLY_PLAN_FRIDGE.html) | Fridge-friendly week view (open in browser) |
| [`docs/plans/WEEK_1_EXECUTION_PLAN.md`](docs/plans/WEEK_1_EXECUTION_PLAN.md) | Concrete day-by-day week 1 schedule (office + running + nutrition) |

---

## Conventions for LLM work

1. Read **`MEDICAL_FOCUS_DASHBOARD_2026.md`** before changing nutrition or training intensity.
2. **Labs & imaging** → `analyses/` (filenames often include dates).
3. **Wearable analysis** → `data/whoop/*/sleeps.csv`, `physiological_cycles.csv`, `workouts.csv`, `journal_entries.csv`.
4. Keep edits **focused**: update `docs/plans/` for schedule changes; update dashboard when labs or priorities change.

---

## Privacy

This folder may contain **identifiable health data**. Do not commit to public repos without review.
