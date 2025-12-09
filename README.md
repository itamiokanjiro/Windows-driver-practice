# Driver samples for Windows 11

These are the official Microsoft Windows Driver Kit (WDK) driver code samples for Windows 11. They provide a foundation for Universal Windows driver support of all hardware form factors, from phones to desktop PCs. Use these samples with Visual Studio 2022 and Windows Driver Kit (WDK) 11.

[Windows Driver Kit documentation](https://docs.microsoft.com/windows-hardware/drivers/)

## Windows 11 driver development

Use Visual Studio 2022 and Windows Driver Kit (WDK) 11 to build, test, and deploy your drivers. With Windows 11, the driver development environment is integrated into Visual Studio. To get started, download the driver development kits and tools for Windows 11.

[Download the WDK, WinDbg, and associated tools](https://developer.microsoft.com/windows/hardware/windows-driver-kit)

### Windows Driver Kit (WDK)

Take a look at the compilation of the new and changed driver-related content for Windows 11. Areas of improvement include camera, print, display, Near Field Communication (NFC), WLAN, Bluetooth, and more.

[Find out what's new in the WDK](https://docs.microsoft.com/windows-hardware/drivers/what-s-new-in-driver-development)

### Universal Windows drivers

Write one driver that runs on Windows 11 for desktop editions, as well as other Windows editions that share a common set of interfaces.

[Getting Started with Universal Windows drivers](https://docs.microsoft.com/windows-hardware/drivers/develop/getting-started-with-universal-drivers)

### Windows Driver Frameworks

The Windows Driver Frameworks (WDF) are a set of libraries that make it simple to write high-quality device drivers.

[WDF driver development guide](https://docs.microsoft.com/windows-hardware/drivers/wdf/)

### Samples

Use the samples in this repo to guide your Windows driver development. Whether you're just getting started or porting an older driver to the newest version of Windows, code samples are valuable guides on how to write drivers.

For information about important changes that need to be made to the WDK sample drivers before releasing device drivers based on the sample code, see the following topic:

[From Sample Code to Production Driver - What to Change in the Samples](https://docs.microsoft.com/en-us/windows-hardware/drivers/gettingstarted/from-sample-code-to-production-driver)

### Build your first driver

If you're writing your first driver, use these exercises to get started. Each exercise is independent of the others, so you can do them in any order.

[Write a UMDF driver based on a template](https://docs.microsoft.com/windows-hardware/drivers/gettingstarted/writing-a-umdf-driver-based-on-a-template)

[Write a KMDF Hello World driver](https://docs.microsoft.com/windows-hardware/drivers/gettingstarted/writing-a-very-small-kmdf--driver)

[Write a KMDF driver based on a template](https://docs.microsoft.com/windows-hardware/drivers/gettingstarted/writing-a-kmdf-driver-based-on-a-template)

[Use GitHub Actions to build a simple driver project](.github/Build-with-GitHub.md)

# Microsoft Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.



# Windows 11 驅動程式範例

這些是官方 Microsoft Windows 驅動程式套件 (WDK) 的 Windows 11 驅動程式範例程式碼。它們為通用 Windows 驅動程式提供基礎，支援所有硬體型態，從手機到桌面電腦皆適用。請搭配 Visual Studio 2022 與 Windows 驅動程式套件 (WDK) 11 使用這些範例。

[Windows 驅動程式套件文件](https://docs.microsoft.com/windows-hardware/drivers/)

## Windows 11 驅動程式開發

使用 Visual Studio 2022 與 Windows 驅動程式套件 (WDK) 11 建置、測試及部署您的驅動程式。在 Windows 11 中，驅動程式開發環境已整合到 Visual Studio 中。要開始，請下載 Windows 11 的驅動程式開發套件與工具。

[下載 WDK、WinDbg 及相關工具](https://developer.microsoft.com/windows/hardware/windows-driver-kit)

### Windows 驅動程式套件 (WDK)

查看 Windows 11 新增及變更的驅動程式相關內容。改進領域包括相機、列印、顯示器、近場通訊 (NFC)、WLAN、藍牙等。

[了解 WDK 的最新功能](https://docs.microsoft.com/windows-hardware/drivers/what-s-new-in-driver-development)

### 通用 Windows 驅動程式

撰寫一個驅動程式，即可在 Windows 11 桌面版本及其他共享相同介面的 Windows 版本上運行。

[通用 Windows 驅動程式入門](https://docs.microsoft.com/windows-hardware/drivers/develop/getting-started-with-universal-drivers)

### Windows 驅動程式框架

Windows 驅動程式框架 (WDF) 是一組函式庫，使撰寫高品質裝置驅動程式變得簡單。

[WDF 驅動程式開發指南](https://docs.microsoft.com/windows-hardware/drivers/wdf/)

### 範例

使用此資源庫中的範例來指導您的 Windows 驅動程式開發。無論您是初學者，還是將舊版驅動程式移植到最新 Windows 版本，範例程式碼都是撰寫驅動程式的重要參考。

有關在基於範例程式碼釋出裝置驅動程式之前，需要對 WDK 範例驅動程式做的重要更改資訊，請參閱以下主題：

[從範例程式碼到正式驅動程式 – 範例中需要更改的內容](https://docs.microsoft.com/en-us/windows-hardware/drivers/gettingstarted/from-sample-code-to-production-driver)

### 建置您的第一個驅動程式

如果您要撰寫第一個驅動程式，請使用這些練習開始。每個練習彼此獨立，因此可依任何順序進行。

[基於範本撰寫 UMDF 驅動程式](https://docs.microsoft.com/windows-hardware/drivers/gettingstarted/writing-a-umdf-driver-based-on-a-template)

[撰寫 KMDF Hello World 驅動程式](https://docs.microsoft.com/windows-hardware/drivers/gettingstarted/writing-a-very-small-kmdf--driver)

[基於範本撰寫 KMDF 驅動程式](https://docs.microsoft.com/windows-hardware/drivers/gettingstarted/writing-a-kmdf-driver-based-on-a-template)

[使用 GitHub Actions 建置簡單驅動程式專案](.github/Build-with-GitHub.md)

# Microsoft 行為準則

本專案已採用 [Microsoft 開源行為準則](https://opensource.microsoft.com/codeofconduct/)。更多資訊請參閱 [行為準則 FAQ](https://opensource.microsoft.com/codeofconduct/faq/) 或聯絡 [opencode@microsoft.com](mailto:opencode@microsoft.com) 以提出其他問題或建議。

