# Hertie-School-Maths-Data-Science-f2026 - cohort control repo

This is the **`.github` repo** for the `Hertie-School-Maths-Data-Science-f2026` cohort org. It holds this cohort's configuration
and the auto-generated student-facing org page - **faculty, instructors and faculty assistants (FAs) delivering the course rarely need to touch it directly.**

- The **faculty & instructors action buttons** (Release, Grade, Sync ...) live in the **parent course org's**
  `.github` **Actions** tab, not here. This repo has no `dsl-course.yml` of its own - all of
  this cohort's config lives in **classroom-config** instead:
  `schedule.yml` (release calendar + due dates), `people.yml` (this cohort's own
  instructors/TAs), `students.csv`, `teams.csv`, `grades/`.
- Course identity (name/code) and `course_admins` are inherited from the parent course org,
  kept in sync by **Sync membership**.
- `profile/README.md` - the student-facing org landing page (auto-generated; don't hand-edit).
- Students join via the **welcome** repo's "Join course" issue; the roster lives in **classroom-config**.

Built and kept in sync by the [DSL teaching toolkit](https://github.com/hertie-data-science-lab/dsl-teaching-toolkit).
