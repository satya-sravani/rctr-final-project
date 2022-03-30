# React Part Time Class Final Project

## Project Links

- [CodeSandbox Link]()

## Project Description

My project Receipe searching App is about a cooking website for users to find recipes and keep track of the ingredients user needs to shop for or find in the kitchen.

## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Also, define the the React components and the architectural design of your app.

- https://lucid.app/lucidchart/b9021ff2-b732-40fa-aeed-951fa8f2defc/edit?invitationId=inv_1f63e209-ec2d-4c5d-9327-7527bbbce070
- https://lucid.app/lucidchart/b84df27a-c7bf-48f4-9b81-7c2c694ef983/edit?invitationId=inv_f6f8e823-902f-4a84-acbc-e2971c8150e0
- https://lucid.app/lucidchart/f4c22da5-2867-4d45-b4aa-d1539f0f87d7/edit?invitationId=inv_9fe287e0-643b-4fb8-b4bc-5f5e094a7f49


### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP EXAMPLE
- Home Page will contain a search bar for the recipe search term and tabs to input the cuisine type & meal type
- API call will be made using the search term to get recipes and the titles will be displayed to the user
- User can select a recipe title to drill down into the ingredients list and instructions
-Check-Boxes will be displayed for each ingredient so the user can track whether they have the ingredient

#### PostMVP EXAMPLE

- ability for users to see suggested options for replacing the ingredients.

## API

If you opted to make use of an API then use this section to include info about the API you have chosen and a code snippet of the data that it returns and is required for your project. 


