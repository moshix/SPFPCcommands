<h1>SPF/PC Line and Panel Commands</h1>

<BR><BR>
<h2>SPFPC Select List Primary Commands - File Manager</h2>
<BR>
<pre>  
  Select
  Browse
  Edit
  Print
  Rename
  Delete
  Move
  Copy
  Information (display properties)
  Go (execute program or batch file)
  Tree (create recursive sub-list)
  User (apply user command)
  Convert (one format to another)
  Exclude (prune list)
 </pre>
  <BR><BR>
  
<h2>SPFPC Select List Line Commands - File Manager</h2>
<BR>
<pre>
  B  Browse a file
  C  Copy a file
  D  Delete a file
  E  Edit a file
  G  Execute program or batch file
  I  Display information about a file
  K  Convert file format
  M  Move a file
  N  New, select file with new SPF task
  P  Print a file
  R  Rename a file
  S  Select a file
  T  Create a recursive sublist
  U  Apply a user command to a file
  X  Exclude a file from the list
</pre><BR>
  
<h2>SPFPC Edit Commands</h2>
<BR>
<pre>
  &          Keep command displayed after it is executed
  :          Treat primary command as line command
  AUTOLIST   Create a source listing after END or [F3]
  AUTONUM    Renumber STD, COBOL, or BASIC upon save
  AUTOSAVE   Turn autosave on/off
  BOT        Position to bottom of file
  BOUNDS     Set/reset current bounds
  CANCEL     Cancel or disregard edit changes
  CAPS       Turn upper case conversion on or off
  CHANGE     Change a string of data
  CHARSET    Set the character set to EBCDIC or ASCII
  COLORMAP   Bind program colorization file to file type
  COMPARE    SUPERC compare current file to external file
  COPY       Copy a file into the current file
  COUNTSAVE  Set number of ENTERs before SAVE (also SAVECOUNT)
  CREATE     Create a new file
  CUT        Cut lines marked with CC or MM to cut buffer
  DATA       Insert data at the current cursor position
  DEFINE     Enable/disable specific macros by name
  DELETE     Delete a group of lines
  DOWN       Scroll view of file down
  END        End edit session; return to prior menu
  ERRORFILE  Insert compiler errors as message lines
  EXCLUDE    Exclude lines from viewing
  FIND       Find a string of data
  FLIP       Invert sense of excluded lines
  HEX        Turn HEX display on or off
  IMACRO     Set initial macro name in the edit profile
  LCOMMAND   Turn line command field ON or OFF
  LEFT       Scroll view of file left
  LEVEL      Set/reset modification level
  LOCATE     Locate a given line
  LRECL      Set logical record length
  MODEL      Access program source templates
  MOVE       Move a file into the current file
  NUMBER     Turn numbering mode on or off
  PASTE      Insert lines from cut buffer
  PROFILE    Display current profile information
  RCHANGE    Repeat last CHANGE command
  RECOVERY   Set UNDO support ON or OFF
  REDO       Redo the last alteration which was undone
  RENUM      Renumber the current file
  REPLACE    Replace a file on disk
  RESET      Reset all pending line commands
  RFIND      Repeat last FIND command
  RIGHT      Scroll view of file right
  SAVE       Save a file on disk
  SAVECOUNT  Set number of ENTERs before SAVE (also COUNTSAVE)
  SCOPY      Copy the selection to the clipboard
  SCREATE    Create a new file from the selection
  SCUT       Copy selection to clipboard, then delete it
  SDELETE    Delete the selection
  SORT       Sorts records or columns
  SPASTE     Paste contents clipboard at cursor position
  SPRINT     Print the current selection
  SREPLACE   Replace an existing file with the selection
  STATS      Turn stats on or off
  STOLOWER   Convert selection to all lower case chars
  STOUPPER   Convert selection to all upper case chars
  SXCLUDE    Exclude all lines touched by the selection
  TABS       Turn tabs on or off
  TOP        Position to top of file
  UNDO       Undo the last alteration
  UNNUM      Reset numbers to blanks
  UP         Scroll view of file up
  XMACRO     Sets exit macro name in the edit profile
</pre><BR>  
  
<h2>SPFPC Edit Line Commands</h2>
<BR>
<pre>

  <     Data shift left.
  <<    Block data shift left.
  >     Data shift right.
  >>    Block data shift right.
  (     Column shift left.
  ((    Block column shift left.
  )     Column shift right.
  ))    Block column shift right.
  A     After.
  B     Before.
  BNDS  Display/set bounds.
  C     Copy.
  CC    Block copy.
  COLS  Display columns.
  D     Delete.
  DD    Block delete.
  F     Display first excluded line(s).
  I     Insert.
  L     Display last excluded line(s).
  LC    Set a line to lowercase.
  LCC   Set a block of lines to lowercase.
  M     Move.
  MM    Move block.
  MASK  Display/set mask.
  MD    Make a NOTE or MSG line into a data line.
  MDD   Make a block of NOTE or MSG lines into data lines.
  O     Overlay.
  OO    Overlay block.
  R     Repeat.
  RR    Repeat block.
  S     Show structure excluded line(s).
  TABS  Display/set tabs.
  TE    Text entry.
  TF    Text flow.
  TJ    Text join.
  TS    Text split.
  UC    Set a line to uppercase.
  UCC   Set a block of lines to uppercase.
  X     Exclude.
  XX    Exclude block.
  .     Label assignment.
 </pre><BR> 
  
