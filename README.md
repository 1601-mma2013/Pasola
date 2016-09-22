## Group Members

- Hazmi Bin Halid 1132702612
- Mohammad Haziq Shariff Bin Mohamed Haniff 1132702039
- Mohamad Shafiq Faisal Bin Mohamad Najib 1132701768

# **Odigós** - *Augmented Reality Shopping Guidance System*

# I. Analysis

## 1. Research

### a. Scope

1. Objectives
   To create a shopping guidance system inside a retail store.

   ​

2. How

   Providing directions to specific products on store shelves inside clients retail store.

   ​

### b. Audit
1. Field (market) research

   In the past few years, a great amount of interest has been shown to develop indoor navigation systems for the common user because indoor mapping  can help customers find what they need. Retailers are starting to implement such technologies inside their store. The easier that retailers make it for shoppers to find what they’re looking for, the less likely those consumers are to leave a store without making a purchase. According to a national survey commissioned by Aisle411, 20% of shoppers have departed a store without fulfilling their purchase intent, and 84% have had difficulty finding products on the crowded shelves of retailers. Employing a team of sales associates to help customers find what they’re looking for is an expensive (and in many cases ineffective) solution to the problem. Nearly three-quarters of consumers with smartphones (or 73%) say they would rather use their mobile devices in a store than ask an associate for help.

   ​

2. Competitors / alternatives / replacement

   - **WIFARER** - http://www.wifarer.com/

     Pros

     - Support alternative paths.
     - Including walking time and distance.

     Cons

     - Complex maps layout

   - **Indoor Google Maps** - https://www.google.com/maps/about/partners/indoormaps/

     Pros

     - Excellent search capabilities - Very intuitive!
     - Visually appealing maps.
     - The service is available free of charge.

     Cons

     - No aerial photos.

   - **MazeMap** - https://www.mazemap.com/

     Pros

     - Complete search-find-navigate solution for all indoor locations that supports MazeMap.
     - Quick searching with search suggestions.

     Cons

     - No aerial photos.

   - **Aisle411** - http://aisle411.com/

     Pros

     - Implements Augmented Reality technology.
     - Supports a wide variety of indoor positioning technologies, including wi-fi, beacon, magnetic, visible light communication and computer vision.
     - Has the capabilities to search for products.

     ​

3. Relevant technologies

   - Using Wi-Fi for client based indoor positioning can be beneficial because in many cases existing infrastructure can be used. This could be for example Wi-Fi enabled cash register systems, routers and client hotspots. It is not even necessary that the devices are connected with the access points to determine their position.

   - Augmented Reality is the integration of digital information with live video or the user's environment in real time. Basically, it takes an existing picture and blends new information into it.

     ​

4. Users

   Clients and Shoppers.

   ​

### c. Stakeholder Interviews
1. Project vision

   - We intend to provide our clients with the best shopping guidance app for customers to use inside their retail store.

     ​

2. Risk
   - Inaccurate positioning and navigation.

   - Wrong list of products inside clients retail store.

     ​

3. Obstacles
   - Developing an indoor navigation system can be hard because of it's limited use of technology to detect users location.

   - Relying exclusively on Wi-Fi would mean that a lot of devices are excluded because not all smartphones or tablets support client based positioning via Wi-Fi.

   - Competing with other competitors.

     ​

4. Constraints 
   - Viable technologies.

   - Developing Odigós will need experience programmers and the cost of it will be expensive.

     ​

5. Opportunities 

   In spite of the obstacles we have, this project has strength from:

   - Dedicated developers to keep the application up to date and smooth as possible.

   - High security to avoid data leak.

     ​

