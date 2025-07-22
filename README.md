  💻Eureka Netflix Server to help interact two different services in an environment.
  Steps: 
  ✅ Register other services as client -> affected files -> app.properties with the url, build.gradle and annotate main application with @EnableDiscoveryClientand finally Access it via resttemplate client
  ✅ Register the server as eureka server by privding the app.properties 

  Key Notes: app config for overloading restTemplate() constructor to return new RestTempalte();

  