<h2>SPFPC ISREDIT Macro Commands</h2>
<BR>
  <pre>
  AUTOLIST       Set or retrieve the AUTOLIST profile variable.
  AUTONUM        Set or retrieve the AUTONUM profile variable.
  AUTOSAVE       Set or retrieve the AUTOSAVE profile variable.
  BLKSIZE        Retrieves the current block size.
  BOUNDS         Set or retrieve the BOUNDS profile variable.
  CANCEL         Cancels editing of current file without saving changes.
  CAPS           Set or retrieve the CAPS profile variable.
  CHANGE         Searches for a string and replaces it with another string.
  CHANGE_COUNTS  Retrieves the count set by the last issued CHANGE command.
  CHARSET        Set or retrieve the CHARSET profile variable.
  COLORMAP       Set or retrieve the COLORMAP profile variable.
  COMPARE        Compare an external file to the current edit file.
  COPY           Copies another file into the current file.
  CREATE         Specifies a new file is to be created.
  CURSOR         Sets or retrieve line and col number of current cursor pos.
  CUT            Copy/Move block of lines to clipboard.
  DATA           Insert/overtype data at the current cursor position.
  DATA_CHANGED   Retrieves the current data changed status.
  DATA_WIDTH     Returns data width of current file.
  DATASET        Retrieves the name of the current file.
  DEFINE         Enable/disable specific macros by name.
  DELETE         Removes one or more lines from the file you are editing.
  DISPLAY_COLS   Retrieves the first and last display columns.
  DISPLAY_LINES  Retrieves line numbers of first and last displayed lines.
  DOS            Executes an operating system command.
  DOWN           Displays the next frame of lines in the file.
  EDIT           Edit another file without leaving the current file.
  END            Ends the edit session.
  ERRORFILE      Merge compiler error messages with program source.
  EXCLUDE        Allows you to temporarily exclude lines from view
  EXCLUDE_COUNTS Sets count of strings and lines excluded by last EXCLUDE.
  FIND           Searches a file for a specified string.
  FIND_COUNTS    Sets count of strings and lines found by last FIND or RFIND.
  FLOW_COUNTS    Sets count of original and resulting lines created by last TFLOW.
  HEX            Set or retrieve the HEX profile variable.
  HOLD_LOCK      Hold the lock on the file.
  IMACRO         Set or retrieve the IMACRO profile variable.
  INSERT         Inserts one or more null lines for data entry in current file.
  LABEL          Sets or retrieves the label on a specific line.
  LCOMMAND       Set or retrieve the LCOMMAND profile variable.
  LEFT           Displays currently undisplayed columns to the left.
  LEVEL          Set or retrieve the current modification level.
  LINE           Sets or retrieves data from a specified line.
  LINE_AFTER     Inserts line of text after a specified line in current file.
  LINE_BEFORE    Inserts line of text before a specified line in current file.
  LINENUM        Retrieves the relative line number of a labeled line.
  LOCATE         Makes line matching search criteria the top display line.
  LRECL          Returns the logical record length of the current file.
  MACRO          Identifies a macro, its parameters, and processing conditions.
  MACRO_LEVEL    Retrieves the nesting level of the current macro.
  MASKLINE       Set or retrieve the MASKLINE profile variable.
  MEMBER         Retrieves the name of the current file.
  MODEL          Insert MODEL syntax entry applicable to this file type.
  MOVE           Moves another file into the current file.
  NOTE           Set or retrieve the NOTE profile variable.
  NUMBER         Set or retrieve the NUMBER profile variable.
  PASTE          Insert lines from clipboard at A or B line.
  PROCESS        Controls when pending line commands and data are processed.
  PROFILE        Displays the current edit profile.
  RANGE_CMD      Identifies first line command captured by PROCESS RANGE.
  RCHANGE        Repeats the most recent CHANGE command.
  READ_ONLY      Set the file to read only.
  RECFM          Retrieves the record format of the current file.
  RECOVERY       Allow UNDO.
  REDO           Redo an edit transaction after an undo.
  RENUM          Turns NUMBER mode on and renumbers lines.
  REPLACE        Replaces an existing file with all or part of the current file.
  RESET          Restores the status of data lines and removes special lines.
  RFIND          Repeats the most recent FIND command.
  RIGHT          Displays currently undisplayed columns to the right.
  SAVE           Saves the current file without terminating the edit session.
  SAVECOUNT      Set or retrieve the SAVECOUNT profile variable.
  SAVE_ENABLED   Set the file to allow SAVE.
  SCAN           Sets or retrieves the SCAN mode.
  SCOPY          Copy the current selection to the clipboard.
  SCREATE        Create a new file with the current selection contents.
  SCUT           Copy current selection to clipboard, then delete selection.
  SDELETE        Delete the current selection.
  SEEK           Same as FIND but does not expose excluded lines.
  SEEK_COUNTS    Sets count of strings and lines found by last SEEK.
  SHIFT (        Moves data left using column shift logic.
  SHIFT )        Moves data right using column shift logic.
  SHIFT <        Moves data left using data shift logic.
  SHIFT >        Moves data right using data shift logic.
  SORT           Rearranges data or cols of data in a specified order.
  SPASTE         Insert the clipboard contents at the current cursor position.
  SREPLACE       Replace a file with the current selection contents.
  STATS          Sets or retrieves the current STATS mode.
  STOLOWER       Convert all alpha characters in the selection to lower case.
  STOUPPER       Convert all alpha characters in the selection to uppercase.
  SUBMIT         Only supported if MVS access component purchased.
  SXCLUDE        Exclude all lines touched by the current selection.
  TABS           Set or retrieve the TABS profile variable.
  TABSLINE       Set or retrieve the TABSLINE profile variable.
  TENTER         Provides blank screen space for text entry.
  TFLOW          Composes a block of text within designated BOUNDS.
  TJOIN          Joins current line with following line; inverse of TSPLIT.
  TSPLIT         Splits a line so that additional text can be inserted.
  UNDO           Undo the last edit operation.
  UNNUM          Turns NUMBER mode off and removes line numbers.
  UP             Displays the previous frame of lines in the file.
  USER_STATE     Saves or restores user state information.
  XMACRO         Set or retrieve the XMACRO profile variable.
  XSTATUS        Sets or retrieves exclude status of specified data line.
