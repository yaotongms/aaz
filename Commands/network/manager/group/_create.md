# [Command] _network manager group create_

Create a network group.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL25ldHdvcmttYW5hZ2Vycy97fS9uZXR3b3JrZ3JvdXBzL3t9/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/networkmanagers/{}/networkgroups/{} 2022-01-01 -->

#### examples

- Create/Update Azure Virtual Network Manager Network Group
    ```bash
        network manager group create --name "TestNetworkGroup" --network-manager-name "testNetworkManager" --description "A sample group" --resource-group "rg1"
    ```
