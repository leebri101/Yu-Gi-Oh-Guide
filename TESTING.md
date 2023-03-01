# Testing Page of Contents
## **During Development Testing**
In the development phase, I was manually testing the site in two ways:-
    
1. Publishing the page via GitHub and sharing it with friends and family to test within a set controlled environment, and receive feedback on major and small changes that needed to be rectified.

1. Self testing to ensure that "I" as the creator know what to expect of the site.

### **Manual Testing**
* During the testing phase , I used three different browsers to ensure consistency & cross-platform connectivity. The browsers used in the tests are:

  1. Chrome
  2. Firefox  
  3. Edge

* I also used devtools to experiment the different screen sizes and devices from 320 px up to 4000px in width. 
* I have also asked a small group of people to test the site using Apple & Android products using safari. The users reported back with no issues or bugs only styling suggestions which will be implimented in the near future.

## **Validator Testing**

### **Validators**

#### **HTML** - https://validator.w3.org/nu/

* All pages have been fully tested no issues were found via URL or file upload.

#### **CSS** - https://jigsaw.w3.org/css-validator/

* CSS page has been tested, no issues found via URL or file upload.\
![CSS validator badge](https://jigsaw.w3.org/css-validator/images/vcss)

### **Lighthouse Scoring**
### **Testing Conditions:##
* I ran the tests for mobile and desktop. 
* I have asked a small group of people to run lighthouse tests from their own devices. 

#### ***Desktop Version:***
I have only included one screenshot for desktop as all pages were the same score, only changing by one or two points in performance if I ran it multiple times. 

![Desktop Lighthouse Score](/workspace/Yu-Gi-Oh-guide-/doc/screenshots/desktop-lighthouse-score.png) 

**Required to get attain the score:**


<!--
Image formats like WebP and AVIF often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. 
1. The initial SEO score was 90 due to having no Meta description tag in the page head. Once I added this, the score became 100.

1. The best practice score was first 93 and impacted by three factors:
    * Aspect ratio of the images on the teachings page. I fixed this by resizing the images proportionately with the calculator found on https://andrew.hedges.name/experiments/aspect_ratio/.

    * There were some anchor tags on the community page and the form feedback page where the contained text was "here". I changed these anchor texts to a more descriptive text indicating where the links would lead the user.

    * The graphic used as an anchor to download the book Modern Buddhism on index.html was the correct size with no need to specify width and height. However, the best practice scored suggested it should have a height and width specified. I used an extension called pesticide to get the dimension of the image and added these to the CSS file under an ID explicitly created for this element (#modbudd-ebook). Once I added the dimensions best practice score became 100.

1. The performance was 93 on the form feedback page but fluctuating around 93 each time I ran the test. I used https://tinypng.com/ to compress the hero image on this page, which took the score to a minimum of 95 or higher each time I ran the lighthouse test. -->