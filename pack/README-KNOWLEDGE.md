# TechDiag - knowledge pack

Data files for TechDiag, a read-only diagnostic tool for Windows 11 PCs of Dell and HP that do not start.
Nothing here is a program and nothing here is run: plain text that TechDiag reads.

- `TechDiag-Knowledge-<DD-MM-YYYY>.zip` - the pack. Put it beside `TECHDIAG-UPDATE.exe` and double-click the program:
  it checks every file against `MANIFEST.txt` (size and SHA-256) and installs the knowledge.
- `pack/` - the same files, unpacked, to read.
- `PACK.txt` - one line that names the newest pack and its SHA-256. A `TECHDIAG-UPDATE.exe` that knows this place
  reads it and downloads the pack by itself.

What is in it: known problems of Windows updates and the update that fixes each, the builds of Windows 11 and their
KB numbers, Windows error and stop codes, cases the makers themselves documented (Microsoft, Dell, HP, Intel) and the
makers' diagnostic codes. Every line comes from the maker's own public page.

What is never in it: anything of an organization - no PC names, users, serial numbers, logs or internal rules.

Lines under "added by the night watch" in the list were found and checked by an automatic nightly job: each is a
CHECK (never a PROBLEM) with the update Microsoft names as the fix.

## The program

TechDiag itself - the program, its versions and how to run it - is in the repository `Tzahibo/TechDiag`
(private): its Releases page holds every version. This pack was checked with TechDiag 4.0.1.

**בעברית:** כאן נמצאת תמיד חבילת הידע החדשה ביותר של TechDiag. מורידים את קובץ ה-zip, שמים אותו בתיקייה
`TechDiag\Knowledge\Packs` שעל ה-USB ומריצים את `Update\TECHDIAG-UPDATE.exe`.
