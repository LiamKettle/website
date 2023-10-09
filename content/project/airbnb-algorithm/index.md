---
url_pdf: ""
url_video: ""
external_link: ""
url_slides: ""
title: Evaluating Airbnb's Preferred Features
date: 2023-10-09T00:00:00.000Z
summary: Individual research conducting MaxDiff survey to identify user driven
  preferred Airbnb listing features
draft: false
featured: false
tags:
  - UX
image:
  caption: ""
  filename: icon-airbnb.png
  focal_point: Smart
  preview_only: true
url_code: ""
---
**Summary:** Airbnb has millions of users searching for accommodations around the world. Given the vast number of available listings, Airbnb recommends listings to users using an algorithm model that considers a number of various listing features and characteristics. Although Airbnb is transparent in which factors they consider influential to their recommendation algorithm, a key question is whether these factors align with users' perspectives. Through a MaxDiff survey and follow-up user interviews, findings indicated that price, location, and rating align well with users' perspectives, yet features such as self check-in, superhost status, and instant book were less important than expected.

Project overview: Understanding how Airbnb's search algorithm is aligned with user perspectives.

# Process:

## Identify current filters and features

* Identified available features to filter, researched recommendation algorithm

## Identify target population and constrains

* Individuals residing in the US

* Accommodation in the US

* College graduate students and young professionals

## Initial user interviews with 2 individuals to talk over filter features 

* discussed combining features that were relevant (e.g., smoke alarm and carbon monoxide alarm)

* identified uncertainty in features (e.g., what is considered "breakfast")

## Define set list of target features

* Decisions were made

* Keep certain items together: air conditioning and heating; washer and dryer

* Excluded accessibility features - through discussion with others, decided to exclude as do not want to overshadow accessibility needs when using the general population

## Administer survey online

* 28 participants - users of Airbnb

## Follow-up user interviews

* 4 participants


**Goals**

* Identify which Airbnb listing features/characteristics that are most or least important when selecting accommodation

* Identify whether users' perceived feature importance matches the current algorithm (as outlined on their website).

**Why MaxDiff?**

* Good discrimination among items - forces individuals to make a choice between multiple items rather than potentially rating everything as 4 or 5 out of 5 for importance.

* Reduces scale use bias

* Forces participants to pick their most and least preferred feature

* Easy to administer

* Works with a small number of participants


# Airbnb's Recommendation Algorithm

Airbnb is transparent about which features they use for their recommendation algorithm. Therefore, I used their specified features as comparisons. Three key characteristics are heavily prominent in their algorithm: **Quality, popularity,** and **price.** 

> **Quality.** The algorithm assesses many characteristics to evaluate quality, including the **listing photos, reviews of the listing, and listing characteristics.** Higher quality listings tend to rank higher in search.


> **Popularity.** The algorithm evaluates the popularity of a listing using a wide range of information, including **how guests engage with the listing** and **how often the listing gets booked.** Examples of guest engagement with a listing include how often guests save a listing to their wish list, how often guests book, and **how often guests message the Host.** More popular listings tend to rank higher in search.


> **Price.** To determine how attractive the price of a listing is, the algorithm considers a variety of price data, including **how the price compares to similar listings** in the area for the given dates. Listings that are priced below other comparable listings—other listings in the area with similar guest capacity and amenities—tend to rank higher in search.

* Quality includes features such as **listing photos, reviews of the listing, and listing characteristics**
* Popularity evaluates how guests engage with the listing and how often the listing gets booked
* Price considers a variety of price data, including how the price compares to similar listings





Other factors that influence search results:
* Location
* High quality listing photos
* Accurate list of amenities
* Superhost status
* Instant booking
* Guest influence


To focus on features selectable by users, 7 features were selected as core influencers of Airbnb's recommendation algorithm:
* Price
* Ratings
* Number of reviews
* Distance from the desired area
* High Quality Listing Photos
* Superhost status
* Instant book


# Procedure:

* Initially interviewed 2 individuals on features they would find comparable using the Airbnb filtering features plus features utilized in their own algorithm scheme.

* Cognitive walkthrough when pilot testing the survey - identify areas of confusion and add explanations at the start of the survey

"When you are considering Airbnb accommodation options within the US, **which one of the following 5 features is the LEAST important for you and which one feature is the MOST important to you?**"


| | Listed Features for Comparison | |
| - | - | - |
| Number of reviews | Accommodation rating | Price |
| Instant book | Self check-in | (Clothes) Iron |
| Air conditioning / Heating | Dedicated workspace | Hair dryer |
| Kitchen | TV | Washer / Dryer |
| Wifi | Free parking | Hot tub |
| Indoor fireplace | Pool | Smoking allowed |
| Host language | Distance from the desired area | High quality listing photos |
| Airbnb plus | Smoke alarm and/or carbon monoxide alarm | Superhost |


# MaxDiff survey

Participants were randomly presented 5 of the 24 features and asked to select their most important and least important features. There were 14 sets.


# Findings

## Survey

* **Price** has greatest relative preference in listing features.
* Next is **distance** and **accommodation rating**, followed by **wifi** and **air conditioning/heating**.
* Participants showed only slightly positive preference for **Superhost status** and **high quality listing photos**.
* Participants did not show positive or negative preference for **Airbnb Plus** and **Instant Book**.
* **Fireplace** consistently rated the least preferred feature.

## Interviews

### Misalignment of what key Airbnb features are
Participants were confused on what **Superhost** and **Airbnb plus** was.
> **Superhost:** "A Superhost is a nice feature if I am willing to give up autonomy"

> **Airbnb Plus:** "It'd be less overall fees potentially, or it's like all fees grouped together in one go ... I know that's probably not the right definition."

### Accommodation ratings and review number have a complicated relationship
Accommodation rating generally had greater preference than the total number of reviews, yet participants would skim reviews to make their final determination.

> "I will take more risks with fewer reviews because everyone has to start somewhere ... I would prefer a 4.6/5 with 100 reviews over a 4.8/5 with 5 reviews."

### Host interaction (well, lack of) matters!
Participants mentioned preference against interacting with a host at the accommodation, sometimes assuming host interaction is a part of Superhost status.

> "I don't really prioritize the social interaction of the host. I don't always know who the host is. Sometimes they're a little weird."

### Physical self check-ins can be a scavenger hunt!
One participant mentioned a bad experience of trying to search for a physical key external to the accommodation, but had good experiences with digital self check-ins.

> "They sent me photos of where to find the key. I have to walk out from the apartment, turn right, find a tree, and the key lock is under the tree. What would happen if someone decided to cut that tree? or if there was a storm or something?"





# Recommendations
* Enhance understanding of Airbnb specific terms such as **Superhost** and **Airbnb Plus**.
* Add a "general vibe" of reviews
* Enhance visibility of potential in-person host interactions
* Restructure what listing characteristics users can filter by


# Reflection

* Qualtrics is good for learning MaxDiff, but not for applying under their basic subscription. Next time, I would trial Sawtooth Software given their survey tools specific to conjoint analysis.



# The Technical
