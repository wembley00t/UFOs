# UFOs

## Overview of Analysis

Dana is data journalist completing an article on UFO sightings.  This includes a dynamic web page of the UFO sightings.  This project is to allow users to filter for multiple criteria at the same time when reviewing data on the UFO sightings. In addition to the date, filters for the city, state, country, and shape will be added.


## Results 

The web page is displayed below showing the filters for date, city, state, country and shape.  The web page utilizes JavaScript, HTML and Bootstrap.

![original web page](https://user-images.githubusercontent.com/100876517/172072073-df9a0b8b-d0e1-4af1-8d25-0248f790e9f8.png)

### Filtering the Table

The table allows for users to filter the table for one criteria or multiple criteria at the same time. 

The first image shows the results if filtered only on date.

![date filter](https://user-images.githubusercontent.com/100876517/172072590-50406e6e-be55-479d-8523-cd39e4d7c108.png)

The second image shows the results if filtered on two criteria.  In this exampple, the user entered two criteria which are city
and shape.

![la mesa](https://user-images.githubusercontent.com/100876517/172072607-2271554a-1173-46fa-a8d2-cb9e91215a0c.png)



## Summary

### Drawback

One drawback of this table is the user must enter data in the exact format as the data is stored.  Below shows if the user enters 1//04/2010 
rather than 1/4/2010, no information will be displayed.  

![date filter wrong](https://user-images.githubusercontent.com/100876517/172072593-f3ced014-1d84-4bdc-a52d-f2167982c847.png)

### Recommendations

Two recommendations that would be beneficial for the next version of this table include:

* Adding a drop down within each filter so the user knows the options to choose from without having to review the detailed data.  This would allow
  the user to have a selection of shapes rather than needing to know the shape to enter.  The user may not be familiar with all shapes available.
* Updating so that exact matches do not need to be entered.  Lowercase and uppercase letters could be used for the text data.
* Utilizing a date range to give the user added flexibility when filtering data.
