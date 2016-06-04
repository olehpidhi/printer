#Printer script (Windows Only)

Python script that uses watchdog to monitor directory changes and prints newly added files.

Dependencies:
```
pip install pypiwin32
pip install watchdog
```

Create .bat file that runs this script on os startup. Path to watched directory is passed via cmd parameter. See example in `printer.bat`.
