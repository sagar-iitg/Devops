
## Exmaple 1


### show_date_time.sh


```
#!/bin/bash

echo "The date is:"

date | awk '{print $1,$2,$3}'

echo "The time is"

date | awk '{print $4}'

```


## Exmaple 2
### variable.sh
```
#!/bin/bash


name="sagar"
echo "My name is: $name"

```

