# [Command] _acat report update_

Update a new AppComplianceAutomation report or update an exiting AppComplianceAutomation report.

## Versions

### [2024-06-27](/Resources/mgmt-plane/L3Byb3ZpZGVycy9taWNyb3NvZnQuYXBwY29tcGxpYW5jZWF1dG9tYXRpb24vcmVwb3J0cy97fQ==/2024-06-27.xml) **Stable**

<!-- mgmt-plane /providers/microsoft.appcomplianceautomation/reports/{} 2024-06-27 -->

#### examples

- update acat report
    ```bash
        acat report update --reportName testName     --offer-guid "00000000-0000-0000-0000-000000000001"
    ```

- update resource list
    ```bash
        acat report update  --report-name youReportName  --resources test.json
    ```
