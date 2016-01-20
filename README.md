# adnext

**Show User By Id**
----
  Returns json data about a single user.

* **URL**

  web/v1/user/getById?{userid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `userid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{"userid":"PLCGY4SDAC","username":"nishan@gmail.com","userpassword":"MTIzNDU2Nzg5"}`
 
* **Error Response:**
  No Error Response returning
___________________________________________________________________________________________________________________________

**User Login**
----
  Returns json data about a single user.

* **URL**

  /web/v1/user/getUserLogin?{username}&{userpassword}

* **Method:**

  `POST`
  
*  **URL Params**

   **Required:**
 
   `username=[String]`
   `userpassword=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `[{"userid": "3PUT5KBBZK","username": "aj@gmail.com"}]`
 
* **Error Response:**

  * **No Error Response returning** <br />
  
__________________________________________________________________________________________________________________________

**Get Advertisement By Id**
----
  Returns json data about a single Advertisement.

* **URL**

  /web/v1/advertisement/getByAdvertisementId?{advertisementid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `advertisementid=["String"]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />`{"timestamp": 1421193600000,"adtimerange": "2hr","strttime": "06.00pm","endtime": "12.00pm","userpayment": 3000,"userid": "2SWVABJT5F","advertisementId": "G613Z5DFQL"}`
 
* **Error Response:**

  * **No Error Response returning** <br />

__________________________________________________________________________________________________________________________

**Get Advertisement By UserId**
----
  Returns json data about a list of Advertisements.

* **URL**

  /web/v1/advertisement/getByUserId?{userid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `userid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `[{"advertisementid": "G613Z5DFQL","timestamp": 1421193600000,"adtimerange": "2hr","strttime": "06.00pm","endtime": "12.00pm","userpayment": 3000,"username": "sandunwikramasinha@gmail.com"},{"advertisementid":"XI9VASNI0M","timestamp": 1421193600000,"adtimerange": "1hr",strttime":"10.00pm","endtime": "12.00pm","userpayment": 300,"username": "sandunwikramasinha@gmail.com"}]`
 
* **Error Response:**

  * **No Error Response returning** <br />
   
__________________________________________________________________________________________________________________________

  
