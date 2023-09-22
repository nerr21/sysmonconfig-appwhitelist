This sysmonconfig file used by RBC it excluded some applications used by the company that might be noisy in the event logs.
How to use:
1. download the sysmonconfig
2. save it where your sysmon is located
3. run cmd as admin
4. locate the sysmon path and change the directory for ex. "cd C:\Users\username\Sysmon"
5. if the sysmon is not installed type this in the terminal "Sysmon64.exe -accepteula -i sysmonconfig_endpoint.xml"
6. if its already installed type this "Sysmon64.exe -c sysmonconfig_endpoint.xml" to change the configuration from default to this custom config.

credits: to Mr. Olaf Hartong
