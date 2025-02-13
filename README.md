# Project Title

Now that Macro's are depreciated, you can use this file for outbound call tracking with Asternic. This file uses GoSub and will work on FreePBX v17 and Asterisk 21. 



## Installation


```bash
  1. Add extensions_custom_asternic_outbound_freepbx_plus.conf to /etc/asterisk/
  2. Edit /etc/asterisk/extensions_custom.conf and add #include extensions_custom_asternic_outbound_freepbx_plus.conf
  3. Run command: asterisk -r asterisk -rx "reload dialplan"
```
    
