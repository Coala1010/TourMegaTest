# TourMega Test Project

### This project includes GOOGLE API_KEY. Don't share it with others

I registered a user on https://staging.tourmega.com/

  Then I can get auth token from /api/v2/login by using my credential
    
Next, By using that token, I also got the data from /api/v2/cities

     "data": [
        {
            "id": 1,
            "name": "Dhaka",
            "country_id": 19,
            "slug": "dhaka"
        },
        {
            "id": 2,
            "name": "Phnom Penh",
            "country_id": 115,
            "slug": "phnom-penh"
        },
        {
            "id": 3,
            "name": "Beijing",
            "country_id": 46,
            "slug": "beijing"
        },
        ...........
      ]

The other apis are similar
If you want to integrate other apis, it would be no problem for me :)

------------------------------------------------------------------------------------

I integrated JEST for unit test

you can see the tours list according to mock area
