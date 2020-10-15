---
evaluationName: Encryption
readinessFlag: '2'
criteria:
  - criteria_summary: >-
      Information I provide is encrypted so that it can't be easily read or used
      by attackers.
    indicators:
      - indicator: >-
          Transmission of user communications or information is encrypted by
          default.
        procedure_html: >-
          <li>Investigation and analysis of publicly available documentation to
          determine what the company clearly discloses.</li>
      - indicator: >-
          Transmission of user communications or information is encrypted using
          unique keys.
        procedure_html: <li>Inspect traffic to determine if SSL encryption is used.</li>
      - indicator: Users can secure their content using end-to-end encryption.
        procedure_html: <li>Inspect traffic to determine if SSL encryption is used.</li>
      - indicator: End-to-end encryption is enabled by default.
        procedure_html: <li>Inspect traffic to determine if SSL encryption is used.</li>
      - indicator: >-
          User information and communications are encrypted by default when at
          rest.
        procedure_html: <li>Inspect traffic to determine if SSL encryption is used.</li>
---

