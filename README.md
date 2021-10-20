# Meals DB REST API for Mobile Team Practise
A rest apis for Mobile team for practise
# Find the below Endpoints for -GET Request.
***
## GET-Endpoints

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
***
### For Searchig A Particular Meals from Category:
Use the below endpoint for sorting based on Category.
`http://blacky.tech/mealsapi/search.php?catid=15`
Here,the catid is a required pareameter and of type Integer.

### For Paging 
The above REST Api provides paging feature.use `page` parameter in the URL Request,

Example,`http://blacky.tech/mealsapi/meals.php?page=1 or 2 or 3 ...so on`

### Note
By default the API gives 10 Entries/Meals per Request per Page

Also on Android Manifest file under application tag,include `android:usesClearTextTraffic=true`, by this way Android knows that its hitting Http request instead of Https.
