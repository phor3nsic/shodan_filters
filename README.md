# shodan_filters
<br>
ssl:"Target"<br>
ssl:"Target" 200<br><br>
ssl:"Target" org:"Amazon"<br>
ssl:"Target" -"AkamaiGHost"<br>
title:"Target"<br>
html:"Pattern" ***footer***<br>
ssl:"company development"<br>
<br>
**RUBY DEBUG ON**<br>
html:"SECRET_KEY_BASE"<br>
html:"rack.version"<br>
html:"rack.errors"<br>
html:"puma.socket"<br>
http.component:ruby<br>
<br>
**DJANGO**<br>
http.component:django<br>
<br>
<br>
**Kubernates**<br>
http.component:Kubernetes<br>
<br>
**Jenkins**<br>
html:"Dashboard Jenkins" <br>
http.component:"Jenkins"<br>
<br>
**GlassFish**<br>
http.component:glassfish<br>
port 9898<br>
<br>
**Moodle**<br>
http.component:moodle<br>
<br>
@ph0rensic
