# CREATE YOUR OWN PASSWORD AND PASTE IT INTO jupyter_notebook_config.json

## Open Python commandline and type:
<code>
    from notebook.auth import passwd
    passwd()
</code>

## You will see that program is asking for password
<code>
    Enter password:
    Verify password:
</code>

## Type your password and repeat
## Program will give you encrypted password that you need to copy and paste into jupyter_notebook_config.json
For example
<code>
    'argon2:$argon2id$v=19$m=10240,t=10,p=8$RDX2WPKrcl4AiJzPa/q5kg$ssuQQdS0hGRblx+WconB39U9mqjX3Et/FOazU79YqWw'
</code>