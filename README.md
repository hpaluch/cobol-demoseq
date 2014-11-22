# COBOL Sequential files demo

Here is simple example of sequential file handling in Cobol. The program
creates DIAG.DAT sequential file, writes 3 records, reads them back and displaying
output on console.

Note: if you run this program multiple times you should remove existing DIAG.DAT
before this program.

## Setup

You need COBOL compiler. This project has been tested on 
* Microfocus Visual COBOL for Visual Studio Personal Edition	2.2.0
* Microsoft Cobol v 2.20 for DOS

### Microfocus COBOL

You can get Microfocus Cobol Personal Edition freely (registration required)
 from https://www.microfocus.com/product-downloads/vcpe/vcpe22/index.aspx

Note: you don't need Visual Studio (it installs Visual Studio Shell Edition in such case).

Note: I have no luck in Win XP, use Win 7 if you experience install problems.

### Microsoft COBOL

There has been "MICROSOFT COBOL COMPILER" (mscobol.zip) available on
http://www.ibmmainframes.com/downloads.php (however that site recently
changed - now registration is required).
Use it on your own risk (including licensing risk)!

Note: it will run on MS DOS (including emulation) only - there is no longer
DOS support in 64bit Vista/Win7

Ensure that you have MS Cobol in your path. Then use provided compile.bat and run.bat scripts

## Compiling this program

In Microfocus Cobol IDE Use:

* Build -> Build Solution

For Microsoft Cobol run provided bat:

	compile.bat

## Running this program

In Microfocus Cobol IDE Use:

* Start button on Toolbar

For Microsoft Cobol use provided bat:

	run.bat

##Resources

* very good manual for CPM version of Microsoft Cobol (it is similar
  to DOS version described in this project)
  http://bitsavers.informatik.uni-stuttgart.de/pdf/microsoft/cpm/Microsoft_COBOL-80_1978.pdf 
  

