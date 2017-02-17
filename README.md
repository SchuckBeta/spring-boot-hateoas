# spring-boot

spring-boot集成spring-data-rest、spring-data-jpa、spring-data-jpa、spring-data-hateoas

支持json\xml\hateoas
json:http://host:prot/teams.json
xml:http://host:prot/teams.xml或http://host:prot/teams
hateoas:http://host:prot/teams/1(id)

匹配的URL格式和支持的文件
 "{[/{repository}/{id}],methods=[GET],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}],methods=[PUT],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}],methods=[OPTIONS],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}],methods=[DELETE],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}],methods=[POST],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}],methods=[GET],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}" 

 "{[/{repository}/{id}],methods=[PATCH],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}],methods=[HEAD],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}],methods=[OPTIONS],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}],methods=[HEAD],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}],methods=[GET],produces=[application/x-spring-data-compact+json || text/uri-list]}" 

 "{[/{repository}/{id}/{property}],methods=[GET],produces=[application/x-spring-data-compact+json || text/uri-list]}"

 "{[/{repository}/{id}/{property}],methods=[DELETE],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}/{property}/{propertyId}],methods=[DELETE],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}/{property}],methods=[GET],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}/{property}/{propertyId}],methods=[GET],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"

 "{[/{repository}/{id}/{property}],methods=[PATCH || PUT || POST],consumes=[application/json || application/x-spring-data-compact+json || text/uri-list],produces=[application/hal+json || application/json || application/*+json;charset=UTF-8]}"
