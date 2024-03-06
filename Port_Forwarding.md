# Port Forwarding
1. Find your router login info
   * Most people don't change the username/password (some people don't have a username)
   * In most cases this information listed on the back/bottom of your router
2. Get into your router
   * Go to your browser and type in the *local* IP address
   * This is probably something along the lines of `192.168.0.0.1` ... if you are lazy like me type in `http://localhost`
   * Login with the router info from step 1
3. Find Port Forwarding
   * Somewhere in your router you will find wifi settings go there
   * Look for "Port Forwarding"
     * It may be a subheading under "Firewall" or you may need to look for an advanced options tab to find it
4. Set it to forward
   * ***NOTE:** setting up port forwarding means that anyone using your public ip address + the port being forwarded will be thrust into your router bypassing any and all firewalls... You have been warned. I highly suggest clicking the check box to undo it but save the setting option when not in use.*
   * First, identify the port it is forwarding to- for this it is ***XXXXXX*** port
