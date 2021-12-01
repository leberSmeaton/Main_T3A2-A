# **Picnic Victoria**

###### **ASSESSMENT:** Full Stack Application - Part A

###### **DEV TEAM:** Karla Tolentino, Ruilai Zhang, Matthew Liu, Bella Leber-Smeaton

<br />

## **Picnic Victoria Description**

> _Nothing is better than a picnic in Vic!_

#### **Client:**

Parks Victoria - Victorian State Government

#### **Purpose:**

In a post Covid world we now know more than ever that we need to connect with our friends and family, outdoors in the _real world_. We need to utilise our green open spaces to enrich our lives.<br />
To meet calls and pressure that local councils and the State Government aren't providing enough green space, Parks Victoria are creating a new inner city park database. For small and large parks alike!<br />
The **Picnic Victoria** app provides detailed park amenity information to help facilitate a family picnic to a skate park hangout.<br /><br />
**_A park is nothing without a picnic and nothing is better than a picnic in Vic!_** <br /><br />
Want to reach peak picnic? 🍷 + 🧀 = 🧺 <br/>
The Picnic Victoria app have teamed up with Victorian Wine and Cheese producers to pair your local park with local picnic produce. <br />
_It doesn't get much Gouda than that._
<br /><br />

#### **Functionality / Features:**

- Landing Page is the Map View: allows for instant viewing of proximity to parks.
  - Navigation Header allows to switch to List View - Has markers of park locations
  - Has model popups on click of park locations
  - Has drop down to select which type of park you want to select.
    ![The Novak Family picture](./Resources/desktop-wireframe-a-feature.png)
- List View: lists the entire of park markers in an informative readable listicle.
  - cards on click expand to show comments and any additional imagery if present.
  - Users can reply if logged in.
  - Authorisation will be requested.
  - Special Picnic Victoria feature is that users can pair a wine and or cheese with their park visit by clicking the randomise buttons. This shows the random options.
  - if logged in the user can also rate or make comments to the parks selected.
    ![The Novak Family picture](./Resources/desktop-wireframe-f-feature.png)
    ![The Novak Family picture](./Resources/desktop-wireframe-g-feature-b.png)
- About View: gives details about what the app does, who it is by and why.
  - Other feature includes details about our Picnic Victoria partnership with wine and cheese producers.
    ![The Novak Family picture](./Resources/desktop-wireframe-h-feature.png)
- Sign In / Sign Up View: Allows Users and Admin to sign up and sign in.
  - User Sign up and Sign in allows for user authorisation, accessing certain features of the app such as star rating, park commenting and image upload.
  - Authentication for when users sign in includes, email as identifier, password, optional profile pic.
  - Authorisation occurs for features that have CRUD functionality for all users and admin. USers have access to only their commentary. Admin has access to ALL USERS CRUD functionality, including the ability to _hide_ or _delete_ posts that don't meet standard.  
    ![The Novak Family picture](./Resources/desktop-wireframe-i-feature.png)
    ![The Novak Family picture](./Resources/desktop-wireframe-j-feature.png)

#### **Target Audience:**

![The Novak Family picture](./Resources/TheNovaks.jpg)
**Who:** The Novaks. 'The Nuclear Family, with dog'. Two parents. Two Children. One puppy. <br />
**Age:** Parents are late twenties to late thirties, 28-38. One child is of primary school age 7, and one two year old. <br />
**Occupation:** One stay at home parent, the other working 9-5. Children are young learners.<br />
**Nationality:** Slovenian Australians.<br />
**Income:** Lower middle Class, one income of 80k/annum. <br />
**Religion:** Non practicing/ 'lapsed Catholic'.<br />
**Location:** Local resident. Elsternwick, 3185. South-Eastern Suburbs. <br />
**Living circumstances:** Smaller townhouse with no garden.<br />
**What is the problem this Target Audience needs solving?**<br />
The Novaks have a young family and no backyard, so they spend a lot of their family time outside of the home to entertain their young children. They go for walks with their dog so they also need parks that allow for dogs and an off leash area. Picnics are a regular occurrence for the Novaks. <br />
As a family they have a lot of needs that have to be met for an enjoyable picnic. Their number 1 problem is that most parks near them don't have toilet / change table facilities and a playground. They wish they had the ability to look this up so they don't have to arrive disappointed.
Their ultimate park is one that has a toilet, cover from the sun, a playground and dog park. An 'all-in-one' park scenario. Their lower grade park might be one they take their dog to for a short morning walk. <br />

