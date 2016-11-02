# evtparser
# Description
This is a Perl script that reads in new Windows Event (evt) files, parses them, and results in a CSV text file that is then intended to be ingested by Splunk (though this is just one option.)

# Example Usage
perl evtparse.pl -x /etc/evtparser/history.log -d /mnt/[share with evt files]/ -o /etc/evtparser/evttext/