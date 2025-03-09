- [ ] How to handle dataComponents?

- [ ] Some functions like onDelete are expected to have a Promise, but do not.

# BudgetCategories Type to-do list:
- L66: onCollapse argument type is any.
- L91: What value gets added in addition to the type?  What group ID?
- L115: newDrag State: DragState<what type?>


# Patch Notes
Objective: Convert BudgetCategories to TypeScript.

index.tsx
## Changed onSaveGroup in index.tsx to async.
- Updated in BudgetTable