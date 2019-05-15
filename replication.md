# Determining how to replicate

We need to know under exactly what conditions the issue occurs. To help figure this out, it's helpful to know of any specific browser errors. **You will need a Mac and an iPhone for these instructions.**

### Set up your Mac

Open Safari. Go to `Safari > Preferences > Advanced` and check `Show Develop menu in menu bar`.

![Develop menu](./1.png)

## Mobile

### Set up your iPhone
On your phone, go to `Settings > Safari > Advanced` and check `Web Inspector`.

<div class="row">

  ![Settings](./2.png)
  
  ![Settings](./3.png)
  
  ![Settings](./4.png)

</div>

### Connect your iPhone to your Mac

Plug in your iPhone via USB cable, and select **"Trust"** on your iPhone (if you're prompted). Open up the desired site on Safari for iPhone.

>  ⚠️ You **must** use Safari, not Chrome!

On your Mac, you should see your device under the `Develop` menu. Go to `Develop > [Device Name] > [Site Name]`, replacing `[Device Name]` for your iPhone's name and `[Site Name]` for the name of the site you have open on your iPhone.

![Connect to device](./5.png)

You should see the following screen:

![Console](./6.png)

### Usage

Browse the site like normal. When the error occurs, **do not refresh the page!** 

- Take screenshots of the console window (pictured above) and your phone's screen
- Navigate to the `Network` tab (pictured below) and export its contents using the `Export` button at the upper right.

![Network tab](./7.png)

## Desktop

### Safari

Visit the website you wish to troubleshoot. Open `Develop > Show JavaScript Console`. Click the `Detatch into separate window` icon (pictured below).

![Detach](./8.png)

You should see the following screen:

![Console](./11.png)

Browse the site like normal. When the error occurs, **do not refresh the page!** 

- Take screenshots of the console window (pictured above) and your phone's screen
- Navigate to the `Network` tab (pictured below) and export its contents using the `Export` button at the upper right.

### Google Chrome

Open the website you wish to troubleshoot. Go to `View > Developer > Javascript console`

![Develop menu](./9.png)

You should see the following screen:

![Console](./10.png)

Browse the site like normal. When the error occurs, **do not refresh the page!** 

- Take screenshots of the console window (pictured above) and your phone's screen
- Navigate to the `Network` tab (pictured below). To export its contents, right click on any row and choose `Save all as HAR with content`. 