</pre><BR>  
  
<h2>SPFPC ISPEXEC COMMANDS</h2>
<BR>
  <pre>
  ADDPOP         Display a panel as a sub-window on the current panel.
  BROWSE         Browse a file (or files).
  CONTROL        Set dialog processing options.
  DISPLAY        Display a panel or table.
  EDIT           Edit a file (or files).
  GETMSG         Get elements of a message.
  PDSCREATE      Create a PDS file format file.
  PDSDELETE      Delete a member from a PDS.
  PDSEXPORT      Export a member from a PDS to a file.
  PDSIMPORT      Import a file to a PDS into a member.
  POPUPMENU      Display a GUI popup menu on the panel.
  PRNCLOSE       Close the default printer.,
  PRNOPEN        Open the default printer and set the headings.
  PRNRECORD      Print a record on the default printer.
  REMPOP         Remove the sub window displayed with ADDPOP.
  SELECT         Invoke a function or display a menu panel.
  SETMSG         Set message to be displayed on next panel.
  TBADD          Add a row to a table.
  TBBOTTOM       Position to the bottom of a table.
  TBCLOSE        Close a table; write to disk if applicable.
  TBCREATE       Create a new table.
  TBDELETE       Delete a row from a table.
  TBDIRCREATE    Create a special table to contain directory entries.
  TBDIRDISPL     Display a table of directory entries using SPF/Pro defaults.
  TBDIRPOPULATE  Populate a table of directory entries from a supplied file mask.
  TBDISPL        Display a table.
  TBEND          Close a table; don't write to disk.
  TBERASE        Delete a disk based table.
  TBEXIST        Determine if keyed table row exists.
  TBGET          Load dialog vars from a table row.
  TBMOD          Update a keyed table row.
  TBOPEN         Open a disk based table for access.
  TBPUT          Update a non-keyed table row.
  TBQUERY        Get information about a particular table.
  TBSARG         Set search args for TBSCAN or TBDISPL.
  TBSAVE         Write a disk based table without closing.
  TBSCAN         Search a table for a particular row.
  TBSKIP         Position in a table and retrieve the row.
  TBSORT         Sort a table by field(s).
  TBSTATS        Obtain statistical information about a table.
  TBTOP          Position to the top of a table.
  TBVCLEAR       Clear variables in the current row.
  VGET           Copy non-function pool var to function pool.
  VPUT           Copy function pool var to non-function pool.
</pre><BR>  
  
