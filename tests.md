# Functional Test Cases

## Test Case 1

#### ID:

AIB-1

#### Summary:

Adding an item to the bag.

#### Preconditions:

- Website https://znwr.ru/ is opened.
- All possible popups are closed.

#### Test steps:

1. Click the _women_ category.
2. Select first element of clothing (photo of clothes).
3. Click the "Add to Bag" button.
4. Click the "Bag" button in the header.

#### Expected Result:

The selected product is in the bag.

#### Status:

Success.

## Test Case 2

#### ID:

BIB-1

#### Summary:

Buying item from the bag.

#### Preconditions:

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- There is at least one item in the bag.

#### Test steps:

1. Click "Bag" button in the header.
2. Fill in the fields of the order form with correct data.
3. Click the button "Proceed to payment".
4. Fill in the card data with correct data.
5. Click Pay button.

#### Expected Result:

Order is made.

#### Status:

Success.

## Test Case 3

#### ID:

DIB-1

#### Summary:

Deleting item from the bag.

#### Preconditions:

- Website https://znwr.ru/ is opened.
- All possible popups are closed.
- There is at least one item in the bag.

#### Test steps:

1. Click "Bag" button in the header.
2. Click on the trashcan icon for item.

#### Expected Result:

"Bag is empty" message appeared on the page of the bag.

#### Status:

Success.
