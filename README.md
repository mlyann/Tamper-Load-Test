# TamperLoadTest



## Getting Started with TamperMonkey

1. Install Tampermonkey as an browser extension at: [TamperMonkey](https://www.tampermonkey.net/)
2. Ensure Developer Mode is enabled by:
- For Chrome, click the 3 dots at the top right of your browser
- Navigate to Extensions
- Navigate to Manage Extensions
- Ensure developer mode is enabled in the top right

3. TamperMonkey should be ready to use!


## Usage
1. Navigate to the TamperMonkey dashboard and copy/paste the Fetch_Response_Time.js Script into a new Script.

2. Make sure the @Match (line 4) matches the URL of the website that you're checking the response time of.
    - In Tampermonkey, the @match directive specifies which URLs the script will run on, using a pattern where * acts as a wildcard to match any         characters, allowing for flexible URL matching.
    - The script will automatically test the exact URL you are on

3. Go to the website you wish to test, if the script is enabled the UI should appear.


## Features
1. Set the parameters for your test
    - The Duration the test will run (Minutes)
    - The Expected Response time, Acceptable upper limit for Response Time to Configure Graph (Seconds)
    - The Pause Time in between each fetch, how long it should Pause before it checks the load time again (Seconds)

2. Start the Script
    - Graph should automatically appear and will by dynamically updated
    - Graph can be downloaded at any time during the test
    - Statistics will be available after 'Duration'
    - Data will be available to download after 'Duration'



## Notes
On some websites, the UI proportions or some buttons may appear different, you can reconfigure in the CreateUI() function.

## Authors and acknowledgment
Authored by Minglai Yang