<h2>ZVARIABLES</h2>
<BR>
<pre>
  Name    Service  Ver Pool Type Len   Description
 -------- -------- --- ---- ---- ---  -------------------------------------
 Z        general  2.3 shr  non    0  null variable, used as a placeholder
 ZACCTNUM general  3.3 shr  non   40  logon account number (MVS type)
 ZAPLCNT  general  2.3 shr  non    4  APL usage count per logical screen
 ZAPPLID  general  2.3 shr  non    8  identifier application
 ZASPECT  PRINTG   2.3 func in     4  aspect ratio of printed output
 ZCMD     panel    2.3 func      256  command input field
          LMMDISP  2.3 func out  256  member list primary command field
 ZCOLORS  screen   2.3 shr  non    4  supported number of colors (1 or 7)
 ZCONT    panel    2.3                next continuation panel name
 ZCS      general  3.3 shr  non    5  NLS symbol for currency
 ZCURFLD  DTL      3.1 func out    8  field/column with cursor on exit
 ZCURINX  DTL      3.1 func out    8  table display row number with cursor
 ZCURPOS  DTL      3.1 func out    4  relative field position of cursor
 ZDATE    date     2.3 shr  non    8  current date, format depends on
                                      current national language
 ZDATEF   date     2.3 shr  non    8  current national language date format
                                      DD = day, MM = month, YY = year
                                      and national language delimiter
 ZDATEFD  date     2.3 shr  non    8  date format as described for ZDATEF,
                                      but w/national language convention
 ZDAY     date     2.3 shr  non    2  2 character day of month
 ZDBCS    screen   2.3 shr  non    3  DBCS capability (YES or NO)
 ZDECS    general  3.3 shr  non    1  NLS character to separate decimals
 ZDEVNAM  PRINTG   2.3 func in     8  device name
 ZDLBLKSZ LMDLIST  3.1 func out    5  size of block
 ZDLCDATE LMDLIST  3.1 func out   10  date member was created
 ZDLDEV   LMDLIST  3.1 func out    8  type of device
 ZDLDSORG LMDLIST  3.1 func out    4  organization of data set
 ZDLDTYPE LMDLIST  3.1 func out    7  type of data set (eg 'PDS' 'LIBRARY')
 ZDLEDATE LMDLIST  3.1 func out   10  date the data set expires
 ZDLLRECL LMDLIST  3.1 func out    5  length of logical record
 ZDLNEXT  LMDLIST  3.1 func out    3  number of used extents
 ZDLPAGES LMDLIST  3.1 func out    6  number of allocated pages
 ZDLPUSED LMDLIST  3.1 func out    3  percent of PDSE used or blanks
 ZDLRDATE LMDLIST  3.1 func out   10  last reference data
 ZDLRECFM LMDLIST  3.1 func out    5  format of record
 ZDLSIZE  LMDLIST  3.1 func out    6  number of tracks in data set
 ZDLUSED  LMDLIST  3.1 func out    3  percent of tracks used
 ZDLVOL   LMDLIST  3.1 func out    6  volume serial
 ZDSN     LMMDISP  2.3 func out   44  first data set for member list
          BR/EDIF  2.3 func out   54  data name on BRIF/EDIF title line
 ZEDBDSN  EDIT     2.3 func i/o   44  edit recovery backup data set name
 ZEDROW   EDIT     2.3 func i/o    4  edit recovery table row number
 ZEDTDSN  EDIT     3.1 func i/o   44  edit recovery target data set name
 ZEDTMEM  EDIT     3.1 func i/o    8  edit recovery target member name
 ZEDTRD   EDIT     3.1 func i/o    6  edit recovery target volser
 ZEDUSER  EDIT     3.1 func i/o    *  edit recovery user data table ext.
 ZEIBSDN  EDIF     2.3 func i/o   54  EDIF edit recovery backup data set
 ZEIROW   EDIF     2.3 func i/o    4  EDIF edit recovery table row number
 ZEITDSN  EDIF     2.3 func i/o   54  EDIF edit recovery target data set
 ZEIUSER  EDIF     2.3 func i/o    *  EDIF edit recovery user data tbl ext.
 ZENVIR   general  2.3 shr  non   32  environment information, positions:
                                      -  1 to 8 = product, version, release
                                      -  9 to 16 = operating system name
                                                   (MVS or MVS/XA)
                                      -  17 to 24 = operating system mode
                                                    (TSO or BATCH)
                                      -  25 to 32 = reserved (blanks)
 ZERRALRM error    2.3 func out    3  indicates message alarm (YES or NO)
 ZERRHM   error    2.3 func out    8  error message help panel name
 ZERRLM   error    2.3 func out   78  long error message text
                   3.2           512
 ZERRMSG  error    2.3 func out    8  error message ID
 ZERRSM   error    2.3 func out   24  short error message text
 ZERRTYPE error    3.1 func out    8  error message type
 ZERRWIND error    3.1 func out    6  error message window type
 ZFAMPRT  PRINTG   2.3 func non    4  family printer type
 ZFKA     screen   3.1 shr  non    8  function key area (long, short, no)
 ZGE      terminal 3.3 shr  non    3  graphic escape order support
 ZGRPLVL  LMHIER   2.3 func out    8  hierarchy level of library (group)
 ZGRPNME  LMHIER   2.3 func out    8  library group name
 ZHILITE  screen   2.3 shr  non    3  extended highlighting (YES or NO)
 ZHINDEX  panel    2.3                first index panel name
 ZHTOP    panel    2.3                top panel name
 ZIND     panel    2.3                specify an index page (YES)
 ZISPFRC  general  2.3 shr  in     8  return code from ISPSTART dialog
 ZJDATE   date     2.3 shr  non    6  day-of-year date(julian format yy.ddd)
 ZKEYS    PF keys  2.3 prof out    4  number of PF keys
 ZKEYHELP keys     3.1 any  in     8  keys definition help panel name
 ZLANG    general  2.3 prof non    8  language of current session
 ZLCDATE  LMF      2.3 func i/o    8  member create date (national format)
 ZLCNORC  LMF      2.3 func i/o    4  member current record count
 ZLINORC  LMF      2.3 func i/o    4  member creation record count
 ZLLIB    LMF      2.3 func out    4  library concatenation sequence (1 - 4)
 ZLMDATE  LMF      2.3 func i/o    8  last modified date (national format)
 ZLMEMBER LMMDISP  2.3 func out    8  current member
 ZLMNORC  LMF      2.3 func i/o    4  modified record count
 ZLMOD    LMF      2.3 func i/o    4  modification level (0 to 99)
 ZLMTIME  LMF      2.3 func i/o    5  last modified time (format hh:mm)
 ZLOGNAME LOG      2.3 shr  non   44  full log data set name
 ZLOGO    general  3.1 shr  non    3  bypass LOGO panel (YES or NO)
 ZLOGON   general  2.3 shr  non    8  TSO logon procedure stepname
 ZLPDSUDA LMMDISP  2.3 func out   62  PDS directory user data information
 ZLSTLPP  LIST     2.3 shr  non    4  lines per page in list data set
 ZLSTNAME LIST     2.3 shr  non   44  full list data set
 ZLSTNUML LIST     2.3 shr  non    4  current list data set lines written
 ZLSTTRUN LIST     2.3 shr  non    4  list record length truncation value
 ZLUSER   LMF      2.3 func i/o    8  userid that last modified member
 ZLVERS   LMF      2.3 func i/o    4  member version number (1 to 99)
 ZMLCOLS  LMMDISP  2.3 func out   80  member statistics column headings
 ZMLCR    LMMDISP  2.3 func out    4  member list top member rel. number
 ZMLTR    LMMDISP  2.3 func out    4  member list number of members
 ZMONTH   date     2.3 shr  non    2  2 character month of year
 ZPARENT  panel    2.3                parent menu name
 ZPFCTL   PF keys  2.3 prof i/o    5  PFSHOW command authorization
 ZPFFMT   PF keys  2.3 prof i/o    4  PF key format (displayed per line)
 ZPFLnn   PF keys  2.3 prof i/o    8  PF key labels, for display
 ZPFSET   PF keys  2.3 prof i/o    4  PF key range set shown
 ZPFSHOW  PF keys  2.3 prof i/o    4  PFSHOW command status
 ZPFnn    PF keys  2.3 prof i/o <256  PF key definition value
 ZPLACE   general  2.3 prof i/o    7  command line place (ASIS or BOTTOM)
 ZPREFIX  general  2.3 shr  non    8  prefix of TSO user
 ZPRIKEYS PF keys  2.3 prof i/o    4  primary PF keys (LOW or UPP)
 ZPRIM    panel    2.3                panel is a primary option menu (YES)
 ZPROFAPP general  2.3 prof in     8  application profile extension table
 ZSCBR    scroll   2.3 prof i/o    4  scroll amount for BROWSE
 ZSCED    scroll   2.3 prof i/o    4  scroll amount for EDIT
 ZSCML    scroll   2.3 prof i/o    4  scroll amount for member lists
 ZSCREEN  screen   2.3 shr  non    1  logical screen number (1, 2, 3, or 4)
 ZSCREEND screen   2.3 shr  non    4  screen depth available for dialog use
 ZSCREENW screen   2.3 shr  non    4  screen width available for dialog use
 ZSCRMAXD screen   2.3 shr  non    4  maximum screen depth available
 ZSCRMAXW screen   2.3 shr  non    4  maximum screen width available
 ZSCROLLA scroll   2.3 shr  out    4  scroll amount value (PAGE, MAX, nnn)
 ZSCROLLN scroll   2.3 shr  out    4  scroll number of rows
 ZSCROLLD scroll   2.3 any  in     4  scroll default for dynamic areas
 ZSEL     panel    2.3                truncated command input field
 ZSPLIT   screen   2.3 shr  non    3  split-screen mode (YES or NO)
 ZSTDYEAR date     3.3 shr  non    4  four character year (yyyy)
 ZSYSID   general  3.3 shr  non    8  SYS1.PARMLIB(IEASYSxx) SYSNAME
 ZTDADD   tbldsply 2.3 func out    3  add rows for scroll request (YES¦NO)
 ZTDAMT   tbldsply 2.3 func out    4  number of rows needed for scroll
 ZTDLROWS tbldsply 2.3 func in     6  number of logical table rows
 ZTDLTOP  tbldsply 2.3 func in     6  logical table row of physical top
 ZTDMARK  tbldsply 2.3 any  in <scrwid bottom-of-data marker text
 ZTDMSG   tbldsply 2.3 any  in     8  top-row-displayed message ID
 ZTDRET   tbldsply 2.3 func in     8  scroll return feature
 ZTDROWS  tbldsply 2.3 func out    6  number of table rows after display
 ZTDSCRP  tbldsply 2.3 func i/o    6  top row CRP after scroll
 ZTDSELS  tbldsply 2.3 func out    4  number of selected table rows
 ZTDSIZE  tbldsply 2.3 func out    4  number of sets in scrollable area
 ZTDSRID  tbldsply 2.3 func out    6  top row rowid after scroll
 ZTDTOP   tbldsply 2.3 func out    6  display top row number (CRP)
 ZTEMPF   ftailor  2.3 shr  non   44  temporary data set for file tailoring
 ZTEMPN   ftailor  2.3 shr  non    8  temporary data set DDname
 ZTERM    terminal 2.3 prof out    8  terminal type (defined by option 0.1)
 ZTERMCID terminal 3.3 shr  non    5  CCSID coded character set terminal ID
 ZTERMCP  terminal 3.3 shr  non    4  CECP support code page
 ZTERMCS  terminal 3.3 shr  non    4  CECP support character set
 ZTHS     general  3.3 shr  non    1  NLS character to separate thousands
 ZTIME    time     2.3 shr  non    5  current time (in format hh:mm)
 ZTS      general  3.3 shr  non    1  NLS character to separate time
 ZTSICMD  general  3.3 shr  non  32k  ISPF invocation command string
 ZTSSCMD  general  3.3 shr  non  32k  ISPF invocation cmnd, SELECT portion
 ZUP      panel    2.3                next panel up/backwards (parent)
 ZUSER    general  2.3 shr  non    8  user ID
 ZVERB    general  2.3 shr  out    8  command table verb (from SETVERB)
 ZWINTTL  general  3.1 any  in    N/A window title for pop-up window frame
 ZYEAR    date     2.3 shr  non    2  2 character year
 </pre><BR>
 
 
