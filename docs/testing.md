# Testing

## Test Plan


| Test-Case ID | Test type | Description | Scenario |
| ----------- | -----------| ---------   | ------   |
| TF1 | UAT| System shall get geo users location  | when the user is on the page it a pop up should come up asking to grant access to location  |
| TF2 | UAT| The system shall get the nearest BMX facilities from the database   | When the user grants permission for access all BMX facilities in Bristol should pop up, especially the ones closest to the user.   |
| TNF4 | UAT| The system should work on chrome and other browsers   | if the user opens up the website on any browser no unique error should occur  |
| TF7 | UAT| The system won't share the user's data   | when the user is accessing the site with a log in personal information such as email or social media links will be kept private and under protection    |
| TNF5 | UAT| Marker larger should not be larger than 7% as it can obscure view  | when user has different marker for all the facilities on the map in Bristol it should not be larger than 7% as it can obstruct the view of the location and be unvisually appealing     |

## Test Runs


| Use-Case ID | Requirement ID | Test Case | Status |
| ----------- | -------------- | --------- | ------ |
| UC1 | TF1 | System shall get geo users location | pass |
| UC1 | TF2 | The system shall get the nearest BMX facilities from the database  | pass |
| UC1 | N/A | opt to view table of BMX facilities | pass |
| UC1 | TNF4 | The system works on chrome browser | pass |


