---
title: "Curl commands"
---

Options:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>curl -o [file] </code>
  <span style="margin-left: 10px; color: #555;"># --output: write to file</span>
  <br>
  <code>curl -u user:pass </code>
  <span style="margin-left: 10px; color: #555;"># --user: auth</span>
  <br>
  <code>curl -v </code>
  <span style="margin-left: 10px; color: #555;"># --verbose </span>
  <br>
  <code>curl -vv </code>
  <span style="margin-left: 10px; color: #555;"># More verbose</span>
  <br>
  <code>curl -s </code> 
  <span style="margin-left: 10px; color: #555;"># --silent, does not show progress or errors</span>
  <br>
  <code>curl -S </code> 
  <span style="margin-left: 10px; color: #555;"># --show-error: when used with --silent(-sS)</span>
  <br>
  <code>curl -i </code> 
  <span style="margin-left: 10px; color: #555;"># --include: Include the HTTP-header in the output </span>
  <br>
  <code>curl -I </code> 
  <span style="margin-left: 10px; color: #555;"># --head: headers only</span>
</div>
Request:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>curl -X POST </code>
  <span style="margin-left: 10px; color: #555;"># --request</span>
  <br>
  <code>curl -L </code>
  <span style="margin-left: 10px; color: #555;"># --follow link if redirected</span>
  <br>
  <code>curl -F </code>
  <span style="margin-left: 10px; color: #555;"># --form: HTTP POST data</span>
</div>
Data:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>curl -d 'data' </code>
  <span style="margin-left: 10px; color: #555;"># --data: HTTP post data, URL encoded</span>
  <br>
  <code>curl -d @file </code>
  <span style="margin-left: 10px; color: #555;"># --data via file</span>
  <br>
  <code>curl -G </code>
  <span style="margin-left: 10px; color: #555;"># --get: send -d data via get</span>
</div>
Headers:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>curl -A [str] </code>
  <span style="margin-left: 10px; color: #555;"># --user-agent</span>
  <br>
  <code>curl -b name=val </code>
  <span style="margin-left: 10px; color: #555;"># --cookie</span>
  <br>
  <code>curl -b FILE </code>
  <span style="margin-left: 10px; color: #555;"># --cookie</span>
  <br>
  <code>curl -H "X-Foo: y" </code>
  <span style="margin-left: 10px; color: #555;"># --header</span>
  <br>
   <code>curl --compressed </code>
  <span style="margin-left: 10px; color: #555;"># use gzip</span>
</div>
SSL:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>curl -E, --cert [cert] --cert-type </code>
  <span style="margin-left: 10px; color: #555;"># --cert: client cert file , der/pem/eng</span>
  <br>
  <code>curl -k, --insecure </code>
  <span style="margin-left: 10px; color: #555;"># for self assigned certs</span>
  <br>
  <code>--cacert [file] </code>
  <br>
  <code>--capath[dir] </code>
  
</div>
