# Overview
Chatbots have recently become quite popular. They are being used by businesses to provide proactive assistance to their customers.
They have grown and improved to capitalize on social media and messenger platforms. Most people haven’t openly identified the true potential of chatbots, so this article is designed to act as a guide to build chatbots on Engati Platform.

*Billions of people are already using chatbots, so it’s time your business did too.*

## The Idea
Ever felt lost and directionless while in a huge mall?

This bot addresses this problem by providing a **hyper-local map with the relative location** of whatever brand/store, restaurant, restroom/elevator or mall-amenity the user wants to know.  Apart from providing a catalogue of services and stores the mall can offer, the bot also serves a medium for **Business to Consumer(B2C) Marketing** for the brands/stores in the mall to broadcast their latest offers/sales. The bot also provides a functionality to contact the mall help-desk when desired.

**Note** - This bot is targeted for Phoenix Marketcity Pune, as a proof of concept , it only includes a set percentage of all stores currently in the mall.

## Industry & User Segment
The bot is targeted for *Malls/Supermarkets/Shopping Complexes*.

This bot is aimed to provide *assistance to all people visiting the mall regardless of age*. Since, it provides an ability to explore an a huge area quickly, it will be of *great use for tourists and first-time visitors* who have no idea about the location of stores within the mall.

## How does Engati work?
This is very simple - Engati offers two major functionalities to help create the bot- **Paths** & **FAQs**. 

*Paths* can be defined as different waterfalls or flows which the bot can take. They define what the bot is going to reply to user in case of a specific intent.

For Eg- For a Restaurant Bot you may have paths like - View Menu, Order, Cancel Order, View Discounts, Track Order etc


*FAQs* define the many ways a bot could interact with the user. This functionality allows you to define various utterances/phrases for the defined paths. 

For Eg- For a Restuarant Bot, to view menu you can have FAQs like - "Show me the menu", "What cuisines do you serve?", "Can I see the menu?" etc

**Note** - Apart from the mentioned functionalities, Engati also offers a lot of other smart features which we are going to find out about as we proceed.

## Building the Idea
We started by charting out the various major features/information and functionalities the bot could offer to the user-

Given below is an brief list of functionalities of the bot-

**Services & Stores Catalogue** - Gives a carousel of services, stores and amenities in the mall.
  
**Shop Categories** - Gives a carousel of shop categories in the mall.

**Eat/Restaurant Categories** - Gives a carousel of the cuisines served at various restaurants in the mall. 
 
**Entertainment Categories** - Gives a carousel of all cinema halls, bars and gaming zones in the mall. 

**Utilities Categories** - Gives a carousel of all mall-amenities. 

**Offers** - Gives a list of current offers in stores.(From Mall-Backend) 

**Help** - Provides mall help-desk contact and services/stores in mall. 

### Defining Paths
We started out by covering basic features of the bot, but the platform's rich features allowed us to create upto 20 paths covering almost all features we thought of comprehensively.

![Path-picture](https://image.prntscr.com/image/ufXm2CkWQr_Wj2ETMqJagw.png "Engati Paths")

While creating paths we came across two cool features of the platform-

1. **Add a Node** - This basically allowed us to communicate with the user in every way possible.
![Node-picture](https://image.prntscr.com/image/qtzdY7V_SaSkGkr1abHg3g.png "Engati Nodes")

2. **Declaring & Accessing Variables** - We can readily access variables with key user-data anywhere on the platform like {{var_name}}.
![var-picture](https://image.prntscr.com/image/xvBJtzg8QnqK-F1HTX0TAQ.png "Engati Var")

### Defining FAQs
Now, this was a fun part. We had to define and train the bot with utterances/FAQs which will be used to trigger any of the paths we defined above.

This is how we did that -

![FAQ](https://image.prntscr.com/image/1OTCu6wST_GopNp7wD1gKQ.png "FAQ pic")

The picture above shows some classified sample utterances for trigger paths. 

### Integrating Back-End with Engati

## Configuring Channels
Once we were done building the bot, we decided to integrate and test it out on platforms like - Facebook Messenger and our own website.

Configuring Facebook Messenger as a channel took just 5-10 minutes, the bot was live in ASAP.

![FB](https://image.prntscr.com/image/W_WFzpk0S1y4DVd1CyQ5gQ.png "Fb")

For adding the bot to our website, we just had to add a few scripts in the HTML code and it was up and running!

![web](https://image.prntscr.com/image/oTBUmI1ESme3viJ6rr6FRQ.png "web")

## Main Takeaway
* The platform allowed us to create, train and deploy a chatbot on multiple channels, in minutes, without writing any code.

* The platform’s ability to deploy continuously saved a lot of our time while testing out flows and features.

* We were able to connect our bot to Facebook Messenger channel and configure the persistent menus without going through Facebook’s Messenger App Review.

* The platform is intuitive (better than API.AI), well defined and has a pretty easy learning curve, it provided us with a wide array of ways to interact with the user.

* The pre-configured ability of bot to handle small-talk is pretty great and keeps the conversation flow intact.

* The comprehensive analytics offered by the platform (user engagement and retention) are pretty great and saves the pain of using 3rd party tools like Bot Analytics (https://botanalytics.co/)

