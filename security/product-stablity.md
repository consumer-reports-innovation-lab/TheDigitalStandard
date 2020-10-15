---
evaluationName: Product Stablity
readinessFlag: '2'
criteria:
  - criteria_summary: The software is reliable.
    indicators:
      - indicator: The software is not susceptible to crashes.
        procedure_html: <li>Fuzz software to see if and how it crashes.</li>
      - indicator: >-
          If the program is forced to unexpectedly terminate, it shuts down in a
          safe and responsible fashion.
        procedure_html: >-
          <li>Under appropriate fuzz testing, what was the code coverage, number
          of crashes, and type(s) of crashes.</li><li>Are crashes exploitable, or
          do they simply allow a disruption of service?</li>
      - indicator: The software is not vulnerable to algorithmic complexity attacks.
        procedure_html: >-
          <li>Perform modified fuzzing to determine the software's vulnerability
          to algorithmic complexity attacks.</li>
---