```
{
  "from": 1,
  "to": 20,
  "count": 986,
  "_links": {
    "next": {
      "href": "https://api.edamam.com/api/recipes/v2?q=lamb&app_key=%203d9a6e457c84cfb12dd40fe421023e68&field=uri&field=label&field=image&field=images&field=source&field=url&field=yield&field=ingredientLines&field=ingredients&field=calories&field=totalTime&field=cuisineType&field=mealType&field=dishType&mealType=Lunch&_cont=CHcVQBtNNQphDmgVQntAEX4BYlJtAAEOS21JBWUbalB2BAQPUXlSUmoSZ1V3BAYHEmBIADcWZgQmUgdWQGdGAGZGYQRzAAQVLnlSVSBMPkd5BgMbUSYRVTdgMgksRlpSAAcRXTVGcV84SU4%3D&cuisineType=Indian&imageSize=REGULAR&type=public&app_id=a9ce82d3",
      "title": "Next page"
    }
  },
  "hits": [
    {
      "recipe": {
        "uri": "http://www.edamam.com/ontologies/edamam.owl#recipe_2d668f6ca2089032ce80abcd814a8936",
        "label": "Lamb Sausages",
        "image": "https://edamam-product-images.s3.amazonaws.com/web-img/691/69110270a357de1738dd00ceec241492.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e6fdb38c2df654d21f7057b90aca5fdf8c848203fe8e3a62b1ea7ddc16696f17",
        "images": {
          "THUMBNAIL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/691/69110270a357de1738dd00ceec241492-s.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=55f068663ba0a619913ad2e11a0096bee5d97ebbb4a614fb36b0cce0858e756e",
            "width": 100,
            "height": 100
          },
          "SMALL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/691/69110270a357de1738dd00ceec241492-m.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=25d8cfe179b85ad1d40d032bc00753f0df03f690ca4372e0b55eb5cbb7f46652",
            "width": 200,
            "height": 200
          },
          "REGULAR": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/691/69110270a357de1738dd00ceec241492.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e6fdb38c2df654d21f7057b90aca5fdf8c848203fe8e3a62b1ea7ddc16696f17",
            "width": 300,
            "height": 300
          }
        },
        "source": "Martha Stewart",
        "url": "https://www.marthastewart.com/1155033/lamb-sausages",
        "yield": 8,
        "ingredientLines": [
          "1 tablespoon olive oil",
          "6 lamb sausages",
          "Lime wedges, for serving"
        ],
        "ingredients": [
          {
            "text": "1 tablespoon olive oil",
            "quantity": 1,
            "measure": "tablespoon",
            "food": "olive oil",
            "weight": 13.5,
            "foodCategory": "Oils",
            "foodId": "food_b1d1icuad3iktrbqby0hiagafaz7",
            "image": "https://www.edamam.com/food-img/4d6/4d651eaa8a353647746290c7a9b29d84.jpg"
          },
          {
            "text": "6 lamb sausages",
            "quantity": 6,
            "measure": "<unit>",
            "food": "lamb sausages",
            "weight": 840,
            "foodCategory": "meats",
            "foodId": "food_a6pzcv3btrdfeba3r51f7ajjzpo5",
            "image": "https://www.edamam.com/food-img/fc1/fc1e887bb3bcd7006654506686bf4779.jpg"
          },
          {
            "text": "Lime wedges, for serving",
            "quantity": 1,
            "measure": "wedge",
            "food": "Lime",
            "weight": 8.375,
            "foodCategory": "fruit",
            "foodId": "food_av58muyb8kg92fbk0g8g8aui5knv",
            "image": "https://www.edamam.com/food-img/48a/48a123c9576647c4ada6a41df5eeb22a.jpg"
          }
        ],
        "calories": 2490.6525,
        "totalTime": 0,
        "cuisineType": [
          "indian"
        ],
        "mealType": [
          "lunch/dinner"
        ],
        "dishType": [
          "condiments and sauces"
        ]
      },
      "_links": {
        "self": {
          "href": "https://api.edamam.com/api/recipes/v2/2d668f6ca2089032ce80abcd814a8936?type=public&app_id=a9ce82d3&app_key=%203d9a6e457c84cfb12dd40fe421023e68",
          "title": "Self"
        }
      }
    },
    {
      "recipe": {
        "uri": "http://www.edamam.com/ontologies/edamam.owl#recipe_3be6a4c88b061fefd6786de12936c9f2",
        "label": "Quick Lamb Biryani",
        "image": "https://edamam-product-images.s3.amazonaws.com/web-img/0b8/0b89d34ade58e86f1be851737aabcc91.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=4e7a07d7d9f741568825673e9123434227f7ecbc316651ca1ca707c158752527",
        "images": {
          "THUMBNAIL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/0b8/0b89d34ade58e86f1be851737aabcc91-s.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=709c1d8772216a69cd7c244e12a4833c4fbe98dadbf2a17f33cbd7643d029be6",
            "width": 100,
            "height": 100
          },
          "SMALL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/0b8/0b89d34ade58e86f1be851737aabcc91-m.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a6956fcbe0c584ac56ac1c9e95d306a699e5968c38914c17b927e0a152c94bf4",
            "width": 200,
            "height": 200
          },
          "REGULAR": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/0b8/0b89d34ade58e86f1be851737aabcc91.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=4e7a07d7d9f741568825673e9123434227f7ecbc316651ca1ca707c158752527",
            "width": 300,
            "height": 300
          },
          "LARGE": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/0b8/0b89d34ade58e86f1be851737aabcc91-l.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=203e050d5aed2ac894f87cde6038ebc6b451d94c737d38d88877e7600cefd891",
            "width": 600,
            "height": 600
          }
        },
        "source": "BBC Good Food",
        "url": "http://www.bbcgoodfood.com/recipes/4815/",
        "yield": 4,
        "ingredientLines": [
          "1.0 tbsp balti curry paste",
          "400.0ml lamb or chicken stock",
          "200.0g basmati rice , rinsed in cold water",
          "500.0g lean lamb leg steak or neck fillet, cubed",
          "200.0g spinach"
        ],
        "ingredients": [
          {
            "text": "1.0 tbsp balti curry paste",
            "quantity": 1,
            "measure": "tablespoon",
            "food": "curry paste",
            "weight": 16,
            "foodCategory": "condiments and sauces",
            "foodId": "food_aojdol2are6zg7af2nincbe87jot",
            "image": "https://www.edamam.com/food-img/b6a/b6a9ebae5850f42eca0253827603ef9c.jpg"
          },
          {
            "text": "400.0ml lamb or chicken stock",
            "quantity": 400,
            "measure": "milliliter",
            "food": "lamb or chicken stock",
            "weight": 405.768272422116,
            "foodCategory": "canned soup",
            "foodId": "food_bptblvzambd16nbhewqmhaw1rnh5",
            "image": "https://www.edamam.com/food-img/26a/26a10c4cb4e07bab54d8a687ef5ac7d8.jpg"
          },
          {
            "text": "200.0g basmati rice , rinsed in cold water",
            "quantity": 200,
            "measure": "gram",
            "food": "basmati rice",
            "weight": 200,
            "foodCategory": "grains",
            "foodId": "food_a3g7g0kb4xvknbbdl91t8a19a6ci",
            "image": "https://www.edamam.com/food-img/e35/e35ea1529983a3db51a32a1afa7b3837.jpg"
          },
          {
            "text": "500.0g lean lamb leg steak or neck fillet, cubed",
            "quantity": 500,
            "measure": "gram",
            "food": "lamb leg",
            "weight": 500,
            "foodCategory": "meats",
            "foodId": "food_a1egjqqbhgmxpvax5i3vmatvm66l",
            "image": "https://www.edamam.com/food-img/dad/dad70281fdf22cdda2e2d55972190cdf.jpg"
          },
          {
            "text": "200.0g spinach",
            "quantity": 200,
            "measure": "gram",
            "food": "spinach",
            "weight": 200,
            "foodCategory": "vegetables",
            "foodId": "food_aoceuc6bshdej1bbsdammbnj6l6o",
            "image": "https://www.edamam.com/food-img/e6e/e6e4be375c4554ce01c8ea75232efaa6.jpg"
          }
        ],
        "calories": 1986.2214906319618,
        "totalTime": 0,
        "cuisineType": [
          "indian"
        ],
        "mealType": [
          "lunch/dinner"
        ],
        "dishType": [
          "main course",
          "starter"
        ]
      },
      "_links": {
        "self": {
          "href": "https://api.edamam.com/api/recipes/v2/3be6a4c88b061fefd6786de12936c9f2?type=public&app_id=a9ce82d3&app_key=%203d9a6e457c84cfb12dd40fe421023e68",
          "title": "Self"
        }
      }
    },
    {
      "recipe": {
        "uri": "http://www.edamam.com/ontologies/edamam.owl#recipe_2774b45975b105f9a78b8bd953eda42d",
        "label": "Rack of Lamb with Chutney-Mint Glaze",
        "image": "https://edamam-product-images.s3.amazonaws.com/web-img/fda/fda9efe5498e8d4b3e76d93d981d08e9.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=22997f14be220fc43263d14cc7310c99fbf171ceb48e5ba2601c2157bca91ce8",
        "images": {
          "THUMBNAIL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/fda/fda9efe5498e8d4b3e76d93d981d08e9-s.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=978d9f9dadc4efcc329164492e0b1772a4c7e54d22c7992d3babc3b7a6c5242a",
            "width": 100,
            "height": 100
          },
          "SMALL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/fda/fda9efe5498e8d4b3e76d93d981d08e9-m.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=f973e3a463eb841e108dfba36a7f94a1fa29e6296e7c40554d472448d567f1a3",
            "width": 200,
            "height": 200
          },
          "REGULAR": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/fda/fda9efe5498e8d4b3e76d93d981d08e9.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=22997f14be220fc43263d14cc7310c99fbf171ceb48e5ba2601c2157bca91ce8",
            "width": 300,
            "height": 300
          }
        },
        "source": "Epicurious",
        "url": "https://www.epicurious.com/recipes/food/views/rack-of-lamb-with-chutney-mint-glaze-105990",
        "yield": 4,
        "ingredientLines": [
          "2 1 1/4-pound racks of lamb, trimmed",
          "2/3 cup mango chutney",
          "1/2 cup mint jelly",
          "2 tablespoons chopped fresh mint plus mint sprigs for garnish"
        ],
        "ingredients": [
          {
            "text": "2 1 1/4-pound racks of lamb, trimmed",
            "quantity": 2.5,
            "measure": "pound",
            "food": "racks of lamb",
            "weight": 1133.980925,
            "foodCategory": "meats",
            "foodId": "food_angq554ak5jmcyasmt9xca4h2d3p",
            "image": "https://www.edamam.com/food-img/a90/a90c6b8376ae5feeaeeb3b81505a2089.jpg"
          },
          {
            "text": "2/3 cup mango chutney",
            "quantity": 0.6666666666666666,
            "measure": "cup",
            "food": "mango chutney",
            "weight": 213.33333333333331,
            "foodCategory": "sugar syrups",
            "foodId": "food_b6nq9p3bqu2ydrbayvipqbpt22qx",
            "image": "https://www.edamam.com/food-img/55e/55e9572a1c35eeedc4900c5430f821b8.jpg"
          },
          {
            "text": "1/2 cup mint jelly",
            "quantity": 0.5,
            "measure": "cup",
            "food": "jelly",
            "weight": 160.00000000270512,
            "foodCategory": "sugar syrups",
            "foodId": "food_bzsx4atbph30cebveok2ebmgwrq8",
            "image": "https://www.edamam.com/food-img/42b/42ba8bb2c0e13f6e69b3af18f0f641ae.jpg"
          },
          {
            "text": "2 tablespoons chopped fresh mint plus mint sprigs for garnish",
            "quantity": 2,
            "measure": "tablespoon",
            "food": "mint",
            "weight": 11.4,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_bxl4xoga4owdkeay51sy8anesxj5",
            "image": "https://www.edamam.com/food-img/7f0/7f01cc4f71c5c6ad31051ed74b9c058b.jpg"
          },
          {
            "text": "2 tablespoons chopped fresh mint plus mint sprigs for garnish",
            "quantity": 1,
            "measure": "sprig",
            "food": "mint",
            "weight": 11.4,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_bxl4xoga4owdkeay51sy8anesxj5",
            "image": "https://www.edamam.com/food-img/7f0/7f01cc4f71c5c6ad31051ed74b9c058b.jpg"
          }
        ],
        "calories": 4059.070599937521,
        "totalTime": 0,
        "cuisineType": [
          "indian"
        ],
        "mealType": [
          "lunch/dinner"
        ],
        "dishType": [
          "main course"
        ]
      },
      "_links": {
        "self": {
          "href": "https://api.edamam.com/api/recipes/v2/2774b45975b105f9a78b8bd953eda42d?type=public&app_id=a9ce82d3&app_key=%203d9a6e457c84cfb12dd40fe421023e68",
          "title": "Self"
        }
      }
    },
    {
      "recipe": {
        "uri": "http://www.edamam.com/ontologies/edamam.owl#recipe_54b11886c46d0d93cdedbdd71b97cde9",
        "label": "Lamb Curry",
        "image": "https://edamam-product-images.s3.amazonaws.com/web-img/301/301807ab3289b279cbcb49e144f49133.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=8bf9d547acce4a72c03a8ac5fb5b2490b86735c3a0563e2769d620237858eff0",
        "images": {
          "THUMBNAIL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/301/301807ab3289b279cbcb49e144f49133-s.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a29f16a29975b58dc30cc6a38cf386c88c8628aee5e48eff874965350e639ecd",
            "width": 100,
            "height": 100
          },
          "SMALL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/301/301807ab3289b279cbcb49e144f49133-m.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b591830a7c9646a804856d27a59bb56a4e8fc3d396455adc014d429d13d45421",
            "width": 200,
            "height": 200
          },
          "REGULAR": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/301/301807ab3289b279cbcb49e144f49133.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=8bf9d547acce4a72c03a8ac5fb5b2490b86735c3a0563e2769d620237858eff0",
            "width": 300,
            "height": 300
          },
          "LARGE": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/301/301807ab3289b279cbcb49e144f49133-l.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=dece6c7fae6cece17c052f7f47c09c52fb04480d2a3f5618286ad176f5621df2",
            "width": 600,
            "height": 600
          }
        },
        "source": "Simply Recipes",
        "url": "http://simplyrecipes.com/recipes/lamb_curry/",
        "yield": 6,
        "ingredientLines": [
          "2 lamb shanks AND 2 lamb shoulder steaks (yielding about 2 lbs of meat without the bone)",
          "1 large onions, chopped, about 3 1/2 cups",
          "3-5 cloves of garlic, crushed",
          "2-3 Tbsp ghee (clarified butter) or 1 Tbsp olive oil with butter",
          "2-3 Tbsp curry powder",
          "2 tsp salt",
          "1 Tbsp black pepper",
          "1 Tbsp ground coriander",
          "1 Tbsp cumin",
          "1 tsp fresh rosemary, chopped",
          "1 tsp thyme, dried",
          "1/2 Meyer lemon sliced (with rind)",
          "2 peeled and chopped apples (tart green granny smith if possible), about 2 cups",
          "1/4 cup of raisins (my addition to Maria",
          "1 1/2 cups chicken broth*",
          "8-12 small potatoes, quartered, about 1 1/2 pounds",
          "Chutney, yogurt, rice"
        ],
        "ingredients": [
          {
            "text": "2 lamb shanks AND 2 lamb shoulder steaks (yielding about 2 lbs of meat without the bone)",
            "quantity": 2,
            "measure": "<unit>",
            "food": "lamb shanks",
            "weight": 906,
            "foodCategory": "meats",
            "foodId": "food_ai1zuazbhdt1cgbp57he3b0emm7d",
            "image": null
          },
          {
            "text": "2 lamb shanks AND 2 lamb shoulder steaks (yielding about 2 lbs of meat without the bone)",
            "quantity": 2,
            "measure": "steak",
            "food": "lamb shoulder",
            "weight": 680,
            "foodCategory": "meats",
            "foodId": "food_aubt242bs7x1shagh2ibkar7bckb",
            "image": "https://www.edamam.com/food-img/35c/35cd09ea1665452ca64fccf9e32df4e9.jpg"
          },
          {
            "text": "1 large onions, chopped, about 3 1/2 cups",
            "quantity": 1,
            "measure": "<unit>",
            "food": "onions",
            "weight": 150,
            "foodCategory": "vegetables",
            "foodId": "food_bmrvi4ob4binw9a5m7l07amlfcoy",
            "image": "https://www.edamam.com/food-img/205/205e6bf2399b85d34741892ef91cc603.jpg"
          },
          {
            "text": "3-5 cloves of garlic, crushed",
            "quantity": 4,
            "measure": "clove",
            "food": "garlic",
            "weight": 12,
            "foodCategory": "vegetables",
            "foodId": "food_avtcmx6bgjv1jvay6s6stan8dnyp",
            "image": "https://www.edamam.com/food-img/6ee/6ee142951f48aaf94f4312409f8d133d.jpg"
          },
          {
            "text": "2-3 Tbsp ghee (clarified butter) or 1 Tbsp olive oil with butter",
            "quantity": 2.5,
            "measure": "tablespoon",
            "food": "olive oil",
            "weight": 33.75,
            "foodCategory": "Oils",
            "foodId": "food_b1d1icuad3iktrbqby0hiagafaz7",
            "image": "https://www.edamam.com/food-img/4d6/4d651eaa8a353647746290c7a9b29d84.jpg"
          },
          {
            "text": "2-3 Tbsp curry powder",
            "quantity": 2.5,
            "measure": "tablespoon",
            "food": "curry powder",
            "weight": 15.75,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_ao4koeoajh7yjxaq2knzrbv55y8o",
            "image": "https://www.edamam.com/food-img/9ce/9ce02a2887385fd2adaec8dd8adcf9c5.jpg"
          },
          {
            "text": "2 tsp salt",
            "quantity": 2,
            "measure": "teaspoon",
            "food": "salt",
            "weight": 12,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_btxz81db72hwbra2pncvebzzzum9",
            "image": "https://www.edamam.com/food-img/694/6943ea510918c6025795e8dc6e6eaaeb.jpg"
          },
          {
            "text": "1 Tbsp black pepper",
            "quantity": 1,
            "measure": "tablespoon",
            "food": "black pepper",
            "weight": 6.9,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_b6ywzluaaxv02wad7s1r9ag4py89",
            "image": "https://www.edamam.com/food-img/c6e/c6e5c3bd8d3bc15175d9766971a4d1b2.jpg"
          },
          {
            "text": "1 Tbsp ground coriander",
            "quantity": 1,
            "measure": "tablespoon",
            "food": "coriander",
            "weight": 5,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_afpcy6rb44nx6gbfff63ga2cqksw",
            "image": "https://www.edamam.com/food-img/a90/a901cee0b9028841d258f5d07b5924e7.jpg"
          },
          {
            "text": "1 Tbsp cumin",
            "quantity": 1,
            "measure": "tablespoon",
            "food": "cumin",
            "weight": 6,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_a8jjbx4biqndasapojdb5by3e92e",
            "image": "https://www.edamam.com/food-img/07e/07e2a4eb77ce46591033846504817d35.jpg"
          },
          {
            "text": "1 tsp fresh rosemary, chopped",
            "quantity": 1,
            "measure": "teaspoon",
            "food": "fresh rosemary",
            "weight": 0.7,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_b6tm2t2blxi7okaeiv91wb8bmygq",
            "image": "https://www.edamam.com/food-img/0ac/0ac8f7cf6f2d0ad7b1a2f9900fae44f3.jpg"
          },
          {
            "text": "1 tsp thyme, dried",
            "quantity": 1,
            "measure": "teaspoon",
            "food": "thyme",
            "weight": 0.8,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_b3o3cj7a5gskecb0ufphtadnbfqb",
            "image": "https://www.edamam.com/food-img/3e7/3e7cf3c8d767a90b906447f5e74059f7.jpg"
          },
          {
            "text": "1/2 Meyer lemon sliced (with rind)",
            "quantity": 0.5,
            "measure": "<unit>",
            "food": "lemon",
            "weight": 29,
            "foodCategory": "fruit",
            "foodId": "food_a6uzc62astrxcgbtzyq59b6fncrr",
            "image": "https://www.edamam.com/food-img/70a/70acba3d4c734d7c70ef4efeed85dc8f.jpg"
          },
          {
            "text": "2 peeled and chopped apples (tart green granny smith if possible), about 2 cups",
            "quantity": 2,
            "measure": "<unit>",
            "food": "granny smith",
            "weight": 349.2,
            "foodCategory": "fruit",
            "foodId": "food_b4m99bgatuhmfybeq0d7xa9uvr1b",
            "image": "https://www.edamam.com/food-img/288/288a6646dd6bb05a482f4405bf6e2861.jpg"
          },
          {
            "text": "1/4 cup of raisins (my addition to Maria",
            "quantity": 0.25,
            "measure": "cup",
            "food": "raisins",
            "weight": 36.25,
            "foodCategory": "fruit",
            "foodId": "food_a3qcdxyb09op1hbwstv5cbmoqc3d",
            "image": "https://www.edamam.com/food-img/159/159e247350db62e1f87b0636a53687f5.jpg"
          },
          {
            "text": "1 1/2 cups chicken broth*",
            "quantity": 1.5,
            "measure": "cup",
            "food": "chicken broth",
            "weight": 360,
            "foodCategory": "canned soup",
            "foodId": "food_bptblvzambd16nbhewqmhaw1rnh5",
            "image": "https://www.edamam.com/food-img/26a/26a10c4cb4e07bab54d8a687ef5ac7d8.jpg"
          },
          {
            "text": "8-12 small potatoes, quartered, about 1 1/2 pounds",
            "quantity": 1.5,
            "measure": "pound",
            "food": "potatoes",
            "weight": 680.388555,
            "foodCategory": "vegetables",
            "foodId": "food_abiw5baauresjmb6xpap2bg3otzu",
            "image": "https://www.edamam.com/food-img/651/6512e82417bce15c2899630c1a2799df.jpg"
          },
          {
            "text": "Chutney, yogurt, rice",
            "quantity": 0,
            "measure": null,
            "food": "Chutney",
            "weight": 0,
            "foodCategory": "sugar syrups",
            "foodId": "food_b6nq9p3bqu2ydrbayvipqbpt22qx",
            "image": "https://www.edamam.com/food-img/55e/55e9572a1c35eeedc4900c5430f821b8.jpg"
          },
          {
            "text": "Chutney, yogurt, rice",
            "quantity": 0,
            "measure": null,
            "food": "yogurt",
            "weight": 0,
            "foodCategory": "yogurt",
            "foodId": "food_a79ojfkbgdeekgblqmky9bunr8f6",
            "image": "https://www.edamam.com/food-img/933/933eb3791b3a2175e007f1607d56b7e2.jpg"
          },
          {
            "text": "Chutney, yogurt, rice",
            "quantity": 0,
            "measure": null,
            "food": "rice",
            "weight": 0,
            "foodCategory": "grains",
            "foodId": "food_bpumdjzb5rtqaeabb0kbgbcgr4t9",
            "image": "https://www.edamam.com/food-img/0fc/0fc9fa8a3e0276198d75b2e259068f8a.jpg"
          }
        ],
        "calories": 4941.979390512502,
        "totalTime": 0,
        "cuisineType": [
          "indian"
        ],
        "mealType": [
          "lunch/dinner"
        ],
        "dishType": [
          "starter"
        ]
      },
      "_links": {
        "self": {
          "href": "https://api.edamam.com/api/recipes/v2/54b11886c46d0d93cdedbdd71b97cde9?type=public&app_id=a9ce82d3&app_key=%203d9a6e457c84cfb12dd40fe421023e68",
          "title": "Self"
        }
      }
    },
    {
      "recipe": {
        "uri": "http://www.edamam.com/ontologies/edamam.owl#recipe_3190446907db7d77c0494b258a471472",
        "label": "Cook the Book: Indian Lamb and Carrot Salad",
        "image": "https://edamam-product-images.s3.amazonaws.com/web-img/840/84077cefb33823e08c2633d93c0b7e6d.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=d645d81e190193bad8e930ceb301558cbb6f3a82335128faaf36c49ff68a5a27",
        "images": {
          "THUMBNAIL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/840/84077cefb33823e08c2633d93c0b7e6d-s.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=1a2f616f5f51710381ba3525f936f27c8c4c0e70def158410c4c7d8f616bf77f",
            "width": 100,
            "height": 100
          },
          "SMALL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/840/84077cefb33823e08c2633d93c0b7e6d-m.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=f68badbf849e18d8ef22e523c3e29e9a9bcbf048a2d18d955e1125f1ca29b232",
            "width": 200,
            "height": 200
          },
          "REGULAR": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/840/84077cefb33823e08c2633d93c0b7e6d.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=d645d81e190193bad8e930ceb301558cbb6f3a82335128faaf36c49ff68a5a27",
            "width": 300,
            "height": 300
          }
        },
        "source": "Serious Eats",
        "url": "http://www.seriouseats.com/recipes/2009/01/jamie-oliver-indian-lamb-and-carrot-salad-recipe.html",
        "yield": 4,
        "ingredientLines": [
          "1 1/4 pounds good-quality coarsely ground lamb",
          "2 teaspoons garam masala",
          "Sea salt",
          "1 pound carrots (mixed colors if possible), peeled",
          "1 tablespoon sesame seeds",
          "A small bunch of fresh cilantro, leaves picked",
          "A small bunch of fresh mint, leaves picked",
          "1 teaspoon cumin seeds",
          "3 shallots or 1 small red onion, peeled",
          "Zest and juice of 1 lemon",
          "1 heaped teaspoon freshly grated ginger",
          "Extra virgin olive oil"
        ],
        "ingredients": [
          {
            "text": "1 1/4 pounds good-quality coarsely ground lamb",
            "quantity": 1.25,
            "measure": "pound",
            "food": "ground lamb",
            "weight": 566.9904625,
            "foodCategory": "meats",
            "foodId": "food_a6pzcv3btrdfeba3r51f7ajjzpo5",
            "image": "https://www.edamam.com/food-img/fc1/fc1e887bb3bcd7006654506686bf4779.jpg"
          },
          {
            "text": "2 teaspoons garam masala",
            "quantity": 2,
            "measure": "teaspoon",
            "food": "masala",
            "weight": 3.8,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_avzem7oamop4dsa5wb65obt5ldgi",
            "image": "https://www.edamam.com/food-img/c3f/c3f96d47d334b92f0120ff0b3a512ec3.jpg"
          },
          {
            "text": "Sea salt",
            "quantity": 0,
            "measure": null,
            "food": "Sea salt",
            "weight": 8.147896995,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_a1vgrj1bs8rd1majvmd9ubz8ttkg",
            "image": "https://www.edamam.com/food-img/694/6943ea510918c6025795e8dc6e6eaaeb.jpg"
          },
          {
            "text": "1 pound carrots (mixed colors if possible), peeled",
            "quantity": 1,
            "measure": "pound",
            "food": "carrots",
            "weight": 453.59237,
            "foodCategory": "vegetables",
            "foodId": "food_ai215e5b85pdh5ajd4aafa3w2zm8",
            "image": "https://www.edamam.com/food-img/121/121e33fce0bb9546ed7d060b6c114e29.jpg"
          },
          {
            "text": "1 tablespoon sesame seeds",
            "quantity": 1,
            "measure": "tablespoon",
            "food": "sesame seeds",
            "weight": 9,
            "foodCategory": "plant-based protein",
            "foodId": "food_bvxfnx8bwz2q3abs04kd6bbuf9w8",
            "image": "https://www.edamam.com/food-img/291/291b355a7a0948716243164427697279.jpg"
          },
          {
            "text": "A small bunch of fresh cilantro, leaves picked",
            "quantity": 1,
            "measure": "bunch",
            "food": "cilantro",
            "weight": 30,
            "foodCategory": "vegetables",
            "foodId": "food_alhzhuwb4lc7jnb5s6f02by60bzp",
            "image": "https://www.edamam.com/food-img/d57/d57e375b6ff99a90c7ee2b1990a1af36.jpg"
          },
          {
            "text": "A small bunch of fresh mint, leaves picked",
            "quantity": 1,
            "measure": "bunch",
            "food": "mint",
            "weight": 22.5,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_bxl4xoga4owdkeay51sy8anesxj5",
            "image": "https://www.edamam.com/food-img/7f0/7f01cc4f71c5c6ad31051ed74b9c058b.jpg"
          },
          {
            "text": "1 teaspoon cumin seeds",
            "quantity": 1,
            "measure": "teaspoon",
            "food": "cumin seeds",
            "weight": 2.1,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_a8jjbx4biqndasapojdb5by3e92e",
            "image": "https://www.edamam.com/food-img/07e/07e2a4eb77ce46591033846504817d35.jpg"
          },
          {
            "text": "3 shallots or 1 small red onion, peeled",
            "quantity": 3,
            "measure": "<unit>",
            "food": "red onion",
            "weight": 210,
            "foodCategory": "vegetables",
            "foodId": "food_bmrvi4ob4binw9a5m7l07amlfcoy",
            "image": "https://www.edamam.com/food-img/205/205e6bf2399b85d34741892ef91cc603.jpg"
          },
          {
            "text": "Zest and juice of 1 lemon",
            "quantity": 1,
            "measure": "<unit>",
            "food": "lemon",
            "weight": 58,
            "foodCategory": "fruit",
            "foodId": "food_a6uzc62astrxcgbtzyq59b6fncrr",
            "image": "https://www.edamam.com/food-img/70a/70acba3d4c734d7c70ef4efeed85dc8f.jpg"
          },
          {
            "text": "1 heaped teaspoon freshly grated ginger",
            "quantity": 1,
            "measure": "teaspoon",
            "food": "ginger",
            "weight": 2,
            "foodCategory": "vegetables",
            "foodId": "food_bi2ki2xb5zmmvbaiwf7ztbgktzp6",
            "image": "https://www.edamam.com/food-img/b9c/b9c06ef451ef29513880af0a53ebbaa6.jpg"
          },
          {
            "text": "Extra virgin olive oil",
            "quantity": 0,
            "measure": null,
            "food": "Extra virgin olive oil",
            "weight": 18.468566521999996,
            "foodCategory": "Oils",
            "foodId": "food_b1d1icuad3iktrbqby0hiagafaz7",
            "image": "https://www.edamam.com/food-img/4d6/4d651eaa8a353647746290c7a9b29d84.jpg"
          }
        ],
        "calories": 2136.80710400448,
        "totalTime": 81,
        "cuisineType": [
          "indian",
          "mediterranean"
        ],
        "mealType": [
          "lunch/dinner"
        ],
        "dishType": [
          "salad"
        ]
      },
      "_links": {
        "self": {
          "href": "https://api.edamam.com/api/recipes/v2/3190446907db7d77c0494b258a471472?type=public&app_id=a9ce82d3&app_key=%203d9a6e457c84cfb12dd40fe421023e68",
          "title": "Self"
        }
      }
    },
    {
      "recipe": {
        "uri": "http://www.edamam.com/ontologies/edamam.owl#recipe_4451a3b0998018629490bd9ba891290c",
        "label": "Lamb Vindaloo",
        "image": "https://edamam-product-images.s3.amazonaws.com/web-img/047/0479b4a7f1643dba7a9fa48ecbb2b549.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=2bafc3066720d44bae621f34c0281fed130565797af329c467a7ff8ea3bce981",
        "images": {
          "THUMBNAIL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/047/0479b4a7f1643dba7a9fa48ecbb2b549-s.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=7c432c06477d0317a0723ca8b0b076a0bbe5fb3ab074b429e345254868fdd7e1",
            "width": 100,
            "height": 100
          },
          "SMALL": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/047/0479b4a7f1643dba7a9fa48ecbb2b549-m.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=46febc5b044eb50b94f076e5e25ee04ca1a933493bbb39a850f83eae1f46136f",
            "width": 200,
            "height": 200
          },
          "REGULAR": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/047/0479b4a7f1643dba7a9fa48ecbb2b549.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=2bafc3066720d44bae621f34c0281fed130565797af329c467a7ff8ea3bce981",
            "width": 300,
            "height": 300
          },
          "LARGE": {
            "url": "https://edamam-product-images.s3.amazonaws.com/web-img/047/0479b4a7f1643dba7a9fa48ecbb2b549-l.jpg?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEG0aCXVzLWVhc3QtMSJHMEUCIBKhlYQMl3zT4Sy7sho0E7tFMewFoPMQnUGq1oYMYxyGAiEAkwa7N8iv2pfBu5uDVfl1R2%2BdpaHOa%2F6bj%2Fhl%2BRKY2bIqgwQI9v%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgwxODcwMTcxNTA5ODYiDPQHj5rA45eN%2F3RP4CrXA2uQgO2GQq6vHER7G4YfU%2BuBHxgNEcwAlh1DQdS7mvm0C7fswECoKg1kf3GFECUC8Mfj88DrL8ScotF118VatVa0X2qwXkITFlnJT1VhvQlg%2BmTnQKuIsfRvuS1kHHBqt65m9LNZoQCp4jmiq%2F4Zrnmuwf0JOn9L%2ByTz1ErX%2BZfQ7EEionMFJekKPXvvmVzaepPapusbq4K0d%2BxqumSdc%2Fmgz7GcnPLoMTByuk3GFnPUU73dczMpU6yu7agcutlPduH9%2FBaeO65vFYyPs67qHM5HK7qmNgnG9g3TejTLjKPAVZGPeoBaV4USNFCyap8QFXqvEYkPjebOZAGb3Rzu9ndDxlNIwcUH500qYDVKDr6ofcmckBGXFRmyZpyA63bWSN9j%2FlHY3bgR1hVOjOa4ttxidqVGYek2%2BJyvCBLyGYkMFsc%2FuiKdEqXn3Ge%2Fki5StplD5MKv5ngSyPPBSwQV6xFOK%2FIHrL74ccgse%2FeuCB1ZKhpOAeugRuJwysS8zLGgVfZtbRWk%2BCy0dYpcV49jHbi9KmK1kXqZoJks%2B5MgkRhhmz1CFZRd4KAt71gGL9q17ugC5HqGPzwvPbnofRwHCkVjDjDS4Jke5XAfphQBE04n%2FYCyy6yGwjDz%2BJKSBjqlAQFbdVOWOC%2F0wVNzBcl8hN5Hpr5hJN6ZB5wTJycQLr41Pb9NO37iy1IWudLLCkEfmDCURMKL%2FVngB4hRzFmZKExseiS5Be%2Bl1e7PIMYVP2Ptd6HYizgdv6ufM8MyNr6lun3Oq8JbgFdn9FGzhvgPdMWqxHtJqSanE33YP6TV%2F%2F%2FG1IVX8bT90QXGWtbehTh0p5cKCSZeahXXdgCqHiXsh8GGP0dXKg%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220330T220359Z&X-Amz-SignedHeaders=host&X-Amz-Expires=3600&X-Amz-Credential=ASIASXCYXIIFI7XOFLFI%2F20220330%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=3f240a474fafda6ea647566a162970f1adc26b9f3cdb4f13187d2e05df681e77",
            "width": 600,
            "height": 600
          }
        },
        "source": "Food52",
        "url": "https://food52.com/recipes/27703-lamb-vindaloo",
        "yield": 6,
        "ingredientLines": [
          "1 1/2 tablespoons grainy mustard",
          "1 1/2 teaspoons ground cumin",
          "3/4 teaspoon ground turmeric",
          "1 teaspoon cayenne pepper (** adjust depending on your heat tolerance .. see notes)",
          "1 teaspoon salt",
          "1 teaspoon red wine vinegar",
          "2 tablespoons olive oil",
          "1 small onion, peeled \\u0026amp; cut into fine half-rings",
          "6 large cloves garlic, minced",
          "2 pounds boned shoulder of lamb -- cut into 1? cubes",
          "2/3 cup canned coconut milk -- well stirred",
          "2/3 cup water",
          "1 green chili (** optional)"
        ],
        "ingredients": [
          {
            "text": "1 1/2 tablespoons grainy mustard",
            "quantity": 1.5,
            "measure": "tablespoon",
            "food": "mustard",
            "weight": 23.34374999960535,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_a34cdj5b0kyuhfbov30xcb50u4dv",
            "image": "https://www.edamam.com/food-img/e23/e238f2e4cfa6aa1a30f46dc73e7344eb.jpg"
          },
          {
            "text": "1 1/2 teaspoons ground cumin",
            "quantity": 1.5,
            "measure": "teaspoon",
            "food": "cumin",
            "weight": 3.1500000000000004,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_a8jjbx4biqndasapojdb5by3e92e",
            "image": "https://www.edamam.com/food-img/07e/07e2a4eb77ce46591033846504817d35.jpg"
          },
          {
            "text": "3/4 teaspoon ground turmeric",
            "quantity": 0.75,
            "measure": "teaspoon",
            "food": "ground turmeric",
            "weight": 2.25,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_bc3ig84amucgmwba3vixyatnyd9b",
            "image": "https://www.edamam.com/food-img/03e/03eb469286b3caf1ae9c13e4eba13587.jpg"
          },
          {
            "text": "1 teaspoon cayenne pepper (** adjust depending on your heat tolerance .. see notes)",
            "quantity": 1,
            "measure": "teaspoon",
            "food": "cayenne pepper",
            "weight": 1.8,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_a8iooz3aris8gba605l07brngnrx",
            "image": "https://www.edamam.com/food-img/374/3742b9434a0fb66a45e0dd6d227ba669.jpg"
          },
          {
            "text": "1 teaspoon salt",
            "quantity": 1,
            "measure": "teaspoon",
            "food": "salt",
            "weight": 6,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_btxz81db72hwbra2pncvebzzzum9",
            "image": "https://www.edamam.com/food-img/694/6943ea510918c6025795e8dc6e6eaaeb.jpg"
          },
          {
            "text": "1 teaspoon red wine vinegar",
            "quantity": 1,
            "measure": "teaspoon",
            "food": "red wine vinegar",
            "weight": 5,
            "foodCategory": "Condiments and sauces",
            "foodId": "food_ad6iyy1anmzb49a817rgnabnz8c9",
            "image": "https://www.edamam.com/food-img/dc8/dc8e998b32b8d45ba15c1b1e6711e958.jpg"
          },
          {
            "text": "2 tablespoons olive oil",
            "quantity": 2,
            "measure": "tablespoon",
            "food": "olive oil",
            "weight": 27,
            "foodCategory": "Oils",
            "foodId": "food_b1d1icuad3iktrbqby0hiagafaz7",
            "image": "https://www.edamam.com/food-img/4d6/4d651eaa8a353647746290c7a9b29d84.jpg"
          },
          {
            "text": "1 small onion, peeled \\u0026amp; cut into fine half-rings",
            "quantity": 1,
            "measure": "<unit>",
            "food": "onion",
            "weight": 70,
            "foodCategory": "vegetables",
            "foodId": "food_bmrvi4ob4binw9a5m7l07amlfcoy",
            "image": "https://www.edamam.com/food-img/205/205e6bf2399b85d34741892ef91cc603.jpg"
          },
          {
            "text": "6 large cloves garlic, minced",
            "quantity": 6,
            "measure": "clove",
            "food": "garlic",
            "weight": 30,
            "foodCategory": "vegetables",
            "foodId": "food_avtcmx6bgjv1jvay6s6stan8dnyp",
            "image": "https://www.edamam.com/food-img/6ee/6ee142951f48aaf94f4312409f8d133d.jpg"
          },
          {
            "text": "2 pounds boned shoulder of lamb -- cut into 1? cubes",
            "quantity": 2,
            "measure": "pound",
            "food": "shoulder of lamb",
            "weight": 907.18474,
            "foodCategory": "meats",
            "foodId": "food_aubt242bs7x1shagh2ibkar7bckb",
            "image": "https://www.edamam.com/food-img/35c/35cd09ea1665452ca64fccf9e32df4e9.jpg"
          },
          {
            "text": "2/3 cup canned coconut milk -- well stirred",
            "quantity": 0.6666666666666666,
            "measure": "cup",
            "food": "canned coconut milk",
            "weight": 150.66666666666666,
            "foodCategory": "non-dairy beverages",
            "foodId": "food_by1k6v2adj7drhbq9w1rpbpen9ms",
            "image": "https://www.edamam.com/food-img/671/671f7528eadb1b01efb53243d0ef0f80.JPG"
          },
          {
            "text": "2/3 cup water",
            "quantity": 0.6666666666666666,
            "measure": "cup",
            "food": "water",
            "weight": 158,
            "foodCategory": "water",
            "foodId": "food_a99vzubbk1ayrsad318rvbzr3dh0",
            "image": "https://www.edamam.com/food-img/5dd/5dd9d1361847b2ca53c4b19a8f92627e.jpg"
          },
          {
            "text": "1 green chili (** optional)",
            "quantity": 1,
            "measure": "<unit>",
            "food": "green chili",
            "weight": 45,
            "foodCategory": "vegetables",
            "foodId": "food_bv2gevdbd1orbiarnp1vfaez1r85",
            "image": "https://www.edamam.com/food-img/73f/73ff2eeb21372fe15b0ec51f9ecf368d.jpeg"
          }
        ],
        "calories": 3060.673796933097,
        "totalTime": 0,
        "cuisineType": [
          "indian"
        ],
        "mealType": [
          "lunch/dinner"
        ],
        "dishType": [
          "main course"
        ]
      },
      "_links": {
        "self": {
          "href": "https://api.edamam.com/api/recipes/v2/4451a3b0998018629490bd9ba891290c?type=public&app_id=a9ce82d3&app_key=%203d9a6e457c84cfb12dd40fe421023e68",
          "title": "Self"
        }
      }
    }
    
    ```

## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| Header | This will render the header include the nav | 
| Footer | This will render the header include the nav | 


## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project such as Axios-For making Endpoint Calls, Material UI and Forms. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