<h2>SPFPC REXX Special Variables</h2>
<BR>
<pre>

 RC        Return code 0 = success <> 0 error occured
 RESULT    Contains returned value from called routine
 SIGL      Contains procedure name and line number of calling function
           whenever a control flow jump is made via CALL or SIGNAL.
</pre><BR>           
           
<h2>SPFPC REXX Trace Processing</h2>
<BR>
<pre>
   TRACE A  /* TRACE ALL CLAUSES   */
   TRACE C  /* TRACE COMMANDS      */
   TRACE E  /* TRACE ERRORS        */
   TRACE F  /* TRACE FAILURE       */
   TRACE I  /* TRACE INTERMEDIATES */
   TRACE L  /* TRACE LABELS        */
   TRACE N  /* TRACE NORMAL        */
   TRACE O  /* TRACE OFF           */
   TRACE R  /* TRACE RESULTS       */
   TRACE S  /* TRACE SCAN          */

  Trace output:

   nn ccc    DO WHILE (position <= LENGTH(filename))

   Where:
   nn        Represents the line number of the REXX statement being executed.
   ccc       The next three characters identify the trace line as one of the
             following:

             *-*  source code
             +++  trace message
             >>>  result of an expression
             >.>  value assigned to a placeholder
             >V>  variable contents of a string
             >L>  literal string
             >F>  function call string
             >P>  prefix operation string
             >O>  operation on two terms string
             >C>  compound variable string

   During interactive tracing, after each line of output the user can enter
   any valid REXX statement to be executed immediately enabling
   variables to be modified with an assignment, variables to be
   queried with a SAY statement and execution to be terminated by the use of
   an explicit EXIT statement if, say, a loop is detected.

   If during testing of a procedure, a loop occurs and tracing is not active,
   pressing Control/Break interrupts the procedure, typing exit terminates
   the procedure.
