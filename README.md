### Technical Exercise for Anypoint platform


the exercise has been deployed to:


[http://techexercise.cloudhub.io/console/]


### What I have done
basically just follow the tutorials and documentation on mulesoft

* Create API project in Anypoint platform
* Design the API from API Manager
* Import to Anypoint studio the created API project
* Using APIKIT and mUnit to generate project files and test files

### further info
**Use case 1**: 
* This looks to be some SLA policy setting in Anypoint platform to ensure the service will be at least accept a minimum of 1 request in 5 
* Another way I can think of is to use the Caching Strategy

**Use case 2**: 
* This will be adding the Security Schemas and setting up OAuth provider then attach api_key in the header or request params
* Another way is to use Authorization header but it's probably less secure

**Use case 3**: 
Have added orders as endpoint per customer id, can probably add products per customer or have another sets of endpoints for product operations

### Interesting ideas
* have tried to use the Mulesoft recommended way to develop the code 
* thought of putting address inside customer response but it will probably be less performant
* I have actually implemented MySQL version in another repository [https://github.com/edmondkwong/api-practice]
