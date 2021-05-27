# Prevent Aging by Curating Optimal Skincare Regime

## Digital Humanities 110 - Heuristics Evaluation by Peterson Le
### Motivation
Skincare is something I have recently indulged in during college, and have been doing more research on in quarantine to learn how to protect my skin in changing environments. I thought this would be an interesting topic for our UX design topic because skincare is relevant for all ages as we must constantly reevaluate the products we use to address our problem areas -- acne-prone skin, wrinkles and aging, etc. Creating an app that recommends skincare products, analyzes current skin needs and progress, and build an online community to learn about skincare (e.g., harmful ingredients) would help us take care of our body through the curation of an optimal skincare routine. I will be addressing two skincare applications (Cleo and TroveSkin) with similar goals, yet have much room for improvements. <br/>

#### Application 1: Cleo
Cloe is a personal skincare diary where you can log the products that you are using and record your skin’s progress. You can also leave reviews on the products that you have tried, while also containing a pseudo-social media where you can post your review and rating of products, leave likes, and write comments. <br/>
<img src="https://user-images.githubusercontent.com/63027004/113802821-38042a00-9710-11eb-8718-ff05bb07dd65.jpeg" width="250">
#### Application 2: TroveSkin
TroveSkin is a skincare application that allows users to take quizzes to determine their skin type and recommend products based on the results. This app’s feature includes keeping track of your daily habits, obtaining skin analyses, and access to articles related to skin, beauty, and health. <br/>
<img src="https://user-images.githubusercontent.com/63027004/113807122-684fc680-9718-11eb-8030-b4e060ee5614.jpeg" width="250">

### Heuristics Evaluation Severity Ratings
**1**: Site performed average for this heuristic and does not need to be reevaluated/altered for better usability.<br/>
**2**: Site performed slightly below average for this heuristic and has the potential to be altered for better usability.<br/>
**3**: Site performed below average for this heuristic and could use major immediate reevaluation for better usability.<br/>

## Cleo Heuristics Evaluation Ratings
### Visibility of System Status
***Severity Rating: 3*** When using the search feature on the main page and the camera feature (separate from the one on the diary entry page), it takes you to a blank screen without any signifiers that it is loading. Here, I searched “Lymecycline” in the search bar, an item I saw already posted, and was met with a purely blank screen. Similarly, I went to take a photo to update my logs and was unable to access the camera, despite allowing the app access to my camera.<br/>

*Recommendation:* Fix the backend of the application to make these functions usable. <br/>

### Match Between Systems and Real World
***Severity Rating: 2*** The icons used to separate the pages are definitely intuitive (i.e., using a calendar for the diary logs, camera icon to access camera, and graph to access analytics); however, after adding entries and posting reviews on the app, the analytics do not update. Therefore, I am left wondering whether there is more to the app that I am unaware of or if the app is not optimized correctly to perform this task. <br/>

**Update:** After a couple of hours, the analytics page updated and now illustrates that I have one entry and one post. This is a concern with the visibility of system status as Cleo does not attempt to reassure nor communicate to users that the analytics would take a while to update. <br/>

<img src="https://user-images.githubusercontent.com/63027004/113803701-eceb1680-9711-11eb-82ed-006442a22b7d.jpeg" width="350">

*Recommendation:* Fix the backend of the application to ensure that the analytics are updated as quickly as possible. If that is not possible, inform users about the processing time for an update. <br/>

***Severity Rating: 3*** Users are able to set notification frequencies in the settings; however, there are two blank buttons with no description about what the buttons do. Thus, users must guess whether the top button is for high frequency or low frequency. In addition, regardless of buttons, you can only select one time to receive notifications. If a user would like a reminder to be reminded to wash their face in the morning and night, then it is impossible to do so using Cleo. <br/>

<img src="https://user-images.githubusercontent.com/63027004/113803770-0c823f00-9712-11eb-85e0-858cbeb130c7.jpeg" width="350">

*Recommendation:* Explicitly state which each box correlates to in terms of notification frequency and allow users to set multiple reminders (e.g., one reminder for morning routine, one reminder for night routine). <br/>

### User Control and Freedom
***Severity Rating: 1*** After entering an entry, users are capable of editing and deleting the entry. In addition, they can delete the photos they have taken for that day. This gives users the freedom to correct any mistakes or discard unwanted entries on their daily logs. Similarly, they can delete posts, but I do not believe they have editing access to it once it is posted. <br/>

