~~~~~~~~~~~~~~~~

//***FILE 128 IS FROM THE INFORMATION SYSTEMS DEPARTMENT            *   FILE 128
//*           OF THE CHURCH OF JESUS CHRIST OF LATTER-DAY SAINTS.   *   FILE 128
//*                                                                 *   FILE 128
//*           THIS PDS CONTAINS THREE APPLICATIONS :                *   FILE 128
//*           1) ISPF APPLICATION THAT ALLOWS THE ENTRY OF          *   FILE 128
//*              VTAM COMMANDS AND THE VIEWING OF THE               *   FILE 128
//*              RESULTS.                                           *   FILE 128
//*           2) A MVS/XA (2.2) ACTIVITY DISPLAY (BASED ON          *   FILE 128
//*              CHIMP)                                             *   FILE 128
//*           3) A SYSLOG SCAN FACILITY.  THE SYSLOG SCAN           *   FILE 128
//*              FACILITY HAS BEEN TESTED UNDER MVS/XA 2.1.7        *   FILE 128
//*              AND MVS 2.2.0 WITH JES2 2.1.5.  ANY OTHER          *   FILE 128
//*              RELEASES OF MVS OR JES2 MAY REQUIRE PROGRAM        *   FILE 128
//*              MODIFICATIONS AS THE PROGRAM IS DEPENDENT ON       *   FILE 128
//*              MESSAGE NUMBERS.  SEE MEMBER UT017DOC FOR          *   FILE 128
//*              MORE DETAILS.                                      *   FILE 128
//*                                                                 *   FILE 128
//*                 ******************************************      *   FILE 128
//*                 ***                                    ***      *   FILE 128
//*                 *** SUMMARY OF THE MEMBERS IN THIS PDS ***      *   FILE 128
//*                 ***                                    ***      *   FILE 128
//*                 ******************************************      *   FILE 128
//*                                                                 *   FILE 128
//*             ACT                                                 *   FILE 128
//*                MVS ACTIVITY DISPLAY.                            *   FILE 128
//*             APPLVTAM                                            *   FILE 128
//*                OUR VTAMLST MEMBER FOR THE VTAM/ISPF             *   FILE 128
//*                COMMAND FACILITY.                                *   FILE 128
//*             SP1TC014                                            *   FILE 128
//*                THE PROGRAM (ASSEMBLER) FOR THE VTAM/ISPF        *   FILE 128
//*                COMMAND FACILITY.  IT ALLOWS THE ENTRY OF        *   FILE 128
//*                VTAM COMMANDS WITH THE RECEIPT OF THE            *   FILE 128
//*                RESPONSES.  IT HAS MANY SHORT CUTS - "R          *   FILE 128
//*                NODENAME" TO DO A "V                             *   FILE 128
//*                NET,INACT,R,ID=NODENAME" FOR EXAMPLE.            *   FILE 128
//*             SP1UT017                                            *   FILE 128
//*                THE SYSLOG SCAN PROGRAM.                         *   FILE 128
//*             SP1VO00                                             *   FILE 128
//*                THE ISPF PANEL FOR THE VTAM/ISPF COMMAND         *   FILE 128
//*                FACILITY.                                        *   FILE 128
//*             SP1VO00A                                            *   FILE 128
//*                THE ISPF HELP PANEL FOR THE VTAM/ISPF            *   FILE 128
//*                COMMAND FACILITY.                                *   FILE 128
//*             SP10                                                *   FILE 128
//*                THE ISPF MESSAGES MEMBER FOR THE VTAM/ISPF       *   FILE 128
//*                COMMAND FACILITY.                                *   FILE 128
//*             SYSENTER                                            *   FILE 128
//*                A VERY GENERAL PURPOSE ASSEMBLER PROGRAM         *   FILE 128
//*                ENTRY MACRO.  IT SUPPORTS BOTH REENTRANT         *   FILE 128
//*                AND NON-REENTRANT PROGRAMS AND WILL ALSO         *   FILE 128
//*                GETMAIN YOUR WORK AREA ALONG WITH YOUR           *   FILE 128
//*                SAVE AREA.  SEE THE INTERNAL DOCUMENTATION       *   FILE 128
//*                FOR MORE DETAILS.  USED BY BOTH SP1TC014         *   FILE 128
//*                AND SP1UT017.                                    *   FILE 128
//*             SYSRETRN                                            *   FILE 128
//*                THE RETURN MACRO CORRESPONDING TO                *   FILE 128
//*                SYSENTER.  IT USES GLOBAL VARIABLES SET IN       *   FILE 128
//*                SYSENTER TO DETERMINE WHETHER OR NOT TO          *   FILE 128
//*                FREEMAIN THE SAVE AND WORK AREAS.  SEE THE       *   FILE 128
//*                INTERNAL DOCUMENTATION FOR MORE DETAILS.         *   FILE 128
//*             UT017DOC                                            *   FILE 128
//*                DOCUMENTATION (FBA FORMAT) FOR THE SYSLOG        *   FILE 128
//*                SCAN FACILITY.                                   *   FILE 128
//*                                                                 *   FILE 128
~~~~~~~~~~~~~~~~