---

![Glenn B](./Resources/glenn.jpeg)
**Who:** Glenn B. Single male<br />
**Age:** 25 years old<br />
**Occupation:** Music teacher and support worker for special needs children. Living with another housemate<br />
**Nationality:** Australian<br />
**Income:** Lower middle class. Income approx. $50-60k per annum<br />
**Religion:** Agnostic<br />
**Location:** Werribee, 3030. Western Suburbs<br />
**Living circumstances:** Currently renting in a small unit and small backyard<br />
**What is the problem this Target Audience needs solving?**<br />
Glenn is a person in his mid 20s. With a small backyard at his rental, he will usually go out and explore the nearby park or reserve to get some fresh air. He is quite keen to visit and explore new places
<br />
The problem that Glenn have are two fold: <br />1. Finding the right park with right facilities. Many times, he has tried to find information on the a particular park, only to find that park does not have the correct facilities. Glenn has run into this problem many times, especially when it comes to working with special needs children, whereby the park does not have a playground or toilet facilities. 2. Finding a different variety of parks. As someone who loves exploring and as a special needs support worker, Glenn feel that some parks around his area are quite underwhelming, and would like to find a way to distinguish and filter out parks, based on what they have to offer.

---

![image](./Resources/HenryW.jpg)
<br />
**Who:** Henry Williams<br />
**Age:** 20 years old<br />
**Occupation:** Student<br />
**Nationality:** American<br />
**Income:** Part-time job<br />
**Religion:** Christian<br />
**Location:** New York, American<br />
**Living circumstances:** Currently live in a backpacker hotel<br />
**What is the problem this Target Audience needs solving?**<br />

1. Henry has very limited time in Melbourne, and he doesn't have much time to take the process of trial and error.<br />
2. Henry want to find parks that have good views and special architechture or hitorical statue etc. However, he don't have friends in melbourne to give him some valuable suggestions, his only option is google searching which is not convnient.<br />
   <br />

---

![image](Resources/ramona-skater.jpg)
<br />
**Who:** Ramona Rodriguez<br />
**Age:** 28<br />
**Occupation:** Graphic Designer<br />
**Nationality:** Australian/Mexican<br />
**Income:** $70,000 p.a.<br />
**Religion:** None<br />
**Location:** Fitzroy North<br />
**Living circumstances:** Sharehouse living with three other creatives<br />
**What is the problem this Target Audience needs solving?**<br />

1. Living in a sharehouse with three other people, Ramona would like to get out of the house and expand her social circle within the skateboarding or skating community.
2. Ramona is a busy person, so having an app that would give her quick and easy information on the types of skateparks available in her local vicinity would be ideal. As she is a budding skateboarder, Ramona would also like to share and find community reviews of the skateparks in her area. This is so she is able to organise meetups and learn with skaters of different backgrounds and experience.
   <br />

---

#### **Tech Stack:**

| Application and Data | Utilities  | DevOps  | Business Tools |
| -------------------- | ---------- | ------- | -------------- |
| HTML 5               | Postman    | GitHub  | Trello         |
| CSS                  | JWT/Devise | Git     | G Suite        |
| JavaScript ES6       | NPM        | VS Code | Discord        |
| Rails                | Ruby Gems  |         | Figma          |
| React                | - cancando gem |         | Google Fonts   |
| PostgreSQL           | RSPEC      |         | Zoom           |
| Amazon S3            | Jest       |         |                |
| Heroku               | Google API |         |                |
| Netlify              |            |         |                |
|                      |            |         |                |

<br />

## **Dataflow Diagram:**

<!-- Show at least 2 dataflow diagrams that follow a set dataflow convention -->

