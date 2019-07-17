# Shodan Filters

ssl:"Target"  
ssl:"Target" 200  
ssl:"Target" org:"Amazon"  
ssl:"Target" -"AkamaiGHost"  
title:"Target"  
html:"Pattern" ***footer***  
ssl:"company development"  


**RUBY**  
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
port 4848  

**Moodle**  
http.component:moodle  
  
@ph0rensic  

reference: https://medium.com/bugbountywriteup/using-shodan-better-way-b40f330e45f6  
