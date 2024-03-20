# Assignment 2: Application DOG API

## End point: List all breeds
### Test Scenarios:
1. Verify that when the API is executed in the application, the response is received.
2. Verify that the status code is 200 OK.
3. Verify that the response is in JSON format.
4. Verify that the response body contains the list of all dog breeds and their sub-breeds.
5. Verify that the response body contains status as "Success" at the end.
6. Measure the API response time and ensure it is within acceptable limits.
7. Verify the size of the response data to ensure it is within reasonable limits.
8. Verify that the status code is 404 for invalid or unexpected inputs.
9. Verify that the status is "error" for invalid or unexpected inputs in the response body.
10. Verify that the response body contains the message "No route found for \"GET http://dog.ceo/api/breeds/list/ll\" with code: 0” for invalid input.

## End point: By Breed
### Test Scenarios:
1. Verify that the status code is 200 OK.
2. Verify that the response is in JSON format.
3. Verify that the response body contains the list of all the image URLs for a particular breed.
4. Verify that the response body contains status as "success" for a valid breed.
5. Measure the API response time and ensure it is within acceptable limits.
6. Verify the size of the response data to ensure it is within reasonable limits.
7. Verify that the response body contains status as "error" for the invalid breed’s name.
8. Verify that the status code is 404 for an invalid breed name.
9. Verify that the response body contains the message "Breed not found (master breed does not exist)" for an invalid breed name input.
