# Day-5-Manual
Static Testing
--------------
Static testing is used to find defects in a software application without executing the code, helping detect errors early when they are easier and cheaper to fix. 
It is important for finds errors at early stage,reduces cost and time,improves code quality,prevents defects from reaching later stages.

Types of Static Testing:
Manual Testing:
---------------
  Manual examinations include analysis of code done manually,also known as REVIEWS.

Types of Review
---------------
  Informal Review  :  An informal review is a simple, unstructured review where defects are identified without following any formal process.
  Walkthrough      :  A walkthrough is a review where the author explains the document or code step-by-step to the team.
  Technical Review :  A technical review is a formal review conducted by experts to check technical correctness.
  Inspection       :  Inspection is the most formal and structured review process used to find defects systematically.

Static testing checks many documents like:
------------------------------------------
    * Requirements (BRD)
    * Test cases
    * Design documents
    * Source code
    * User manuals
    * Test plans

Types of Defects:
-----------------
 Static testing can easily find:
    * Missing requirement
    * Design issues
    * Coding standard violations
    * Unreachable code
    * Inconsistent interfaces
Example:
 return;
 System.out.println("This will never execute");

Static Code Analysis – Uses tools to check code without running it. Finds errors automatically.
---------------------
Data Flow Analysis              : Checks how data is used in the program. Finds uninitialized variables, dead code
Control Flow Analysis           : Checks program flow. Finds infinite loops, unreachable code
Coding Standards Compliance     : Checks if code follows rules and style. 
Security Vulnerability Scanning : Finds security issues in code

Other Static Techniques:
------------------------
Use Case Requirements Validation   : Ensures all user actions are covered
Functional Requirements Validation : Checks all functions are properly defined
Architecture Review                : Verifies system design meets business needs
Field Dictionary Validation        : Checks UI fields for correctness and consistency

Benefits of Static Testing:
---------------------------
  * Early bug detection           : Static testing finds errors early, when they are easy and cheap to fix.
  * Prevention of common issues   : It helps fix common problems like syntax errors and null pointer issues early, avoiding bigger problems later.
  * Improved code quality         : It ensures the code is clean, well-structured, and easy to maintain.
  * Reduced costs                 : Fixing bugs early saves time, effort, and money.
  * Immediate feedback            : It gives quick feedback during each stage of development.
  * Helps find exact bug location : It helps identify the exact place where the error exists.

Static Testing Tools :
----------------------
     *Checkstyle, 
     *Soot, 
     *SourceMeter, 
     *Lint, 
     *SonarQube






    
