
# Installing Apache HOP on Windows

## Table of Contents
1. [Download Apache HOP](#1-download-apache-hop)
2. [Install Java JDK](#2-install-java-jdk)
3. [Extract Apache HOP](#3-extract-apache-hop)
4. [Configure Apache HOP](#4-configure-apache-hop)
5. [Optional: Add HOP to System PATH](#5-optional-add-hop-to-system-path)
6. [Run Apache HOP](#6-run-apache-hop)
7. [Troubleshooting](#7-troubleshooting)

## 1. Download Apache HOP

1. Visit the official Apache HOP website: [https://hop.apache.org/download](https://hop.apache.org/download).
2. Choose the latest stable version and download the ZIP file for Windows.

## 2. Install Java JDK

Apache HOP requires Java JDK 11 or higher to run.

1. Download the appropriate version of the Java Development Kit (JDK) 11 or above from the Oracle website: [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Install the JDK.
3. Add the JDK to your system **PATH**:
   - Open **Control Panel** → **System** → **Advanced system settings**.
   - Go to the **Advanced** tab and click **Environment Variables**.
   - Under **System variables**, find the `Path` variable, select it, and click **Edit**.
   - Add the path to the `bin` folder of the JDK installation (e.g., `C:\Program Files\Java\jdk-11.x.xin`).
4. Verify the Java installation by opening **Command Prompt** and typing:
   ```bash
   java -version
   ```

## 3. Extract Apache HOP

Extract the downloaded ZIP file to a folder of your choice, e.g., `C:\ApacheHop`.

## 4. Configure Apache HOP

1. Navigate to the folder where you extracted Apache HOP, e.g., `C:\ApacheHop`.
2. Locate the `hop-gui.bat` file.
3. Double-click `hop-gui.bat` to start the Apache HOP graphical user interface (GUI).

## 5. Optional: Add HOP to System PATH

To run Apache HOP from anywhere in your system, you can add the `C:\ApacheHopin` folder to your PATH environment variable:

1. Open **Control Panel** → **System** → **Advanced system settings**.
2. Go to the **Advanced** tab and click **Environment Variables**.
3. Under **System variables**, find the **Path** variable, select it, and click **Edit**.
4. Add the path to the HOP `bin` folder (e.g., `C:\ApacheHopin`).

## 6. Run Apache HOP

The Apache HOP GUI will launch, and you can begin creating pipelines and workflows.

## 7. Troubleshooting

If you encounter any issues during installation or need further assistance, feel free to reach out for support.
