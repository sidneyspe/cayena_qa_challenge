# Cayena API test - Features

## Newman
Install newman using the following command:

`npm i -g newman`

## Execute tests

To run the tests, please run the following command:

`newman run <features_postman_file> -e <enviroment_postman_file>`

example:

``` 
newman run Cayena_features.postman_collection.json -e Cayena_QA_Enviroment.postman_environment.json 
```

