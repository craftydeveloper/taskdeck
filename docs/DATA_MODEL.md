# Data model

## Proposed fields

Tasks need a title, status, owner, priority, optional due date, and notes.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.