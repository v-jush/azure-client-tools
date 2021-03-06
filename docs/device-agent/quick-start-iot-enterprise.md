# Quick start using Windows IoT Enterprise

In this tutorial, we will walk the reader through the minimal steps to get a debug version of the Device Agent running on a Windows IoT Enterprise device.

For a quick start on Windows IoT Core with Azure DPS, see this [page](quick-start-iot-core.md).

- Download a pre-built version of the client: [x86](../../downloads/device.agent.1.0.0.1.x86.zip), [x64](../../downloads/device.agent.1.0.0.1.x64.zip), or [arm](../../downloads/device.agent.1.0.0.1.arm.zip).
- Extract to a folder (i.e c:\deploy.arm)
- Update the c:\deploy.arm\bin\AzureDeviceManagementClient.json with the connection string.
- From an admin window, run the client:
    <pre>
    cd c:\deploy.arm\bin
    AzureDeviceManagementClient.exe -install
    net start AzureDeviceManagementClient
    </pre>

**Note**: If you are running on Windows Enterprise, you will need to [enable embedded mode](https://docs.microsoft.com/en-us/windows/iot-core/develop-your-app/embeddedmode).

----

[Home](../../README.md) | [Device Agent](device-agent.md) | [Quick Starts](quick-start.md)
