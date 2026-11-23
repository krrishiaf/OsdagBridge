# OsdagBridge
Software testing and issue report for the OsdagBridge short-span steel girder bridge module. FOSSEE Osdag Winter Internship 2026, Task 4. Includes test log, screenshots, .osi files, dictionaries and final report.
# OsdagBridge Task 4: Software Testing & Issue Reporting

Author: Krrish Ambwani (GitHub: krrishiaf)
Program: FOSSEE Osdag Winter Internship 2026, IIT Bombay (Software Development)
Module tested: OsdagBridge, short-span steel girder highway bridge
Upstream repo: https://github.com/Nidhikhare12/OsdagBridge
Screencast: https://youtu.be/Eh-YW9kLYqs

## Contents
- OsdagBridge_Test_Report_Krrish_Ambwani_FINAL.pdf: final report
- test_log.md: test cases with exact parameters and results
- screenshots/: screenshots from my own runs
- osi_files/: saved .osi input files
- dictionaries/: Input/Output dictionary files
- notes/: extra notes

## Summary of results
| ID | Test | Result |
|----|------|--------|
| T01 | Default design run (span 22 m) | PASS (second Design click; first click showed no visible result) |
| T02 | Top Clear Cover 50 to 40, Save, Design, reopen | FAIL, seen once, unconfirmed (showed 50 after reopening) |
| T03 | Span 22 to 25 m, Design | PASS (3D model and diagrams showed 25 m) |
| T04 | Not performed | NOT TESTED |
| T05 | Boundary / invalid inputs | NOT TESTED |

Three consecutive design runs finished with no crash.

## Issues
No GitHub issues raised. The T02 result was seen once and not repeated, and was not checked against existing issues.

## Not tested
Custom steel grades and custom concrete properties, stiffener / cross-bracing / end diaphragm inputs, Deck Details fields, 3D view checkboxes, Input/Output dictionaries vs
