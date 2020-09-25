# Shodan Filters

General
---
- ssl:"Target"  
- ssl:"Target" 200  
- title:"Target"  
- html:"Pattern" ***footer***  
- ssl:"company development"   
- ssl.cert.subject.CN: domain.com

RUBY
---
- html:"SECRET_KEY_BASE"  
- html:"rack.version"  
- html:"rack.errors"  
- html:"puma.socket"  
- http.component:ruby port:3000 ***debug on***

DJANGO
---  
- http.component:django  
- DisallowedHost
- http.component:django

Python Server
---
- "Server: Werkzeug/1.0"

Kubernates
---  
- http.component:Kubernetes  

Jenkins
---
- html:"Dashboard Jenkins"  
- http.component:"Jenkins"  
- x-jenkins 
- title:Dashboard[Jenkins]
- http.favicon.hash:81586312

GlassFish
--- 
- http.component:glassfish  
- port:4848  

Moodle
---  
- http.component:moodle  

Opmon
---
- http.favicon.hash:710184709

WeaveScope
---
- http.favicon.hash:567176827

Primefaces
---
- html:"ln=primefaces"

Spring Boot
---
- http.favicon.hash:116323821

Tomcat and Apache
---
- "Server: Apache-Coyote"
- http.component:tomcat
- http.favicon.hash:-297069493
- http.favicon.hash:-838827616

Liferay
---
- http.component:liferay
- http.favicon.hash:129457226
- Liferay-Portal

Joomla
---
- http.favicon.hash:366524387

WebLogic
---
- "WebLogic Server"

JBoss
---
- http.favicon.hash:-656811182
- "x-powered-by" "jboss"
- http.component:jboss

Wordpress
---
- http.component:wordpress

CodeIgniter
---
- http.component:codeigniter

Laravel
---
- http.component:laravel

Drupal
---
- http.component:drupal

AEM
---
- http.component:"Adobe Experience Manager"

BIG-IP
---
- http.favicon.hash:-335242539

Meteor
---
- http.component:meteor

React
---
- http.component:react

Mantis
---
- http.favicon.hash:662709064

@phor3nsic 

*reference:*
*https://medium.com/bugbountywriteup/using-shodan-better-way-b40f330e45f6*

###### tags: `SHODAN` `Filters` `shodan filters` 

