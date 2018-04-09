PyRy3D: a software tool for macromolecular structure modeling


(c) 2010 by Joanna M. Kasprzak, Wojciech Potrzebowski, Mateusz Dobrychłop and Janusz M. Bujnicki

Version 4.0.0

Homepage:
http://genesilico.pl/pyry3d/   

Technical Support:
    jkasp@amu.edu.pl

------------------------------------------------------------------------

INSTALLATION INSTRUCTIONS

1. Requirements:

PyRy3D runs on any modern Windows or Linux PC. There is a source code with full functionality, but requires some libraries.


2. Installation on Linux

To install PyRy3D on Linux, you need to:

- Download the source distribution

- Unzip the archive. A catalog with the main program pyry3d.py is created.

- Make sure Python 2.5 or a higher version is installed. (on Ubuntu Linux, use sudo apt-get install python.

- Make sure Numpy is installed (sudo apt-get install python-numpy).

- Make sure BioPython is installed (sudo apt-get install python-biopython).
   (tested with BioPython 1.54)

- Make sure the PyRy3D/pyry3d.py file is executable:
  chmod a+x PyRy3D/pyry3d.py

- Add the path to the PyRy3D directory to your PYTHONPATH variable,e.g. 

- run:
  python pyry3d.py -h


3. Installing PyRy3D on Windows

To install PyRy3D on Windows, you need to:

- Download the source distribution

- Unzip the archive. A catalog with the main program pyry3d.py is created.

- Make sure that these libraries are installed:
    Python 2.5 or a higher
    Numpy
    BioPython (tested with BioPython 1.57)

- After this, you can write in the Python shell:

python pyry3d.py -h

------------------------------------------------------------------------

LEGAL DISCLAIMER

PyRy3D is released under the GPL license, a copy of which is included in 
the distribution (See LICENSE_GPL.TXT for details). For the files in the 
PDB/ directory, the Biopython License applies as well. 
See PDB/LICENSE_BIOPYTHON.TXT for details).

This software is provided "as-is". There are no expressed or implied 
warranties of any kind, including, but not limited to, the warranties of 
merchantability and fitness for a given application. In no event shall 
the authors be liable for any direct, indirect, incidental, special, 
exemplary or consequential damages (including, but not limited to, loss 
of use, data or profits, or business interruption) however caused and on 
any theory of liability, whether in contract, strict liability or tort 
(including negligence or otherwise) arising in any way out of the use 
of this software, even if advised of the possibility of such damage.

The authors take no responsibility for damage caused by this program 
or its components. 

------------------------------------------------------------------------

CREDITS

Joanna M. Kasprzak    - implementation, architecture, tests
Wojciech Potrzebowski - CCP4_reader implementation
Mateusz Dobrychlop    - PyRy3D Chimera Extension and PyRy3D testing
Janusz Bujnicki       - concept and supervision

-----------------------------------------------------------------------

ACKNOWLEDGEMENTS

Credit goes to our lab colleagues Anna Czerwoniec, Kaja Milanowska, 
Anna Philips, Tomasz Puton, Kristian Rother for their comments and 
constructive criticism during development. 
Special thanks to Dominik Kasprzak and Michał Boniecki for advices in Monte Carlo simulations
implementation and for much help in testing and implementation phase of the project.

-------------------------------------------------------------------------

REFERENCES

Components of PyRy3D are based upon the following pieces of scientific literature:
1. Alber F, Förster F, Korkin D, Topf M, Sali A., , Integrating diverse data for structure determination of macromolecular assemblies., Rev Biochem.
2. Sali A, Glaeser R, Earnest T, Baumeister W., , From words to literature in structural proteomics., Nature



