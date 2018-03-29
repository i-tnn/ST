## ST

The main README is inside the zip archive. This one explains the functionality of the developed program pitch_ass.py.
It conatains two methods of pitch and voice estimation such as: autocorrelation and Low Pass frequency. 

## Example:

To launch the program with provided database fda_ue.gui:

```
python pitch_ass.py fda_ue.gui
```

In that case the autocorrelation method will run as it is set by default. To choose another Low Pass frequency method:
```
python pitch_ass.py -m LPF fda_ue.gui
```
After that the pitch_compare.exe program can evaluate the method:
```
pitch_compare.exe fda_ue.gui
```
