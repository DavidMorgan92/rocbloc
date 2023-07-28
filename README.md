# Roc Bloc

![Am I Responsive](documentation/images/amiresponsive.png)

## Table of Contents

1. [UX](#ux)

   - [Ideal User Demographic](#ideal-user-demographic)
   - [Project Goals](#project-goals)
   - [Business Goals](#business-goals)
   - [User Stories](#user-stories)
   - [Development Planes](#development-planes)

2. [Design](#design)

   - [Structure](#structure)
   - [Colour Palette](#colour-palette)
   - [Fonts](#fonts)
   - [Imagery](#imagery)

3. [Testing](#testing)

   - [Lighthouse Scores](#lighthouse-scores)

4. [Deployment](#deployment)

<a name="#ux"></a>

## UX

<a name="#ideal-user-demographic"></a>

### Ideal User Demographic

The ideal user for this website is:

- A new customer
- A current customer

<a name="#project-goals"></a>

### Project Goals

The site's users are gym members and potential members, who want to know more about the gym and its procedures.

<a name="#business-goals"></a>

### Business Goals

The gym is interested in attracting and retaining members.

<a name="#user-stories"></a>

### User Stories

As a new or current user I want:

1. To see what services the business offers
2. To book and pay for the services offered
3. To to stay up to date with changes to the business's offerings
4. To contact a member of the business team

As a business I want:

1. To showcase the business's offerings
2. To allow customers to book and pay for the services offered
3. To allow customers to sign up to our mailing list
4. To provide a point of contact for customers

<a name="development-planes"></a>

### Development Planes

#### Strategy

Strategy incorporates user needs as well as product objectives. This website will focus on the following target audience, divided into three main categories:

- Roles:
  - Current users
  - New users
- Demographic:
  - All ages
  - UK residents
  - Beginner to experienced climbers
- Psychographic:
  - Lifestyles:
    - Active
  - Personality/Attitudes:
    - Outgoing
  - Values:
    - Sense of community

The websites needs to enable the user to:

- See information about services offered:
  - Pay-as-you-go climbing sessions
  - Membership
  - Classes
  - Coaching
- Book a climbing session
- Sign up for the newsletter
- Contact a member of staff

The website needs to enable the site manager to:

- Gather information about booked climbing sessions
- Gather information about membership requests
- Gather information about newsletter sign-up requests
- Gather information about contact requests

![Strategy Table](documentation/images/strategy-table.jpg)

#### Scope

The scope plane is about defining requirements based on the goals established on the strategy plane. Using the information in the strategy plane, the identified required features have been broken into the following two categories.

- Content requirements:
  - The user will be looking for:
    - Prices for climbing
    - Prices for membership
    - Information about the company
    - Information about classes
    - Information about coaching
- Functionality requirements:
  - The user will be able to:
    - Request membership
    - Book a pay-as-you-go climb
    - Contact a member of staff
    - Sign up for the newsletter

#### Structure

The information above was then organized in a hierarchical tree structure, a site map, showing how users can navigate through the site with ease and efficiency, with the following results:

![Site Map](documentation/images/site-map.png)

#### Skeleton

Wireframes were made to showcase the appearance of the site pages while keeping a positive user experience in mind. The wireframes were created using a desktop version of Balsamiq.

##### Home

![Home](documentation/images/home.png)

##### Book a Climb

![Book a Climb](documentation/images/book-a-climb.png)

##### Membership

![Membership](documentation/images/membership.png)

##### Classes

![Classes](documentation/images/classes.png)

##### About Us

![About Us](documentation/images/about-us.png)

<a name="#design"></a>

## Design

<a name="#structure"></a>

### Structure

Overall website structure and design was inspired by https://www.theclimbinghangar.com/

<a name="#colour-palette"></a>

### Colour Palette

[This colour palette](https://coolors.co/palette/e63946-f1faee-a8dadc-457b9d-1d3557) was chosen for its strong red and selection of contrasting blues.

<a name="#fonts"></a>

### Fonts

The entire website uses the [Kanit regular 400](https://fonts.google.com/specimen/Kanit) font from Google Fonts

<a name="#imagery"></a>

### Imagery

### sarah.jpeg

Image from https://www.thebmc.co.uk/indoor-bouldering-the-lowdown under the Creative Commons Licence.

### group.jpeg

Image from https://www.pexels.com/photo/group-climbers-posing-together-7591300 under the Creative Commons Licence.

### climber.jpg

Image from https://www.shutterstock.com/image-photo/climber-boulder-gym-man-climbing-bouldering-1474754396 downloaded from Shutterstock under licence.

### father-daughter.jpg

Image from https://www.shutterstock.com/image-photo/father-his-daughter-rock-climbers-training-2175434795 downloaded from Shutterstock under licence.

### class.jpg

Image from https://www.shutterstock.com/image-photo/children-climbing-gym-1170325528 downloaded from Shutterstock under licence.

### coach.jpg

Image from https://www.shutterstock.com/image-photo/rock-climbers-climbing-gym-young-woman-1147315010 downloaded from Shutterstock under licence.

### climber2.jpg

Image from https://www.shutterstock.com/image-photo/couple-athletes-climber-moving-on-steep-1640478094 downloaded from Shutterstock under licence.

### favicon.png

Image from https://icons8.com/icons/set/bouldering under licence https://intercom.help/icons8-7fb7577e8170/en/articles/5534926-universal-multimedia-license-agreement-for-icons8

<a name="#testing"></a>

## Testing

<a name="#lighthouse-scores"></a>

### Lighthouse Scores

- [Home](documentation/lighthouse/index.pdf)
- [Book](documentation/lighthouse/book.pdf)
- [Membership](documentation/lighthouse/membership.pdf)
- [Classes](documentation/lighthouse/classes.pdf)
- [About](documentation/lighthouse/about.pdf)

<a name="#deployment"></a>

## Deployment

This project was developed using the [Codeanywhere IDE](https://app.codeanywhere.com/), commited to git and pushed to GitHub using the built in function within Codeanywhere.

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/DavidMorgan92/rocbloc) the following steps were taken:

1. Log into GitHub
2. From the list of repositories on the screen, select **DavidMorgan92/rocbloc**
3. From the menu items near the top of the page, select **Settings**
4. Select the **Pages** section
5. Under **Branch** click the drop-down menu labelled **None** and select **main** and click **Save**
6. Upon clicking **Save** the page is automatically refreshed and the website is now deployed
7. Go back to the main page of the repository
8. On the right, under **Environments**, an environment called **github-pages** should appear as active
9. Click this link and then click **View deployment** to see the website
