# Pocket Todo

- App name: Pocket Todo
- Package (applicationId): `com.example.pockettodo`
- Single screen app (`MainActivity` → `TodoScreen`). No login, onboarding, permission prompts, or backend.
- Tasks are kept in memory only; a fresh launch always starts with an empty list.

## Main screen

- Title "To-do", with a counter below it: "0 tasks left", "1 task left", "N tasks left" (counts tasks not yet checked).
- A "New task" text field and an "Add" button. "Add" is disabled while the field is empty or blank.
- With no tasks, the text "No tasks yet" is shown.
- Each task row has a checkbox (checking it strikes through the title and lowers the counter) and a "Delete" button.
