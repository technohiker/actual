- [ ] How to handle dataComponents?

- [ ] Some functions like onDelete are expected to have a Promise, but do not.

# BudgetCategories Type to-do list:
- L66: value type is any.
- L115: newDrag State: DragState<what type?>
- L160: group type


# Patch Notes
Objective: Convert BudgetCategories to TypeScript.

index.tsx
## Changed onSaveGroup in index.tsx to async.
- Updated in BudgetTable