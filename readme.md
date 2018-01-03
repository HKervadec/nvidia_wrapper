# Wrapper
To use it, simply put the wrapper before the usual script:
```
./launch.sh python3 superscript.py argument1 --param=toto
```
If you face some path troubles (it will be launched from the wrapper location), that can be easily be fixed:
```
PATH=$PATH:path_to_code ./launch.sh <initial command>
```