![app_architecture_diagram](./Resources/Dataflow_Diagram_1.png)

## **Application Architecture Diagram:**

![app_architecture_diagram](./Resources/aad.png)

## **Park Vic User Stories:**
The Novak Family
- As **stay at home** mum Katja Novak, **I need an easy wine and cheese option** whilst I watch my children at the park, as **being a mum is hard work and I deserve a treat**.

- As **working dad** Phil Novak, I want to make sure my **park is the right type** and has **all the features I need** for my family, so I can ensure **family time is stress free** and **maximum time is spent together**.


Ramona Rodriguez
- As Ramona, I want to be able to review parks with skate features and leave comments on it, so that I can share this information to other people in my community.

- As Ramona, I want to be able to search for my nearest skatepark on a map, so that I can save time between my busy schedule.

- As Ramona, I want to view different suggestions for wine and cheese, so that I can organise social picnics at the park with friends.


Glenn B:
- As a support worker for special needs children, I want to be able to find a park nearby, so that I can keep children entertained.

- As an active person, I want to be a able to find and review quality parks with appropriate sporting facilities with up-to-date images, so that I'm not left disappointed.

- As a social person, I want to be able to find filter for a park with appropriate eating facilities, so that I do not have to drive around to find a park with the appropriate facilities.


Henry Williams:
- As a backpacker, I want to be able to search for beautiful parks with features that I am interested in so that I can avoid visiting parks that have nothing to attract me.

-As a backpacker, I want to be able to find parks on the map with my current location so that I can save time on searching because local addresses make no sense to travelers.


<!-- Show 2 versions of user stories 'shows evidence of user story revision and refinement' -->

### [Katja Novak](<https://www.figma.com/file/InWmz7kkpj2u7o86HhEdsl/User-personas-(Community)?node-id=0%3A1>)

![Image one of Katja Novak user story](./Resources/UserStory_Katja_1.png)
![Image two of Katja Novak user story](./Resources/UserStory_Katja_2.png)

### [Glenn B](https://www.figma.com/file/2DryqFWrEVPYJMFjB7luzn/A-user-persona?node-id=0%3A1)

![Image one of ](./Resources/userStory-glenn1.png)
![Image two of ](./Resources/userStory-glenn2.1.png)

### [Ramona Rodriguez](https://www.figma.com/file/dN11zwW6TYaPncwCPeT7pu/Skater-Girl-User-Story?node-id=0%3A1)

![Image one of ](Resources/UserStory-Ramona1.jpg)
![Image two of ](Resources/UserStory-Ramona2.jpg)

### [Henry Williams](https://www.figma.com/file/Ix0i5H4wdlQMbqRtiHGorb/User-personas---Henry-Williams?node-id=0%3A1)

![Image one of ](./Resources/UserStory_Henry_1.png)
![Image two of ](./Resources/UserStory_Henry_2.png)

## **Device Wireframes:**

<!-- Show 2 versions of your FIGMA wireframes -->

### [Picnic Victoria Wireframe View](https://www.figma.com/file/1NgAVHDgzPuJq9B8WJswjZ/Wireframes?node-id=0%3A1)

Landing View
![Image one of Desktop](./Resources/desktop-wireframe-a.png)
Landing View Zoomed with type of park selected
![Image one of Desktop](./Resources/desktop-wireframe-b.png)
List View
![Image one of Desktop](./Resources/desktop-wireframe-c.png)
List View Expanded with randomise wine and cheese picnic pairing and comments
![Image one of Desktop](./Resources/desktop-wireframe-f.png)
List View Expanded with comment form and image upload
![Image one of Desktop](./Resources/desktop-wireframe-g.png)
About View
![Image one of Desktop](./Resources/desktop-wireframe-h.png)
Sign In View
![Image one of Desktop](./Resources/desktop-wireframe-i.png)
Sign Up View
![Image one of Desktop](./Resources/desktop-wireframe-j.png)

---

