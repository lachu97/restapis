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
![Json Response for Meals](http://blacky.tech/meals/jsonresp.png)

***
#### For Category End-Point:
![Json Response for Category](http://blacky.tech/meals/catresp.png)


***

### For Paging 
The above REST Api provides paging feature.use `page` parameter in the URL Request,

Example,`http://blacky.tech/mealsapi/meals.php?page=1 or 2 or 3 ...so on`

### Note
By default the API gives 10 Entries/Meals per Request per Page

Also on Android Manifest file under application tag,include `android:usesClearTextTraffic=true`, by this way Android knows that its hitting Http request instead of Https.
