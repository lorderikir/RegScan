RegScan (Series 1.0.1)
======= 
travis-ci Status: [![Build Status](https://magnum.travis-ci.com/jia0020/RegScan.svg?token=jNcGbvhpzf7ShKf8jn8X)](https://magnum.travis-ci.com/jia0020/RegScan)<br>
AppVeyor Status: [![Build status](https://ci.appveyor.com/api/projects/status/iwvd7ke4vhqvanrd?svg=true)](https://ci.appveyor.com/project/jia0020/regscan)

Current Update Notes
-------
- RegScan scans in WindowsStore
- Runs with Administrative Privallages (HighestPossible)

General Usage Notes
-------
- RegScan is to be used as a background program. Scanning for changes in the Registry (regedit.exe) on targeted registry keys. It scans the following keys:
```
    - HKEY_CURRENT_USER\\Software\\Policies\\Microsoft\\WindowsStore\\WindowsStore (INT)
    - HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\System\\DisableChangePassword (DWORD)
```
- RegScan is also used to block changing of the Local Administrator (.\administrator) Password

Planned Features/Debugging (Notes for Developers)
------
- latest version is unstable (redeveloping core)
- need to find a way to block Administrator Password, registry?
- license Registry Status

Documentation/Bug Tracker:
-------
Core Site: http://jia0020.github.io/RegScan <br>
PhantomLabs Site: http://phantomlabs.me <br>
Wiki: http://github.com/jia0020/RegScan/Wiki <br>
Bug Tracking Software: http://issue.phantomlabs.me/


Installation
-------
- install with Source
- Install with commerical *.exe (downloadable within next update)

License
-------
This Program is licensed under the Apache Version 2.0 License. See LICENSE for more details.
Also Protected with EULA license.
