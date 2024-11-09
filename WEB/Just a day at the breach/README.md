# Just a day at the breach
**Category**: WEB
**Value**: 464
**ID**: 157

## Challenge Description
```
```py
import os
import json
import zlib

def lambda_handler(event, context):
    try:
        payload=bytes.fromhex(event["queryStringParameters"]["payload"])
        flag = os.environ["flag"].encode()
        message = b"Your payload is: %b\nThe flag is: %b" % (payload, flag)
        compressed_length = len(zlib.compress(message,9))
    except ValueError as e:
        return {'statusCode': 500, "error": str(e)}

    return {
        'statusCode': 200,
        'body': json.dumps({"sniffed": compressed_length})
    }
```

It's a little more crypto than web, but I know the exploit from a web defcon talk ages ago.  This is a common web exploit for network sniffers.

-ProfNinja
```

## Solve
Add your solution notes here.