</pre><BR>
  
  
<h2>SPFPC REXX Instrinsic Instructions</h2>
<BR>
<pre>
 ADDRESS    set the destination for external commands
 ARG        retrieve parameters passed to function
 CALL       invoke a function
 DO         execute a block of instructions
 DROP       restore a variable to an uninitialized state
 EXIT       end program immediately
 IF         modify control flow based on condition
 INTERPRET  execute instructions stored in a variable
 ITERATE    jump to the top of a DO loop from middle
 LEAVE      exit a DO loop immediately
 NOP        does nothing (use as placeholder)
 NUMERIC    modify how arithmetic processing is performed
 PARSE      parse a string under control of a template
 PROCEDURE  control scope of variables
 PULL       read a line from the TTY keyboard
 RETURN     end a function, optionally return a value
 SAY        write a line to the TTY screen
 SELECT     multiple condition list (aka CASE)
 SIGNAL     set error trapping conditions
 TRACE      trace REXX interpreter actions
  
</pre><BR>
  
  
<H2>SPFPC REXX Built-in Functions</h2>
<BR>
<pre>

 ABBREV     return TRUE/FALSE, is short string part of long string?
 ABS        return the absolute value of a number without a sign
 ADDRESS    return the name of the external command processor
 ARG        return the parameters passed to a function
 BITAND     return result of logically ANDed bit strings
 BITOR      return result of logically ORed bit strings
 BITXOR     return result of logically XORed bit strings
 B2X        return hex char string, input binary char string
 CENTER     return base string padded on left and right to center
 CENTRE     same as CENTER
 CHARIN     read a string from an external file
 CHAROUT    write a string to an external file
 CHARS      return number of chars remaining unread in external file
 COMPARE    return TRUE/FALSE, do strings compare?
 CONDITION  return current error condition (see CALL and SIGNAL)
 COPIES     returns string catenated to self N times
 C2D        returns decimal value, input char string
 C2X        returns hex char string, input char string
 DATATYPE   returns data type, or TRUE/FALSE on data type test
 DATE       returns the date
 DELSTR     returns substring after deleting at Nth char for N chars
 DELWORD    returns substring after deleting at Nth word for N words
 DIGITS     returns the current setting of the NUMERIC digits value
 D2C        returns char value, input decimal value
 D2X        returns hex string, input decimal value
 ERRORTEXT  returns the text associated with a particular error number
 FORM       returns the current setting of NUMERIC form value
 FORMAT     formats a number (rounds if necessary)
 FUZZ       returns the current setting of the NUMERIC fuzz value
 INSERT     returns superstring comprised of base plus insert strings
 LASTPOS    returns position of last little string in big string
 LEFT       returns substring starting at 1 for N
 LENGTH     returns the length of string
 LINEIN     reads one record from an external file
 LINEOUT    writes one record to an external file
 LINES      returns TRUE/FALSE, any unread lines in external file?
 MAX        returns largest number of a set of numbers
 MIN        returns smallest number of a set of numbers
 OVERLAY    overlays one string with another
 POS        returns position of first little string in big string
 RANDOM     returns a random number from a range
 REVERSE    returns string with chars reordered right to left
 RIGHT      returns N chars from right end of string
 SIGN       returns the sign of a number
 SOURCELINE returns number of lines or a specific line of a REXX proc
 SPACE      set specific number of blanks (or other char) between words
 STREAM     return state info on a file, also open/close/seek
 STRIP      strip leading and/or trailing blanks (or other char) from string
 SUBSTR     returns substring at N for N chars
 SUBWORD    returns subword at N for N words
 SYMBOL     returns the state of a var, undefined, defined, or literal
 TIME       returns the time
 TRACE      returns or current setting sets TRACE
 TRANSLATE  returns translated string, char for char by table
 TRUNC      returns a specified decimal precision derivitive of a number
 VALUE      returns or set the value of an environment variable
 VERIFY     verify presence or absence of chars within a string
 WORD       returns the Nth word in a string
 WORDINDEX  returns the char position of the Nth word in a string
 WORDLENGTH returns the length of the Nth word in a string
 WORDPOS    returns the word number after search for a word in a string
 WORDS      returns the number of words in a string
 XRANGE     returns full range of codes between start and end char/num
 X2B        returns binary char string, input hex char string
 X2C        returns ASCII (or EBCDIC) char string, input hex char string
 X2D        returns decimal value, input hex char string

