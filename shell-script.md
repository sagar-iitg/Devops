

### show_date_time.sh


```
#!/bin/bash

echo "The date is:"

date | awk '{print $1,$2,$3}'

echo "The time is"

date | awk '{print $4}'

```


### variable.sh
```
#!/bin/bash


name="sagar"
echo "My name is: $name"

```

### Print Hello World

```
#!/bin/bash
echo "Hello World"

```

### directoryCreationAndchangeDirectory

```

cd /home/ubuntu/devops/myscript/
mkdir new_folder
cd new_folder
touch sk.txt
echo "hello sk.txt script" >> sk.txt
```