### Consistency and Standard
***Severity Rating: 2*** As aforementioned, the app’s homepage consists of a pseudo-social media that mimics apps like Instagram. Therefore, those familiar with instagram would have an easy time using the app to post reviews and scroll. However, it is unclear if there is a proper algorithm to the app where it shows you products catered to your skin type and concern. Without a proper search feature, filter function, explore page, or the ability to visit reviewer’s profiles it is difficult to see any use to the reviews posted. <br/>

*Recommendation:* Allow users to filter through the home page by product type, fix the search feature, and establish profiles to build a stronger community with the app. Profiles would also allow users to find individuals with similar skin types and concern to share how they chose to address it. <br/>

### Error Prevention
***Severity Rating: 1*** When editing a diary entry, I assumed all edits were automatically saved and pressing the back button would update the entry. However, when pressing the back button, an error message occurs asking if the user would like to discard all changes made to the entry. <br/>

<img src="https://user-images.githubusercontent.com/63027004/113804000-831f3c80-9712-11eb-8a69-36b481c27373.jpeg" width="350">

### Recogniton Rather than Recall 
***Severity Rating: 3*** When you like or interact with a review about a skincare product, there is no space to access all of your liked contents. Therefore, users must recall what products they were interested in through scrolling through the home page. This is very time consuming and could potentially disrupt the flow of the user. <br/>

*Recommendation:* Create a page that list all items that users have liked while exploring the homepage; thus, they will not need to use a separate application to remember which products they would like to try. <br/>

### Flexibility and Efficiency of Use
***Severity Rating: 3*** There are multiple ways to add photos on the app to keep track of your skincare process —  one through the diary entry and one through the general camera feature. Because the diary entries are mainly for end of the day inputs (due to users only being allowed one entry per day), having two options is great for when you are having breakouts or skin complications throughout the day (or have shown great improvements) and would like to take update picture both in the day and at night for the entries. However, the general camera feature does not work as aforementioned or the waiting time is too long without any signifiers that it is loading. <br/>

*Recommendation:* I would have rated this heuristics a 1 in severity, but because the features aforementioned was nonfunctional, it it utterly uselss. Designing functions that are achievable for the engineers should be highest priority. <br/>

### Aesthetic and Minimalist Design
***Severity Rating: 1*** Cleo has a very minimalistic design with key features needed to keep track of your skin and skincare regime. Because of this, it is very easy to use if we disregard the malfunctions of some of the features. There could have been different design choices that may make the app look better; however, those are more personal decisions that do not interfere with the user interface. <br/>

### Help Users Recognize, Diagnose, and Recover From Errors
***Severity Rating: 1*** There are no error messages on the application; however, I was never in the position to need one. Because they allow users to edit much of the content that they post, it makes recovering from “errors” less taxing. <br/>

### Help and Documentation
***Severity Rating: 2*** There is no help (e.g., FAQ page) or any documentation that should assist users. I suspect Cleo believes their site to be highly intuitive; however, a simple onboarding process for new users would help users adjust to the new site. <br/>

*Recommendation:* Create an FAQ page or introduce a *very* simple onboarding process to ease users in. <br/>

## TroveSkin Heuristics Evaluation Ratings

### Visibility of System Status
***Severity Rating: 1*** There are multiple quizzes that are taken on TrovenSkin — one to establish your current skin routine, one to state your skin goals, and one to determine your skin type. Some of these quizzes state how many minutes you should expect to take answering the questions. Furthermore, it shows a progress bar and the number of questions there are during the quiz. <br/>

<img src="https://user-images.githubusercontent.com/63027004/113807205-89b0b280-9718-11eb-90d2-c4e32199aba6.jpeg" width="250">

### Match Between Systems and Real World
***Severity Rating: 3*** The words TroveSkin uses to separate content is confusing to me because they all mean the same thing, yet they perform different tasks. The application has a “Skin Report,” “Skin Log,” “Skin Diary,” and “Skin Analysis,” and at first glance it is difficult to understand what these do until users click around and make mistakes when performing a different task than intended. Thus, users are expected to get comfortable with the site through trial and error rather than to understand the intentions of the words used. <br/>

*Recommendation:* Use words with different meaning to differentiate all of the different pages or introduce an onboarding process that explains each section and subtly describe why the name is fitting for the features it holds. <br/>

