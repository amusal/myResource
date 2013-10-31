Usage:
1. run server/upload.bat
appid ==> wfsuibian|wfsuibiangoagent
email ==> wfsuibian@gmail.com
passw ==> s4
# if don't have accout, register a  https://appengine.google.com account and apply an app, remember the appid.

2. open file local/proxy.ini, find section "gae", modify appid as:
appid = wfsuibian|wfsuibiangoagent
# note: multi apps use '|' to split

3. run local/goagent.exe, proxy runs. This is only a http proxy app, the proxy ip and port just open local/proxy.ini and discovery the "pac" section.
Default ip is 127.0.0.1, port is 8086.

4. Set browsers local http proxy as setting in local/goagent, every goes well. Enjoy your FanQiang journal! :-)