### d. User observations
1. Users

   **Shoppers**

   These are the outcomes of our observations as well as the results of the survey that we have conducted inside one of many retail stores in local shopping mall, Sunway Pyramid. 50 people have participate in the survey.

   ​

   ![alt tag](http://i64.tinypic.com/2qlsnis.jpg)

   ​

   ![alt tag](http://i63.tinypic.com/2pop2m9.jpg)

   ​

   ​

2. Behaviors

   Based on our observations, we can categories shoppers into five groups and later did a survey on shoppers to determine their behavior when visiting a retail store:

   - **Touchy** -  Shopper that picks up something and then usually purchases it.

   - **The Lingerer** - Shoppers that like to take their time going through a store.

   - **Guerrilla Shopper** - The opposite of The Lingerer. These shoppers waits until the last minute, especially around the holiday season, and then runs around frantically, trying to get all the shopping done in one shot.

   - **The Sales Junkie** - These people are subjected to a spillover effect. If they see one bargain, they think everything in the store is a bargain, making them apt to spend more money.

   - **The Social Shopper** - This type enjoys shopping with friends and almost never shops alone, they tend to make a lot of impulsive purchases.

     Ref: http://www.marketingteacher.com/consumer-behavior-shopping-habits/

   ​

   ![alt tag](http://i67.tinypic.com/27yzbzd.jpg)

   ​

3. Attitudes

4. Aptitudes
   - users’s ability to learn something quickly and do it well

5. Motivations

6. Environments

7. Tools

   ​

   ![alt tag](http://i66.tinypic.com/21kfa1d.jpg)

   ​

8. Challenges

   ​

   ![alt tag](http://i64.tinypic.com/hsmixg.jpg)




   ![alt tag](http://i64.tinypic.com/2lnya0z.jpg)

Shoppers agreed that they sometimes had a hard time finding products that they wanted to buy and then  proceed to leave the store without making any purchase. This is the same as the national survey commissioned by Aisle411 where they said that 20% of shoppers have departed a store without fulfilling their purchase intent, and 84% have had difficulty finding products on the crowded shelves of retailers.

## 2. Modeling

### a. Personas

**Name**: Sarah Amanda

**Gender**: Female

**Occupation**: Accountant

**Age**: 28

------



1. Goals: *To complete a shopping session*
2. Behavior: *Likes to take her time going through a store*
3. Attitudes: *Always on time and likes to be punctual*
4. Environments: *The Face Shop (Cosmetic Retail Store in Sunway Pyramid)*
5. Tools: Smartphone
6. Challenges: (Can't find a place to change her baby's diaper, Needs to follow signage which are not accurate)

*Scene:* Amanda is inside a shopping mall called D'Pulze. After entering the mall, her son kept on crying because of full diaper. She had a very hard time finding a baby changing station. She needs to follow signage at the mall but still failed at finding the spot. Finally after multiple time running back and forth, she found the baby changing station.

### b. Other Models

Represent domain factors beyond individual users and customers

1. Workflows among multiple people
2. environments
3. artifacts

# II. Synthesis

## 3. Requirements Definition

### a. Context Scenarios

1. While getting ready in the morning, Sarah open the Odigós app on her smartphone to create a shopping checklist on what things she need to buy later on that day.
2. After she finished her class, she drove to the Sunway Pyramid shopping mall and after she parked her car and entered the mall, she took out her smartphones and open Odigós to refer back her shopping checklist.
3. She walked to Cold Storage to buy the things that she created on the shopping checklist. She ticks on the shopping checklist after she grabbed the things that she wants to buy from Cold Storage.
4. After she finished grabbing her things from Cold Storage, Sarah noticed on her phone that her son, Jackie just texted her asking her to buy Gatsby Moving Rubber purple color. She types the product name in the Odigós app search bar to find the product.
5. After she selected the correct product inside the app, Odigós will start to showing direction towards the product shelf on her smartphone screen by using her smartphone camera.
6. She walks to the location that has been set by Odigós and when she arrived at the store shelf where the product is stored and picks it up.
7. After that she double checked her checklist on the Odigós and then proceed to the counter to complete the payment.
8. Then she walk out from the store and went back home. Her son is very happy because Sarah managed to buy the product that he requested.


### b. Requirements

Describe necessary capabilities of the product

1. Functional and data needs
2. user mental models
3. design imperatives
4. product vision
5. business requirements
6. technology

## 4. Design Framework

### a. Elements

Deﬁne manifestations of information and functionality

1. Information
2. functions
3. mechanisms
4. actions
5. domain object models

### b. Framework

Design overall structure of user experience

1. Object relationships
2. Conceptual groupings
3. Navigation sequencing
4. Principles and patterns
5. Floor Plan
   1. flow
   2. sketches
   3. storyboards

### c. Key Path and Validation Scenarios

Describe how the persona interacts with the product
