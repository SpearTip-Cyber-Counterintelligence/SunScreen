# SunScreen
![Logo](https://www.speartip.com/wp-content/uploads/2020/12/Copy-of-sunburst-3.png)

SunScreen is a tool utilized to detect systems vulnerable to SunBurst, or that have been exploited by SunBurst.

## Usage

Download the latest copy of SunScreen: (https://github.com/SpearTip-Cyber-Counterintelligence/SunScreen/raw/main/SunScreen%20SPF%2010.zip)

Move the latest copy of SunScreen to your Desktop, and double click the application.

SunScreen will then begin scanning the system, outputting notifications in the bottom right hand corner of the Desktop.

![Logo](https://speartiplogo.s3.amazonaws.com/begin_Scan.png)
![vulnicon](https://speartiplogo.s3.amazonaws.com/vulnerable.png)
![ScanComplete](https://speartiplogo.s3.amazonaws.com/complete.png)

When it is complete, a text file titled SolarWinds_Info.txt will appear on the Desktop, providing you with further information, and letting you know if Orion.Core.BusinessLayer.dll is present on the system.

If SunScreen locates the Orion.Core.BusinessLayer.dll, you need to assume your system has been compromised. 

As SpearTip discovers more Indicators of Compromise, SunScreen will recieve updates to reflect them.


## Contributing
Requests are welcome. Please open up an issue.
## License
[MIT](https://choosealicense.com/licenses/mit/)
