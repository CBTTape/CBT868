# CBT868
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 868 is from Claudio Mauceri, and contains a program to    *   FILE 868
//*           do a track-by-track compare of two offline DASD       *   FILE 868
//*           packs.                                                *   FILE 868
//*                                                                 *   FILE 868
//*           email:  Claudio.Mauceri@hds.com                       *   FILE 868
//*                                                                 *   FILE 868
//*     Note from Sam Golob:  It seems to me that the packs are     *   FILE 868
//*          not REQUIRED to be offline.  I tested with one pack    *   FILE 868
//*          online and one pack offline.  Since they had the       *   FILE 868
//*          same volser, only one could be online at a time.       *   FILE 868
//*                                                                 *   FILE 868
//*     Version 0.2.0 of DISKCOMP has EAV support.                  *   FILE 868
//*                                                                 *   FILE 868
//*     Version 0.1.0 of DISKCOMP is member DSKCMP01 of this pds.   *   FILE 868
//*                                                                 *   FILE 868
//*     DESCRIPTION:                                                *   FILE 868
//*                                                                 *   FILE 868
//*     Recently we have had a specific necessity, so the           *   FILE 868
//*     attached program has been created.                          *   FILE 868
//*                                                                 *   FILE 868
//*     It is a simple (?) assembler program able to perform a      *   FILE 868
//*     track-by-track compare of two offline dasd packs.           *   FILE 868
//*                                                                 *   FILE 868
//*     Because I believe it could of interest for someone          *   FILE 868
//*     else, I've decided to send it to you to see if it could     *   FILE 868
//*     be suitable for cbttape.                                    *   FILE 868
//*                                                                 *   FILE 868
//*     Its invocation is pretty simple and intuitive, so I'm       *   FILE 868
//*     not sure if further explanations and comments are           *   FILE 868
//*     needed:  (See member SAMPJCL for JCL examples.)             *   FILE 868
//*                                                                 *   FILE 868
//*     *   Invocation:                                             *   FILE 868
//*     *      //step   EXEC PGM=DISKCOMP,                          *   FILE 868
//*     *      //       PARM='unit1,unit2,locyl,hicyl,msgddn'       *   FILE 868
//*     *      //STEPLIB  DD DISP=SHR,DSN=apf.authorized.loadlib    *   FILE 868
//*     *      //msgddn   DD SYSOUT=*                               *   FILE 868
//*     *                                                           *   FILE 868
//*     *    locyl, hicyl and msgddn are optional                   *   FILE 868
//*     *                                                           *   FILE 868
//*     *    locyl defaults to 0                                    *   FILE 868
//*     *    hicyl defaults to highest cylinder on smallest unit    *   FILE 868
//*     *    msgddn defaults to SYSPRINT                            *   FILE 868
//*                                                                 *   FILE 868
```
