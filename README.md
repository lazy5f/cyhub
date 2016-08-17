# cyhub

## Set up environment

### Windows

#### Win: Install Python 3.5, PyQt5, vtk 7, SimpleITK 0.10.0 (2016, August 17)

1. Install Python 3.5
  * www.python.org

1. Install PyQt5
  * ```pip install PyQt5```

1. Install vtk 7
  * http://www.lfd.uci.edu/~gohlke/pythonlibs/

1. Install simpleITK
  * ```pip install simpleitk```

#### Mac: Install Python 3.5, PyQt5, vtk 7 using homebrew (2016, August 17)

1. Install Xcode

1. xcode-select
  * https://github.com/Homebrew/homebrew-python/issues/234
  * ```$ sudo xcode-select --install```

1. Install homebrew
  * http://brew.sh/
  * ```$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

1. Update homebrew
  * https://github.com/Homebrew/brew/blob/master/share/doc/homebrew/Troubleshooting.md
  * ```$ brew update```
  * ```$ brew update```
  * ```$ brew doctor```
 
1. Install Python 3.5
  * ```$ brew install python3```

1. Install PyQt5
  * ```$ brew install pyqt5```

1. Install vtk 7
  * https://blog.kitware.com/kitware-packages-on-os-x-with-homebrew/
  * ```$ brew tap homebrew/homebrew-science```
  * ```$ brew install vtk --without-python --with-python3```


### Build SimpleITK on Mac (TODO)