</pre><BR>
  
  
<h2>SPFPC Intrinsic Commands</h2>
<BR>
<pre>

 CMD
 CMDNOCLR
 CRETRIEV
 CURSOR
 DOS
 EOF
 FF
 FSPLIT
 HELP
 LPRINT
 LPRINTER
 LPRT
 OS2
 PANELID
 PFSHOW
 PRINT
 RETRIEVE
 SCREEN
 SPLIT
 SPLITH
 SPLITV
 STACKDIS
 SWAP
 VSPLIT
</pre><BR> 
 
<h2>Typical PF Key Settings</h2>
<BR>
<pre>
  3270   PC         Command      Does
  -----  ---------  -----------  ---------------------------------------------------------
  PF01   F1         HELP         Call SPFPC Built-In Help Library
  PF02   F2         SPLIT        Split Screen at current line into 2 browse/edit sessions
  PF03   F3         END          End browse/edit session (does not save)
  PF04   F4         SWAP         Swap to other screen
  PF05   F5         RFIND        Repeat Find
  PF06   F6         RCHANGE      Repeat Change
  PF07   F7         UP           Scroll by page setting towards beginning of text
  PF08   F8         DOWN         Scroll by page setting towards end of text
  PF09   F9         LEFT         Scroll screen towards begining of line (column 1)
  PF10   F10        RIGHT        Scroll screen towards end of line
  PF11   F11        SAVE         Save text
  PF12   F12        RETRIEVE     Retrieve previous commands

  PF13 = <Shift>F1  SCUT         Cut selected text to clipboard
  PF14 = <Shift>F2  SCOPY        Copy selected text to clipboard
  PF15 = <Shift>F3  SPASTE       Paste clipboard starting at current cusor position
  PF16 = <Shift>F4  SCREATE      Create new file with selected text
  PF17 = <Shift>F5  SREPLACE     Replace/create file with selected text
  PF18 = <Shift>F6  STOUPPER     Convert selected text to upper case
  PF19 = <Shift>F7  STOLOWER     Convert selected text to upper case
  PF20 = <Shift>F8  SXCLUDE      Exclude (hide) selected text
  PF21 = <Shift>F9  SDELETE      Delete selected text
  PF22 = <Shift>F10 BACKBOX.SPF  Calls REXX macro to create line box
  PF23 = <Shift>F11 Right        Scroll screen right
  PF24 = <Shift>F12 RETRIEVE     Redisplay previous primary commands
  </pre><BR>  
  
  
