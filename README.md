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

    *NO Error Response returning*
---------------------------------------------------------------------------------------------------------------------

**Show User**
----
  Returns json data about a single user.

* **URL**

  /users/:id

* **Method:**

  `GET`
  
*  **URL Params**

   **Required:**
 
   `id=[integer]`

* **Data Params**

  None

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{ id : 12, name : "Michael Bloom" }`
 
* **Error Response:**

  * **Code:** 404 NOT FOUND <br />
    **Content:** `{ error : "User doesn't exist" }`

  OR

  * **Code:** 401 UNAUTHORIZED <br />
    **Content:** `{ error : "You are unauthorized to make this request." }`

* **Sample Call:**

  ```javascript
    $.ajax({
      url: "/users/1",
      dataType: "json",
      type : "GET",
      success : function(r) {
        console.log(r);
      }
    });
  ```
