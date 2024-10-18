# This the Readme file of the Application

[Website](https://github.com/Blogtech1)

```bash
  echo "Hello World"
```

```python
  print("Hello World")
```

# Features
- fun functional programming
- output bundle size less ~22% than JSX
- faster render and mount up to ~10% than JSX
- smooth integration to an existing React project with JSX
- no transpiler necessary, can be run directly in browser

```bash
 echo -e "Eneter Some Character : \c"
 read value

 case $value in
    [a-z] )
    echo "User entered $value which belongs to a-z category" ;;
    [A-Z] )
    echo "User entered $value which belongs to A-Z category" ;;
    [0-9] )
    echo "User entered $value which belongs to 0-9 category" ;;
    ? )
    echo "User entered $value which belongs to special Character category" ;;
    * )
    echo "User entered Unknown $value" ;;

 esac
```

```bash
  ###### OS Logs ######
  [WinEventLog://Application]
  disabled = 0
  start_from = oldest
  current_only = 0
  checkpointInterval = 5
  renderXml=true
  index = my_first_index
  
  [WinEventLog://Security]
  disabled = 0
  start_from = oldest
  current_only = 0
  evt_resolve_ad_obj = 1
  checkpointInterval = 5
  blacklist1 = EventCode="4662" Message="Object Type:(?!\s*groupPolicyContainer)"
  blacklist2 = EventCode="566" Message="Object Type:(?!\s*groupPolicyContainer)"
  renderXml=true
  index = my_first_index
```


```python
# Import the necessary libaries
import requests
import re
from random import randint
import json


# My API KEY
apiKEY="c738b75f4bbf560194d81d4e88f462ab"

# Send a GET request to an API
def send_request(apiURL, apiKEY=apiKEY):
    """Submit GET request to api server."""
    # Set params
    params = {
        "api_key": apiKEY
    }
```
