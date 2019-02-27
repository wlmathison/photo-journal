## @channel Here is the newest exercise. If you have any questions about the requirements for this or any of the other exercises, please slack me or Kristin. Remember, you should only start on this if you are done with everything else on the list:

Build an application to showcase your collection of photos:
The application will have three html pages: Home, Photos and About.
If you do not want to use your own photos, you can use images from online.
You are more than welcome to add more pages and functionality as long as the following requirement are met.
Please keep the web page professional and employer friendly!

***This is will a new repository on Github. Make sure to keep your commits small.***

1. You will be using Bootstrap for the layout of your application. Go through the documentation for using Bootstrap here: https://getbootstrap.com/docs/4.3/getting-started/introduction/. You can either use the starter template or copy the CSS link tag and the JS script tags into your html.

2. All three pages will contain:
    i. A nav bar at the top with at least three links to your different pages (Home, Photos and About).
    ii. A footer with your your name, email and the name of your website.

3. The home page will also contain:
    ii. A creative title for your web page,
    iii. A Bootstrap carousel that displays your five favorite photos
    iv. A brief description of what you want to show with the photos you have chosen to display.
    
4. The photos page will contain:
    i. A collection of the photos you want to display on your website. Use Bootstrap’s grid system to layout the photos on your page.
    ii. Use Bootstrap’s card component for your individual photos so that for each photo, there is the photo itself and below it the description.
    
5. The About page will contain:
    i. A short bio about yourself
    ii. A photo of you
    iii. A form for users to contact you (Once again, the form does not have to do anything)
    
***STRETCH GOALS***    
These are not required but if you get through the above requirements, please work on the following.

1. When a user clicks on the card for a photo, use a Bootstrap modal to show a full size version of that photo.

2. Add a Javascript file and link it with your three HTML pages.

3. On the about page, when the user submits the contact form, console log the values they entered. Use the following chapters for reference: https://github.com/nashville-software-school/client-side-mastery/blob/master/book-2-the-neophyte/chapters/JS_EVENTS.md and https://github.com/nashville-software-school/client-side-mastery/blob/master/book-2-the-neophyte/chapters/JS_USER_INPUT_BASICS.md

4. For your photos page, instead of writing your HTML in your html files, you are going to dynamically generate it and put it on the DOM using JS. In your JS file, create an array to contain all file paths for your photos. Loop over your array and build your html for each photo card. Append the html you have generated to your html page. Use the following chapters for reference: https://github.com/nashville-software-school/client-side-mastery/blob/master/book-2-the-neophyte/chapters/IDENTIFYING_DOM_COMPONENTS.md and https://github.com/nashville-software-school/client-side-mastery/blob/master/book-2-the-neophyte/chapters/JS_CREATING_COMPONENTS.md