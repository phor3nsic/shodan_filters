# Shodan Filters

ssl:"Target"  
ssl:"Target" 200  
ssl:"Target" org:"Amazon"  
ssl:"Target" -"AkamaiGHost"  
title:"Target"  
html:"Pattern" ***footer***  
ssl:"company development"   
ssl.cert.subject.CN: domain.com


**RUBY**  
html:"SECRET_KEY_BASE"  
html:"rack.version"  
html:"rack.errors"  
html:"puma.socket"  
http.component:ruby port:3000 ***debug on***

**DJANGO**  
http.component:django  

**Kubernates**  
http.component:Kubernetes  

**Jenkins**  
html:"Dashboard Jenkins"  
http.component:"Jenkins"  

**GlassFish**  
http.component:glassfish  
port:4848  

**Moodle**  
http.component:moodle  

'http.favicon.hash:81586312',

**Jenkins**   
'x-jenkins',
'http.component:jenkins',
'title:Dashboard[Jenkins]',

'http.favicon.hash:710184709',
'http.favicon.hash:567176827',
'http.component:glassfish',
'http.component:ruby',
'html:"ln=primefaces"',
'http.favicon.hash:116323821',
'"Server: Apache-Coyote"',
'http.component:tomcat',
'http.component:liferay',
'http.favicon.hash:129457226',
'Liferay-Portal',
'http.favicon.hash:-297069493',
'http.favicon.hash:-838827616',
'http.favicon.hash:366524387',
'"WebLogic Server"',
'http.favicon.hash:-656811182',
'"x-powered-by" "jboss"',
'http.component:jboss',
'DisallowedHost',
'http.component:django',
'http.component:wordpress',
'http.component:codeigniter',
'http.component:laravel',
'http.component:drupal',
'"Server: Werkzeug/1.0"',
'http.component:"Adobe Experience Manager"',
'http.favicon.hash:-335242539' #BIG-IP-F5
  
@phor3nsic 

reference: https://medium.com/bugbountywriteup/using-shodan-better-way-b40f330e45f6  
