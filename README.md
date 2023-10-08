# Restful  Booker API Testing with Postman & Newman

[Restful-booker](http://restful-booker.herokuapp.com/API ) is a Create Read Update Delete Web API that comes with authentication features and loaded with a bunch of bugs for you to explore.
testing and tools website.

[API Documentation](http://restful-booker.herokuapp.com/apidoc/index.html)

---
## Tasks
- Login
	- Create Token
- Create Booking
	- Create Booking
    - Create Booking by First Name Null
- Get Booking
  - Get All Booking ID
  - Get Booking by Specific ID
  - Get Booking by Non Existing ID
  - Get Booking by First Name and Last Name
- Update Booking
	- Update Booking by Valid Data
    - Update Booking by Invalid  First Name
    - Partial Update Booking by Valid Data
- Ping
    - Health Check


## Dependencies

- Install [Postman](https://www.getpostman.com/)
- Install [Restful Booker API](https://github.com/mwinteringham/restful-booker) locally (optional)
- Install [Newman](https://github.com/postmanlabs/newman)
- Install [newman-reporter-htmlextra](https://github.com/DannyDainton/newman-reporter-htmlextra)
---

### Run a test for a single request

1. On the Collections tab of the Postman sidebar, expand the imported Smoke collection and expand any of the included folders, such as "Login".
2. Select a request, such as "Create Token" under the Login folder.
3. Within the CreateToken screen, you'll see smaller tabs for the request info (Params, Authorization, Headers, etc.)
    - Click on the Body tab to see what the request will send.
    - Click on the Tests tab to see what will be validated after the request is sent.
4. Click the big, blue "Send" button in the upper-right of the Create Token screen.
5. All of the response info will then be updated in the lower portion of the screen.
6. Tap on the "Test Results" tab to see if the test(s) passed or failed.

### Run all tests for a folder or collection

1. From the Postman header bar, click "Runner".
2. From the collection browser, select either a collection, such as "Smoke", or drill down to a specific folder, such as "Booking".
3. Select your desired environment from the dropdown.
4. Click the big, blue "Run" button.
5. Review the list of Run Results to see which tests passed or failed.