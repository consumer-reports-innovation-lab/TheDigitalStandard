---
evaluationName: Best Build Practices
readinessFlag: '1'
criteria:
  - criteria_summary: >-
      The software was built and developed according to the industry's best
      practices for security.
    indicators:
      - indicator: The product was built with effectively implemented safety features.
        procedure_html: >-
          <li>Run static analysis software to determine what application armoring
          features are present.</li><li>Are there Stack Guards, and if so, are
          they effectively implemented?</li><li>Are all safety features available
          in the pertinent OS enabled? (e.g., ASLR, CFI, RELRO, DEP,
          etc.)</li><li>Are those safety features well implemented and/or enabled
          with optimal settings? (E.g., High Entropy ASLR, rather than just
          Dynamic Base on Windows 10)</li><li>Are the binaries 32 or 64 bit?</li>
      - indicator: The software does not make use of unsafe functions or libraries.
        procedure_html: >-
          <li>Pull out data from the binary that speaks to developer
          hygiene.</li><li>Do they use strcpy and other historically unsafe
          functions?</li><li>Did the developers use older, less historically safe
          functions, or newer, safer replacements for those
          functions?</li><li>What risks are introduced via the libraries that the
          binary links to, either directly or indirectly?</li>
      - indicator: The software is not overly complex.
        procedure_html: >-
          <li>Pull out data from the binary that speaks to code
          complexity.</li><li>What is the branch density?</li><li>How many stack
          adjusts, function calls, etc are there?</li><li>How complex is the
          code?</li>
---

