# installOpenCV
Comprehensive installer for OpenCV on Raspbian (raspberry Pi).  Does NOT install virtualized.

* Primarily intended for installing OpenCV on top of the Raspbian image provided by Duet for their Duet RepRap V3 based printers.  May work with some other versions of raspbian. 

* Does NOT install multiple "virtual" environments.  
  * Nearly all the tutorials on the web for installing OpenCV do install virtual, in order to allow experimenting with multiple versions of OpenCV. This is undesireably complex for using a single release of OpenCV. 
  
* Accepts an OpenCV version when running to allow moving to newer versions without having to update the script

## Installing and Running the script
```wget https://raw.githubusercontent.com/Xonman/installOpenCV/master/installOpenCV.sh -o installOpenCV.sh```

```chmod 744 installOpenCV.sh```

```./installOpenCV.sh```

_Or specify an OpenCV version_
```./installOpenCV.sh 4.5.2```
