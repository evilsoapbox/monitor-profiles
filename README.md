# Monitor profiles

I noticed that many of the monitors I commonly use had really poor color
calibration. So, I decided to purchase a Datacolor Spyder5Express and calibrate
them. This repository contains color calibration profiles for monitors I
frequently use.

## Testing methodology

To calibrate my monitors, I followed some very useful directions from
[this Amazon review](https://www.amazon.com/gp/customer-reviews/RVFML9ETLEQOE/ref=cm_cr_dp_d_rvw_ttl?ie=UTF8&ASIN=B00UBSL2TO). Specifically, I did/do the following on each machine:

# Download [Argyll](http://www.argyllcms.com/) and [DisplayCAL standalone version](http://dispcalgui.hoech.net/#download)
# Extract the Argyll files somewhere
# Install the Spyder USB driver from the [Argyll installation](http://www.argyllcms.com/doc/Installing_MSWindows.html#WIN8)
# When you start DisplayCAL it will ask for your Argyll installation - point it to
wherever you extracted Argyll
# In DisplayCAL, go to `Menu` > `Options` > enable `Show advanced calibration options`
# Configure DisplayCAL based on the configuration settings in [this thread](http://www.modelmayhem.com/forums/post/870355/1#post17806610)
# Run the calibration

I use a high setting which takes about 1.5 - 2 hours. For profiling, I choose a
profile type of `Curves + matrix`.

## Installation
You should be able to install these ICC profiles as-is. I have also included the
measurement report detailing the settings once everything was complete.
