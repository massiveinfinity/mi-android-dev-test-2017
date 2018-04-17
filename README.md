# Massive Infinity Android Developer Technical Challenge

### Business requirement
As an app user, I want to see:
- a list of my deliveries
- location of each delivery location on a map
- full description of each delivery when I click the delivery item

### API Specification

**Get list of deliveries**
  * API
    `https://staging.massiveinfinity.com/api`
  * Method
    `GET`
  * Endpoint
    `/deliveries`
  * Response example:
    `HTTP code 200`
    ```json
    [
        {
            "description": "Deliver documents to Tracy",
            "imageUrl": "http://placekitten.com.s3.amazonaws.com/homepage-samples/200/287.jpg",
            "location": {
                "lat": 1.3520156,
                "lng": 103.9638572,
                "address": "Changi"
            }
        }, {
            "description": "Deliver parcel to Vea",
            "imageUrl": "http://placekitten.com.s3.amazonaws.com/homepage-samples/200/286.jpg",
            "location": {
                "lat": 1.301805,
                "lng": 103.8356084,
                "address": "Orchard Road"
            }
        },
        ...
    ]
    ```

### User Requirements
  - Retrieve list of deliveries from the API
  - Display list of deliveries.
  - Show details when user select an item in the list.
  - Add marker on the map based on the provided lat/lng. 

### What we expect from you?
Production ready solution that you are proud of.

## Technical Requirement
1. Source code must be stored in git repository (you can send it as github or bitbucket link, dropbox/google drive public folder, etc. **NOTE: email servers will reject .zip files with source code**)
2. App should be able to work offline after initial use.
3. App should be able to handle server errors. By design, the API will randomly produce these errors.
4. Candidates are free to use any libraries.
5. Project must compile in Android Studio and Gradle
6. Support multi pane layout in tablet landscape orientation

## Wireframe
*For reference only, you can be creative with design and UI/UX features.*
![Wireframe](https://github.com/massiveinfinity/mi-android-dev-test-2017/blob/master/wireframe.png)
