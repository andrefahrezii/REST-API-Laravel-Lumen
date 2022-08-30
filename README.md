# REST API Laravel Lumen 

# Documentation
- Git Clone https://github.com/andrefahrezii/REST-API-Laravel-Lumen.git
- please setup database settings in .env
![image](https://user-images.githubusercontent.com/81211215/187435609-dfef0028-153a-45d8-b6d5-3df2912e6ec2.png)
- Php Migrate
![image](https://user-images.githubusercontent.com/81211215/187435820-fa99bea9-c963-4a6f-a579-ccada4a638bc.png)
- run laravel lumen with command
    run laravel lumen with command
- Metod
  + Show All Data
    * GET http://localhost:8000/posts/
      ![image](https://user-images.githubusercontent.com/81211215/187436322-a2fbc7a2-5627-4f55-81be-0107fdd9665c.png)
  + Input Data
      note : On the Body tab, friends, select x-www-form-urlencode and in the key section, enter the title and content and don't forget to use the POST method
        * POST http://localhost:8000/posts/
            ![image](https://user-images.githubusercontent.com/81211215/187437165-5ea9260c-7405-4ddd-bda5-f8b61e0dde2d.png)
  + Display data by ID
    note :  in the last slash enter the id, here I will give an example with id 3
            please enter http://localhost:8000/posts/1 and don't forget to use the GET method.
        * http://localhost:8000/posts/3
        ![image](https://user-images.githubusercontent.com/81211215/187438133-8c35c053-efee-4261-8c88-fa2fbcf4e32a.png)
  + Update Data
    note : Now we try to update the data, please, friends, open Postman and enter http://localhost:8000/posts/3
          In the Body tab, friends, select x-www-form-urlencode and in the key section, enter the title and content and don't forget to use the PUT method
        * http://localhost:8000/posts/3
        ![image](https://user-images.githubusercontent.com/81211215/187438680-4ce007d4-2f5d-481c-90c4-b3cafbc73e6b.png)
  + Delete Data
    Note : Now friends, you can try the application using Postman, please enter http://localhost:8000/posts/3 and don't forget to use the DELETE method.
        * http://localhost:8000/posts/3
        ![image](https://user-images.githubusercontent.com/81211215/187439346-cdeaf2f5-5906-4656-b21b-988e95aff3bc.png)
        



  
  
  *
