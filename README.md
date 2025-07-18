# Web Development Project 4 - *Feline Finder*

Submitted by: **Anubhav Dhungana**

This web app: **Fetches and displays random cat images from The Cat API along with detailed breed information including weight, origin, and life span. Users can click on any cat attribute to add it to a ban list, which prevents cats with those characteristics from appearing in future searches. The app features a clean, interactive interface where users can discover new feline friends while customizing their experience by filtering out unwanted traits. This helps cat lovers to discover cats :3**

Time spent: **7** hours spent in total

## Required Features

The following **required** functionality is completed: 

- [x] **Application features a button that creates a new API fetch request on click and displays at least three attributes and an image obtained from the returned JSON data**
  - The type of attribute displayed for each image should be consistent across API calls (i.e. if you are using a cat API, and display the color, breed, and age in response to an initial API call, subsequent button clicks should also result in the color, breed, and age being displayed)
- [x] **Only one item/data from API call response is viewable at a time and at least one image is displayed per API call**
  - A single result of an API call is displayed at a time 
  - Displayed attributes should match the displayed image (i.e., if showing a picture of a Siamese cat and the attribute breed, the displayed breed should be 'Siamese' not 'Ragdoll' or another breed that doesn't match)
  - There is at least one image per API call
- [x] **API call response results should appear random to the user**
  - Clicking on the API call button should generate a seemingly random new result each time
  - Note: Repeat results are permitted but the API used should have a reasonably large amount of data and repeats should not be frequent
- [x] **Clicking on a displayed value for one attribute adds it to a displayed ban **list**
  - At least one attribute for each API result should be clickable
  - Clicking on a clickable attribute not on the ban list, should imnmediately add it to the ban list 
  - Clicking on an attribute in the ban list should immediately remove it from the ban list 
- [x] **Attributes on the ban list prevent further images/API results with that attribute from being displayed**
  - Clicking on the API call button should not result in any image/attributes with attribute values in the ban list being displayed (ex. Using a cat API, if the ban list includes the value 'Siberian' for the breed attribute, clicking on the Discover button should never result in a Siberian cat being displayed)
  - Note: More attribute values on the ban list may result in a higher frequency of repeat results
  -  [x] _To ensure an accurate grade, your recording **must** show that when clicked, an attribute in the ban list is immediately removed from the list of banned attributes_


The following **optional** features are implemented:

- [x] Multiple types of attributes are clickable and can be added to the ban list

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='src/assets/Feline-Finders-Demo.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with ...  
MacOS Video Capture Tool; 
Giphy; 
EZGIF; 

## Notes

* Working with APIs for the first time was incredibly complex and I was left stracting my head a lot of times. 
* CSS, as always, was a pain to get right. 
* The API url that ensures that very cat has a breed information was not working as I understood it should be working as. 

## License

    Copyright [2025] [Anubhav Dhungana]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
