# Python On Windows 

## use python on Windows

Environment control:

Conda

Virtualenv

Set environment path:

* For all users:

PATH=%PATH%;C:\ProgramData\Anaconda3;C:\ProgramData\Anaconda3\Scripts
* For one user:

PATH=%PATH%;"C:\Users\iemsuser\Anaconda3";"C:\Users\iemsuser\Anaconda3\Scripts"

# For data

## Data Clean

Data pre-explore:

```
import pandas_profiling  
data.profile_report(title='report title')
```
