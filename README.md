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

**Get Advertisement By advertisementId**
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

**Get Advertisement By Date**
----
  Returns json data about list of Advertisement.

* **URL**

  /web/v1/advertisement/getByTimestamp?{timestamp}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `timestamp=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `[{"advertisementid": "G613Z5DFQL","timestamp": 1421193600000,"adtimerange": "2hr","strttime": "06.00pm","endtime": "12.00pm","userpayment": 3000,"username": "sandunwikramasinha@gmail.com"},{"advertisementid":"PVK3RT3NFB","timestamp": 1421193600000,"adtimerange": "1hr","strttime":"08.00am","endtime": "10.00am","userpayment": 1000,"username": "gayan85@gmail.com"},{"advertisementid":"XI9VASNI0M","timestamp": 1421193600000,"adtimerange": "1hr","strttime": "10.00pm","endtime": "12.00pm","userpayment": 300,"username": "sandunwikramasinha@gmail.com"}]`
 
* **Error Response:**

  * **No Error Response returning** <br />

___________________________________________________________________________________________________________________________

**Get Description By descriptionId**
----
  Returns json data about a single Description.

* **URL**

  /web/v1/description/getById?{descriptionid}

* **Method:**

  `POST`
  
*  **URL Params**

   **Required:**
 
   `descriptionid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{"descriptionid": "3GQFMAMOMJ","imgurl": "https://www.google.lk/url?hgv=ygayc","detail": "Travel with Sri Lankan Airlines","adid": "XI9VASNI0M"}`
 
* **Error Response:**

  * **No Error Response returning**<br />

__________________________________________________________________________________________________________________________

**Get Description By AdId**
----
  Returns json data about list of Descriptions.

* **URL**

  /web/v1/description/getByAdId?{adid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `adid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `[{"descriptionid": "3GQFMAMOMJ","imgurl": "https://www.google.lk/url?hgv=ygayc","detail": "Travel with Sri Lankan Airlines","adid": "XI9VASNI0M"},{"descriptionid": "ZV4S2AX391","imgurl": "https://www.google.lk/url?iou12l","detail": "Travel with Sri Lankan Airlines","adid": "XI9VASNI0M"}]`
 
* **Error Response:**

  * **No Error Response returning** <br />
  
__________________________________________________________________________________________________________________________

**Get Platform By platformId**
----
  Returns json data about a single Platform.

* **URL**

  /web/v1/platform/getById?{platformid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `platformid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{"platformid": "9XFBTY90JX","platformusercount": "1000","platformbroadcasttime": "08.00am-10.00am","platformpersecondprice": 0.21}`
 
* **Error Response:**

  * **No Error Response returning** <br />
    
__________________________________________________________________________________________________________________________

**Get AdHasPlatform By adHasPlatformId**
----
  Returns json data about a single AdHasPlatform.

* **URL**

  /web/v1/adHasPlatform/getByAdHasPlatformId ?{adhasplatformid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `adhasplatformid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{"adhasplatformid": "SHRY5YG5N8","adid": "G613Z5DFQL","platformid": "9XFBTY90JX","adhasplatformdate":1453099355000}`
 
* **Error Response:**

  * **No Error Response returning** <br />
    
__________________________________________________________________________________________________________________________

** Get AdvertisementHasPlatfromModel details By AdId**
----
  Returns json data about list of AdvertisementHasPlatfromModels.

* **URL**

  /web/v1/adHasPlatform/getByAdId?{adid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `adid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `[{"adhasplatformid": "SHRY5YG5N8","advertisementid": "G613Z5DFQL","adtimerange": "2hr","strttime":"06.00pm","endtime": "12.00pm","userpayment": 3000,"username": "sandunwikramasinha@gmail.com","adhasplatformdate": 1453099355000,"platformusercount": "1000","platformbroadcasttime":"08.00am-10.00am","platformpersecondprice": 0.21}]`
 
* **Error Response:**

  * **No Error Response returning** <br />
    
__________________________________________________________________________________________________________________________

**Get AdvertisementHasPlatfromModel By adHasPlatformDate**
----
  Returns json data about list of AdvertisementHasPlatfromModels.

* **URL**

  /web/v1/adHasPlatform/getByAdHasPlatformDate?{adhasplatformdate}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `adhasplatformdate=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `[{"adhasplatformid": "SHRY5YG5N8","advertisementid": "G613Z5DFQL","adtimerange": "2hr","strttime":"06.00pm","endtime": "12.00pm","userpayment": 3000,"username": "sandunwikramasinha@gmail.com","adhasplatformdate": 1453099355000,"platformusercount": "1000","platformbroadcasttime":"08.00am-10.00am","platformpersecondprice": 0.21}]`
 
* **Error Response:**

  * **No Error Response returning** <br />
    
__________________________________________________________________________________________________________________________

**Get Site By siteId**
----
  Returns json data about a single Site.

* **URL**

  /web/v1/site/getById?{siteid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `siteid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{"siteid": "FHOISRJYEY","siteaddress": "http://www.youtube.com/","sitedetails": "Video sharing"}`
 
* **Error Response:**

  * **No Error Response returning** <br />
    
__________________________________________________________________________________________________________________________

**Get Site By siteAddress**
----
  Returns json data about a single Site.

* **URL**

  /web/v1/site/getSiteBySiteAddress?{siteaddress}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `siteaddress=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{"siteid": "FHOISRJYEY","siteaddress": "http://www.youtube.com/","sitedetails": "Video sharing"}`
 
* **Error Response:**

  * **No Error Response returning** <br />
    
__________________________________________________________________________________________________________________________

**Get SiteAdDetail by siteAdDetailId**
----
  Returns json data about a single SiteAdDetail.

* **URL**

  /web/v1/siteAdDetail/getByAdvertisementId?{siteaddetailid}

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `siteaddetailid=[String]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{"siteaddetailid": "1P7N1YMIND","sitevisiblecount": "1000","sitebroadcasttime": "10.00am-12.00am","sitepersecondprice": 0.16,"siteid": "AM0XC5F558"}`
 
* **Error Response:**

  * **No Error Response returning** <br />
    
__________________________________________________________________________________________________________________________
  
