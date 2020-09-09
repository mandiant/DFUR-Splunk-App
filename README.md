<h2>DFUR-Splunk-App</h2>
This repo contains the "DFUR" Splunk application and pre-indexed data referenced in the 2020 SANS DFIR Summit presentation "Captain's Log: Take your application log analysis from Starfleet to Star Fleek" by David Pany and Ryan Tomcik. Get started by installing the application in Splunk and opening up the "DFUR Monitoring" dashboard. Or strip it for parts. Either way, enjoy!

<h2>Questions / Comments</h2>
Twitter: @heferyzan

<h2>Splunk Requirements</h2>
<table>
<thead>
<tr>
<th>App / Add-on</th>
<th>Download</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>Splunk Enterprise / Free</td>
<td><a href="http://www.splunk.com" rel="nofollow">http://www.splunk.com</a></td>
<td></td>
</tr>
<tr>
<td>Haversine</td>
<td><a href="https://splunkbase.splunk.com/app/936/" rel="nofollow">https://splunkbase.splunk.com/app/936/</a></td>
<td>If the Haversine application can't be uploaded through the Splunk UI, then extract the file contents to $SPLUNK_HOME/etc/apps</td>  
</tr>
</tr>
<tr>
<td>ASN Lookup Generator</td>
<td><a href="https://splunkbase.splunk.com/app/3531/" rel="nofollow">https://splunkbase.splunk.com/app/3531/</a></td>
<td>Requires the asngen command to be executed to populate the asn lookup</td>
</tr>