### User Freedom and Control
***Severity Rating: 2*** Users are not able to retake quizzes that defined their skin type and skin care goals/concerns. Therefore, once it is completed, users cannot change this information in order for TroveSkin to recommend products. Our skin is constantly changing especially with age, and having the freedom to update our skin type (e.g., combination skin to dry) and concerns (e.g., acne to aging) would ensure that we have the most current information for optimal products. <br/>

<img src="https://user-images.githubusercontent.com/63027004/113807937-dd6fcb80-9719-11eb-9a93-b0c62cd0371c.jpeg" width="350">

*Recommendation:* Allow users to retake quizzes to update their skin type and skin concerns.

### Consistency and Standard
***Severity Rating: 2*** To update your skin diary in TroveSkin, you must go to “Home” and click on “Skin Log” at the top. However, there is a “Skin Diary” in the menu where users can view all of their previous skin logs. I am accustomed to being able to do everything related to a section on that specific page (e.g., being able to update skin logs in the skin diary section), so I had difficulty finding out how to create a new log. I am also not used to having photos being required to input separate information (e.g., hours of sleep, cups of water, products I’ve used); therefore, I was confused when everything took me a camera. <br/>

*Recommendation:* Provide users with access to all of the information and allow them to click a button that would open the camera whenever they are ready. Thus, they users can choose the order in which they input information. <br/>

### Error Prevention
**Severity Rating: 1*** The button to delete logs are hidden from users until you swipe a certain direction; thus, it takes away the possibility of accidentally deleting skin logs. Furthermore, a pop up asking if the users are sure they would like to delete the log is ensued before completing the deletion. These features prevent users from mistakenly deleting their logs. <br/>

<img src="https://user-images.githubusercontent.com/63027004/113807442-fe83ec80-9718-11eb-9dbe-c2b84c465082.jpeg" width="350">

### Recogniton Rather than Recall 
**Severity Rating: 1*** TroveSkin has daily challenges to remind users what they can do to keep track of their skin. As a result, they do not have to remember all of the components of the application and can progress through it linearly and quickly. <br/>

<img src="https://user-images.githubusercontent.com/63027004/113807823-a994a600-9719-11eb-8b7d-c53b9de34e7f.jpeg" width="350">

### Flexibility and Efficiency of Use
***Severity Rating: 1*** There are many call-to-actions on the homepage which can also be accessed through the profile such as challenges, quizzes, and product recommendations. The way it is organized is also different (i.e., grid vs list views) which provide users with multiple ways to access and source through information. <br/>

### Aesthetic and Minimalist Design
***Severity Rating: 1*** The design of TroveSkin can be described as minimalist, and compared to the first application Cleo, it is much more aesthetically pleasing and organized. <br/>

### Help Users Recognize, Diagnose, and Recover From Errors
***Severity Rating: 3*** Although this is not considered an error, it is difficult to know when one of your log entries is incomplete. In the Skin Diary, you can only delete logs as opposed to updating them. A user must go to Skin Report instead to access a single log to complete it. This was hard to find, especially because I did not know the diary was incomplete to begin with. <br/>

*Recommendation:* Inform users after they enter a skin log that their log is incomplete and where to go to complete it. A reminder to complete entries could also be beneficial as long as it doesn't disrupt the flow of the user and can be turned off when appropriate. <br/>

### Help and Documentation
***Severity Rating: 2*** I was unable to find any help and documentation. The application should have an onboarding process to get used to some of the features and especially needs one for the community aspect of TroveSkin. The community feature was very confusing to me, and because of so, I felt uncomfortable using it further. <br/>

*Recommendation:* Introduce an onboarding process, as aforementioned. <br/>

## Overall Impressions
### Cleo
I was disappointed in the application because many of the features did not work and made it difficult to search for products that catered to my skin type. In addition to the malfunctions of current features, Cleo was missing many pages and functions that would have created a better environment for the user. The social media aspect is a great idea, yet I wished it was optimized better to cater to the users; rather, it felt more like an accessory than a need due to the lack of filter and algorithm. <br/>
### TroveSkin
I was very impressed with the functionality of TroveSkin, such as a skin analysis where the system highlights problem area in your skin as shown in the photos you send. It has many properties that I would like to include in my design when creating a skincare app, yet I would like to give users more freedom in their skincare journey. There are a lot of stylistic aspect that I would change, but I believe the application done a lot of things well.

