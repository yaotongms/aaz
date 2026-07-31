# [Command] _connectedmachine identity assign_

Assign the user or system managed identities.

## Versions

### [2026-06-16-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5oeWJyaWRjb21wdXRlL21hY2hpbmVzL3t9/2026-06-16-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.hybridcompute/machines/{} 2026-06-16-preview identity -->

#### examples

- Sample command for connectedmachine identity assign
    ```bash
        connectedmachine identity assign --resource-group myResourceGroup --machine-name myMachine --system-assigned --user-assigned /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myResourceGroup/providers/Microsoft.ManagedIdentity/userAssignedIdentities/myIdentity
    ```
