# Meals DB REST API for Mobile Team Practise
A rest apis for Mobile team for practise
# Hey folks,Find the below endpoints for -GET Request.
***
## GET-Endpoint

To get all the Meals from the DB use the following endpoint
`http://blacky.tech/mealsapi/meals.php`

To get all the category from the DB,
`http://blacky.tech/mealsapi/category.php`

### Sample JSON Response 
#### For Meals End-Point:
The following JSON Response is generated 
![Json Response for Meal.php](https://nr-production-discourse.s3.amazonaws.com/original/2X/3/3c6092be7db28059f2df450317b8bbad6941d61f.png)

#### For Category End-Point:
The following JSON Response is generated 

### For Paging 
The above REST Api provides paging feature.use `page` parameter in the URL Request,

Example,`http://blacky.tech/mealsapi/meals.php?page=1 or 2 or 3 ...so on`

### Note
By default the API gives 10 Entries/Meals per Request per Page

Also on Android Manifest file under application tag,include `android:usesClearTextTraffic=true`, by this way Android knows that its hitting Http request instead of https.
