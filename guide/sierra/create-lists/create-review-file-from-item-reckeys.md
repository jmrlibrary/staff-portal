# create a `Review File` from a list of item reckeys

## get a list of item reckeys. 
- an item reckey (for this purpose) has this format: `i1234567`
  - Note that it does not contain the 8th 'checksum' digit, but it does contain a leading `i` (for 'item')
- a list of item reckeys (for this purpose) has this format: ` "i1234567", "i7654321", "i6784563" `
  - Note that it consists of a series of item reckeys enclosed within plain-text quotation marks (`"`) and separated by commas (`,`) with no trailing comma.

## create the `Review File` 
- start a new query
- name the file
- choose store record type: `ITEM`
- on the `[ENHANCED]` tab, choose `[ITEM] [RECORD #] [in]` and leave the final form input blank
- on the `[JSON]` tab, which will look like the following, replace the line marked (by me just now) `/**  <<<< REPLACE THIS LINE  */` with your List of Item Reckeys
- click `[SEARCH]`

```json
{
  "queries": [
    {
      "target": {
        "record": {
          "type": "item"
        },
        "id": 81
      },
      "expr": [
        {
          "op": "in",
          "operands": [
            "i_______"     /**  <<<< REPLACE THIS LINE  */
          ]
        }
      ]
    }
  ]
}
```
