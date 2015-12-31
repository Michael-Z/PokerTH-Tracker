PokerTH Tracker
===============

This is a simple poker statistics program to analyse your opponents'
behaviour.
It reads the PokerTH logs, so you should collect them for a more
precise analysis.


Compile and Install
-------------------

This program has two build systems: QMake and CMake. You can choose.

CMake:
  $ cd /path/to/PokerTH_tracker
  $ mkdir build
  $ cd build
  $ cmake .. && make
  $ sudo make install
  
QMake:
  $ cd /path/to/PokerTH_tracker
  $ mkdir build
  $ cd build
  $ lrelease ../PokerTH_tracker.pro
  $ qmake ../PokerTH_tracker.pro && make
  $ sudo make install


License
-------

(C) 2015-2016 Daniel Steinhauer (9 of Spades)

PokerTH Tracker is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

PokerTH Tracker is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.