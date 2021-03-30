#### White Label

### Process Steps For Printing with Autobagger:

1. Turn on both printer and autobagger and allow time for them to initialize. The bagger will need to come to temp.
2. run predefined job 3 and hit start
3. Send print job via Bartender Server - xship app - scan enlinx container ID _1015599519_
4. use foot pedal to initiate print.

## Expected Result

Bag prints out with label (attach ZPL), air opens the bag, and it awaits for product to be inserted, and the foot pedal to be depressed again before it seals the bag.

## Actual Behavior

Bag prints correctly on the label but, the printer errors

```
Print Format too Long, Adjust Format or Offest. Printer in Error!
```

## Functional ZPL on Job 3

_1015599519_ - there is a second ucc label for this that doesn't print
_1015601035_

## Non Functional ZPL

_1015612496_
_1015612496_

#### Black Label

Steps are the same as above. However,the printer doesn't print specificly in the white window for the lables. The top of the document is printed black on black.
