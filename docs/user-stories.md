
# User Stories

## User Story 1: Grocery Inventory Management

As a household grocery manager, I want to input and categorize newly purchased food items with their storage details, so that the system can accurately track my inventory.

### Acceptance Criteria

1. Given that the user is adding a grocery item, when they enter the food item's name, purchase date, storage type (pantry, fridge, or freezer), and initial freshness status, then the system records the item with the provided details.

2. Given that the user has entered the required grocery details, when they save the item, then the new item appears in the inventory with its recorded information so that the user can review and track it.

**Related requirement:** FR1 - Grocery Item Entry

## User Story 2: Proactive Spoilage Alerts

As a busy consumer, I want to receive proactive alerts when my perishable items are approaching their predicted spoilage window, so that I can use them before they go bad.

### Acceptance Criteria

1. Given that a stored food item is approaching its predicted spoilage window, when the system identifies the item as needing attention, then it alerts the user and identifies the relevant food item.

2. Given that the user receives a spoilage alert, when they review the alert, then they can identify which food item should be prioritized for consumption.

**Related requirement:** FR2 - Spoilage Risk Prediction


## User Story 3: Inventory Prioritization

As a household user, I want my groceries sorted by estimated spoilage risk and relevant dates, so that I can decide which items to check or use first.

### Acceptance Criteria

1. Given multiple eligible grocery records, when the inventory is displayed, then items are ordered using the documented prioritization logic.

2. Given an item is prioritized, when the user views its details, then its risk category and relevant date information are displayed.

3. Given required prediction inputs are missing, when the inventory is displayed, then the system identifies the item as unavailable for reliable prediction.

**Related requirements:** FR3, FR5, FR6.