Landing view - Tablet
![Image one of Tablet](Resources/tablet-wireframes/Tablet-Landing.png)
Hamburger menu - Tablet
![Image one of Tablet](Resources/tablet-wireframes/Tablet-Hamburger-Menu.png)
List - Tablet
![Image one of Tablet](Resources/tablet-wireframes/Tablet-List.png)
Comment on a park
![Image one of Tablet](Resources/tablet-wireframes/Tablet-List-Comments-Part1.png)
![Image one of Tablet](Resources/tablet-wireframes/Tablet-List-Comments-Part2.png)
Sign In - Tablet
![Image one of Tablet](Resources/tablet-wireframes/Tablet-SignIn.png)
Sign Up - Tablet
![Image one of Tablet](Resources/tablet-wireframes/Tablet-SignUp.png)
About - Tablet
![Image one of Tablet](Resources/tablet-wireframes/Tablet-About.png)

---

Landing view - Mobile<br />
![Image one of Mobile](./Resources/mobile-landing.png)<br />
Hamburger menu - Mobile<br />
![Image one of Mobile](./Resources/mobile-hamburger_menu.png)<br />
List - Mobile<br />
![Image one of Mobile](./Resources/mobile-list.png)<br />
Comment on a park<br />
![Image one of Mobile](./Resources/mobile-post_comment1.png)
![Image one of Mobile](./Resources/mobile-post_comment2.png)<br />
Sign In - Mobile<br />
![Image one of Mobile](./Resources/mobile-signin.png)<br />
Sign Up - Mobile<br />
![Image one of Mobile](./Resources/mobile-signup.png)<br />
About - Mobile<br />
![Image one of Mobile](./Resources/mobile-about.png)<br />

---

Landing view - Fold Mobile <br />
![Image one of Mobile](./Resources/Landing_Fold.png)<br />
Hamburger menu - Fold Mobile <br />
![Image one of Mobile](./Resources/Menu_Fold.png)<br />
List - Fold Mobile <br />
![Image one of Mobile](./Resources/List_Fold.png)<br />
Comment on a park - Fold Mobile <br />
![Image one of Mobile](./Resources/Comment_Fold.png)<br />
Sign In - Fold Mobile <br />
![Image one of Mobile](./Resources/SignIn_Fold.png)<br />
Sign Up - Fold Mobile <br />
![Image one of Mobile](./Resources/SignUp_Fold.png)<br />
About - Fold Mobile <br />
![Image one of Mobile](./Resources/About_Fold.png)
<br />

## **Project Management:**

<!-- State chosen standards and planning methodology -->

Picnic Victoria chose a Kaban workflow management system as their chosen agile management style, specifically for it's simplified visualisation of the team work load. <br />

Individual developers manage their code and their workflow where it is _code reviewed_ before raising the pull request. This was specifically helpful in this documentation stage where all the team needs to be across the entire breadth of functionality and features. <br />

One thing that the team did not implement but will implement in Part B are deadlines on cards. Part A's due date was close enough and everyones social and work calendar too complicated to assign dates. The team worked together in a regard to not require such stringent reminders, but have assessed the need for it in Part B.

Kaban features include:

- Card rating system: low, medium, high.
- Adding members to cards.
  ![Image one kaban style projectment](./Resources/Kaban_detail_1.png)
- Watching necessary cards,
- Comments,
- attachments to ensure links to other softwares are easily accessible,
  ![Image one kaban style projectment](./Resources/Kaban_detail_2.png)
- Checklists: Completed/Code Reviewed/Raised Pull Request,
  ![Image one kaban style projectment](./Resources/Kaban_detail_3.png)

<br />

History of project movement.
![Image one kaban style projectment](./Resources/Kaban_start_1.png)
![Image two kaban style projectment](./Resources/Kaban_start_2.png)
![Image three kaban style projectment](./Resources/Kaban_start_3.png)
![Image four kaban style projectment](./Resources/Kaban_middle_1.png)
![Image four kaban style projectment](./Resources/Kaban_middle_2.png)
![Image four kaban style projectment](./Resources/Kaban_end_1.png)
![Image four kaban style projectment](./Resources/Kaban_end_2.png)
![Image four kaban style projectment](./Resources/Kaban_end_3.png)
