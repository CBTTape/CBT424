# CBT424
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 424 IS FROM BLUE CROSS BLUE SHIELD OF WASHINGTON D.C.     *   FILE 424
//*           AND CONTAINS A COPY OF THEIR 3420 TO 3480 CONVERSION  *   FILE 424
//*           PROGRAM.  THIS FILE IS IN IEBUPDTE SYSIN FORMAT,      *   FILE 424
//*           FOR ADDITIONAL INFORMATION SEE THE MEMBER CALLED      *   FILE 424
//*           INSTALL.                                              *   FILE 424
//*                                                                 *   FILE 424
//*      VETAPE IS A PROGRAM THAT GENERATES AND SUBMITS JOBS        *   FILE 424
//*      TO THE INTERNAL READER TO COPY 3420 VOLUMES TO 3480        *   FILE 424
//*      VOLUMES AND VICE VERSA.                                    *   FILE 424
//*                                                                 *   FILE 424
//*      IT REQUIRES UCC ONE TAPE MANAGEMENT SYSTEM TO RETRIEVE     *   FILE 424
//*      DATA ABOUT THE VOLUMES YOU ARE MIGRATING.  RUNNING AS A    *   FILE 424
//*      STARTED TASK IT ISSUES A REQUEST TO THE OPERATOR TO        *   FILE 424
//*      ENTER A VOLSER OF THE VOLUME TO BE MIGRATED.  FROM THAT    *   FILE 424
//*      IT DETERMINES IF THE VOLUME IS ELGIBLE FOR MIGRATION       *   FILE 424
//*      FROM THE FOLLOWING CRITERIA:                               *   FILE 424
//*                                                                 *   FILE 424
//*       **** SEE FILE 047 FOR A VERSION OF VETAPE THAT            *   FILE 424
//*            SUPPORTS TLMS II RATHER THAN UCC1         ****       *   FILE 424
//*                                                                 *   FILE 424
//*      1. EXPIRATION DATE - IF TAPE DUE TO EXPIRE IN 30 DAYS      *   FILE 424
//*                           OR LESS IT WILL BE BYPASSED.          *   FILE 424
//*                                                                 *   FILE 424
//*      2. DENSITY         - MUST BE STANDARD 6250 BPI.            *   FILE 424
//*                                                                 *   FILE 424
//*      3. CREATING JOBNAME- VOLUMES CREATED BY JOBS USING         *   FILE 424
//*                           CERTAIN UTILITIES OR INTENDED FOR     *   FILE 424
//*                           3420 VOLUMES CAN BE BYPASSED.         *   FILE 424
//*                                                                 *   FILE 424
//*      4. MULTI-FILE TAPES- IF TAPE HAS MULTIPLE DATASETS IT      *   FILE 424
//*                           WILL BE BYPASSED.                     *   FILE 424
//*                                                                 *   FILE 424
//*      IF A VOLUME PASSES THESE CHECKS A TWO STEP JOB IS          *   FILE 424
//*      GENERATED AND SUBMITTED TO THE INTERNAL READER.  THE       *   FILE 424
//*      JOBNAME WILL BE IN THE FORMAT OF JJJJJXX WHERE JJJJJ IS    *   FILE 424
//*      DETERMINED BY YOU AND XX IS THE LAST 2 DIGITS OF THE       *   FILE 424
//*      ORIGINAL VOLSER.  IT WILL DETERMINE FROM THE TMS RECORD    *   FILE 424
//*      THE FOLLOWING:                                             *   FILE 424
//*                                                                 *   FILE 424
//*                   1.  DATASET NAME                              *   FILE 424
//*                   2.  EXPIRATION DATE                           *   FILE 424
//*                   3.  DENSITY                                   *   FILE 424
//*                   4.  CREATING JOB NAME                         *   FILE 424
//*                   5.  NUMBER OF VOLUMES AND SEQUENCE            *   FILE 424
//*                   6.  MUTIPLE DATASET VOLUMES                   *   FILE 424
//*                                                                 *   FILE 424
```
