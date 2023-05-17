# To install Nsight Compute on Ubuntu

1. Download the Nsight Compute installer package from the NVIDIA Developer website. Ensure that you choose the correct version that matches your Ubuntu installation and GPU architecture.

2. Open a terminal and navigate to the directory where the installer package was downloaded.

3. Make the installer package executable by running the following command:
   ```
   chmod +x <installer_package_name>.run
   ```

4. Execute the installer package by running the following command:
   ```
   sudo ./<installer_package_name>.run
   ```

5. Follow the on-screen instructions provided by the installer. Review and accept the license agreement, choose the installation location (or use the default location), and select any additional components you wish to install.

6. Once the installation is complete, you should be able to access Nsight Compute from the Applications menu or by running the "nsight-compute" command in the terminal.

Note: It's recommended to have the latest NVIDIA drivers installed on your system before installing Nsight Compute to ensure compatibility and optimal performance.

# To run Nsight Compute on Ubuntu

1. Ensure that you have installed Nsight Compute on your Ubuntu system by following the installation instructions.

2. Open a terminal on your Ubuntu system.

3. Run the following command to start Nsight Compute:
   ```
   nsight-compute
   ```

4. Nsight Compute will launch, presenting you with the graphical user interface.

5. In the Nsight Compute GUI, you can create a new profiling session by clicking on the "New Profile" button or open an existing session file by selecting "Open Profile" from the File menu.

6. Within Nsight Compute, you can configure various profiling options such as the target CUDA application, CUDA API trace settings, and other parameters specific to your profiling needs.

7. Once the profiling session is set up, you can start the profiling by clicking on the "Start" button or selecting "Profile" from the Run menu.

8. Nsight Compute will then execute the CUDA application with the specified profiling settings and gather performance data.

9. After the profiling session completes, you can analyze the collected performance data in Nsight Compute, exploring metrics, visualizations, and various analysis views to gain insights into the performance characteristics of your CUDA application.

10. Finally, you can save the profiling session for future reference or export the performance data to different formats for further analysis.

Note: It's important to ensure that your CUDA application is compiled with profiling support enabled (using the appropriate compiler flags) to capture accurate performance data in Nsight Compute.

These steps should help you run Nsight Compute on Ubuntu and utilize its features to analyze the performance of your CUDA applications.
