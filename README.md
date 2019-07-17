# shodan_filters

ssl:"Target"
ssl:"Target" 200
ssl:"Target" org:"Amazon"
ssl:"Target" -"AkamaiGHost"
title:"Target"
html:"Pattern" ***footer***
ssl:"company development"

**RUBY DEBUG ON**
html:"SECRET_KEY_BASE"
html:"rack.version"
html:"rack.errors"
html:"puma.socket"
http.component:ruby

**DJANGO**
http.component:django


**Kubernates**
http.component:Kubernetes

**Jenkins**
html:"Dashboard Jenkins" 
http.component:"Jenkins"

**GlassFish**
http.component:glassfish
port 9898

**Moodle**
http.component:moodle

@ph0rensic