<h2>SPF/PC Features</h2>
<BR>
<pre>
Auto source code backup
Auto save during edit
Background/Foreground? compiler and utility support
Edit small or large files (have edited 4 million line data files)
Edit ASCII and EBCDIC text files
Code Folding
Command Line Interface (CLI)
File browser with keyword colorization
File manager
File conversion utilities
Full COBOL source code support (Microsoft, Micro Focus, Realia)
Hex editor
IBM (3270) and PC command keys
IBM ISPF Panel (ASCII and EBCDIC) , Dialog, and REXX (SAA 2) Interpreter
IBM Dialog test facility with Panel, Function, Table testing with variable tracing
ISPEXEC, ISREDIT, TABLE and ZVAR support
Keyboard equivalents provided for all mouse operations
Language line numbering support
Language profile support
Line, column and bounds oriented copy, cut, data shift, find, paste, sort with picture strings
Line lengths (records) up to 64,000 characters in fixed or variable formats
Line exclude, change, find, flip, locate, not-exclude
Merge error files created by compilers into source code as notes (type of comment)
Mulitlevel Undo and Redo
Multiple sequential complex command execution - repeatable with exclude and not-exclude abilities
Partitioned data set (PDS) emulation
Print file, screen or selected text
REXX/2 (IBM) macro language - can use other languages as well
Simple and advanced text/file find/replace (literally search through 10,000 files for text)
Sort file lists and text/data
Sort A-Z, Z-A, bounding by columns, line labels etc.
Split screen (horizontal and vertical)
SuperC? file comparison
Superlist support
Support for MDODS/Linux?/Windows? EOL and EOF markers
User enhancements - add, create, modify dialogs, functions, menus and screens
User defineable fonts
User defineable editor color schemes including several 3270 schemes
User defineable file profiles including EOL, EOF, Line Length etc.
User defineable cursor, half page and page scrolling
User switchable editor line numbers or not
User defineable keyboard and keyboard macros
User modifiable help system
Many more features
  </pre><BR>  
  
<h2>SPFPC Start-up Parameters (CLI)</h2>
<BR>
<pre>

   Invoke SPFPC with parameters to bypass the Primary Option Panel and go
   directly to a specific option:

   SPF [filename]                     Edit filename
       [/Bfilename]                   Browse filename
       [/E]                           Exit to command prompt after edit
       [/Gglobal-profile-path]        Overrides set profile path
       [/Iimacro-name]                Initial maro
       [/Kkeyboard-macro-name]        Execute specified keyboard macro
       [/L(line-number,col-number)]   Specify line-number/column
       [/Pedit-profile-name]          Specify edit-profile
       [/Rfile-name]                  Merge compiler error file file-name
       [/Sdialog-function]            Directly execute dialog:
                                      /SPANEL(panel-id)[PARM(values)]
                                      /SCMD(REXX-procedure-name)[PARM(values)]
                                      /SCTC(internal-function-name)[PARM(values)]
                                      /SPGM(external-program-name)[PARM(values)]
       [/T]                           Turn on profile trace
       [/n.n]                         Goto panel id n.n
</pre><BR>
