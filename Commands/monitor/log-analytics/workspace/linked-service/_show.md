# [Command] _monitor log-analytics workspace linked-service show_

Show the properties of a linked service.

## Versions

### [2020-08-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5vcGVyYXRpb25hbGluc2lnaHRzL3dvcmtzcGFjZXMve30vbGlua2Vkc2VydmljZXMve30=/2020-08-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.operationalinsights/workspaces/{}/linkedservices/{} 2020-08-01 -->

#### examples

- Show the properties of a linked service.
    ```bash
        monitor log-analytics workspace linked-service show -g MyResourceGroup -n cluster --workspace-name MyWorkspace
    ```
