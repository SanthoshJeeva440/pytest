Delete Python Completely on Mac OS

1) run command -> which python3 and which pip3 

2) run commnd -> where python3 and where pip3

3) we need to find python installed location on mac system

3.1) /Library/Frameworks/Python.framework/Versions/3.10/bin/ -> completely delete Python.framework

3.2) /Users/calibraint/Library/Python/3.8/bin -> completely delete this folder (calibraint users name)

3.3) /Applications/Python\ 3.10/ -> completely delete this folder

3.4) once check this folder /Library/Developer/CommandLineTools/ in case the Frameworks/Python.framework/Versions/ may be installed, if means please uninstall the all python file

4) clear python cache -> python3 -m pip3 cache purge
5) https://pip.pypa.io/en/stable/cli/pip_cache/
