Nagios Classic UI
=================

After more than a decade, Nagios replaced its familiar web UI with
a new one. I hate the new one and wanted the old one back.

I've simply copied stylesheets, images and index.php from nagios-3.4.1

Installation
------------

    cd /usr/share/nagios # or wherever your Nagios is installed
    git clone https://github.com/mbailey/nagios-classicui.git
    cp -r nagios-classicui/* html/
