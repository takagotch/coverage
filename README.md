### coverage
---
https://pypi.org/project/coverage/

```py
import coverage
cov = coverage.Coverage()
cov.start()

cov.stop()
cov.save()

cov.html_report()


from coverage import Coverage

cov = Coverage()
cov.start()
cov.stop()
cov.html_report(directory='covhtml')
```

```sh
coverage run my_program.py arg1 arg2
coverage report -m
coverage html
```

```
```


