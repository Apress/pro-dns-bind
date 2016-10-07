Pro DNS and BIND
================
ISBN 1-59059-494-0
By Ron Aitchison
Web site http://www.netwidget.net/books/apress/dns
email: ron.aitchison@netwidget.net

INTRODUCTION:

The various example files used in the book are provided as text files in the format 
and order they appear in the book. All files are formatted in UNIX format (lines 
terminate with a single LF) and will generally not display correctly using a windows
text editor e.g. notepad. BIND will however accept either the UNIX standard (single LF) 
or the Windows standard (CR+LF) when reading either the named.conf or zone files. 
The supplied files will therefore work with BIND running on either UNIX or windows.

SUPPLIED FILES:

The files supplied are either complete or fragments (snippets) as they appear in the 
book. Only multiple line examples are provided. The following are not included:

   a. single line examples
   b. command lines
   c. responses to commands
   d. syntax definitions
   e. the SDB API code fragments (only the complete file is provided)

FILE NAMING CONVENTION:

Files are organised under each chapter and have the following name format:
    FCCXXTQ.txt

Where:
  F  - fixed character F

  CC - two digit chapter number

  XX - sequence number of the file as it appears in the chapter

  T  - single character describing the file type may be:
     Z - zone file
     N - named.conf
     C - C source file
     H - C header file
     R - rc.conf (BSD)
     A - httpd.conf (apache)
     D - rndc.conf
     S - shell script

  Q  - single character file qualifer may be:
     P - snippet, fragment or partial file
     F - full file
     E - edited file (removed base-64 material but file otherwise complete)