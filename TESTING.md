# Testing

## Table of Contents

1. [Testing User Stories](#testing-user-stories)
2. [Manual Testing](#manual-testing)

   - [Home](#home)
   - [Book a Climb](#book-a-climb)
   - [Membership](#membership)
   - [Classes](#classes)
   - [About Us](#about-us)

3. [Automated Testing](#automated-testing)

   - [Lighthouse Scores](#lighthouse-scores)
   - [Code Validation](#code-validation)

## Testing User Stories

As a new or current user I want:

1. To see what services the business offers

   - Pay-as-you-go climbs are advertised on the booking page and the price is given.
   - Membership is advertised on the membership page and the price is given.
   - Classes and coaching are advertised on the booking page.

2. To book and pay for the services offered

   - There is a booking form on the booking page.
   - There is currently no way to pay through the website. This is a feature that can be added later.

3. To stay up to date with changes to the business's offerings

   - A newsletter sign-up form is shown on every page.

4. To contact a member of the business team

   - There is a contact form on the about page.

As a business I want:

1. To showcase the business's offerings

   - Pay-as-you-go climbs, membership, and classes and coaching are advertised on the website.

2. To allow customers to book and pay for the services offered

   - There is a booking form for pay-as-you-go climbs.
   - There is a sign-up form for membership.
   - There is currently no way to pay through the website. This is a feature that can be added later.

3. To allow customers to sign up to our mailing list

   - There is a newsletter sign-up form on every page.

4. To provide a point of contact for customers

   - There is a contact form on the about page.

## Manual Testing

### Home

**1.** The navbar _Home_ link navigates to the home page
<details>
   <summary>Before Action</summary>
     
   ![Before](documentation/testing/home/home-nav/before.jpg)

</details>

<details>
     <summary>After Action</summary>
     
   ![After](documentation/testing/home/home-nav/after.jpg)

</details>

**2.** The navbar _Book a Climb_ link navigates to the booking page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/home/book-nav/before.jpg)
     
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/book-nav/after.jpg)
     
</details>

**3.** The navbar _Membership_ link navigates to the membership page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/home/membership-nav/before.jpg)

</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/membership-nav/after.jpg)
     
</details>

**4.** The navbar _Classes_ link navigates to the classes page
<details>
   <summary>Before Action</summary>
   
   ![Before](documentation/testing/home/classes-nav/before.jpg)
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/classes-nav/after.jpg)
   
</details>

**5.** The navbar _About Us_ link navigates to the about page
<details>
   <summary>Before Action</summary>
   
   ![Before](documentation/testing/home/about-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/about-nav/after.jpg)
   
</details>
    
**6.** The _Book a Climb_ button navigates to the booking page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/home/book-button/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/book-button/after.jpg)
   
</details>
    
**7.** The _Book a Class_ button navigates to the classes page
<details>
   <summary>Before Action</summary>
   
   ![Before](documentation/testing/home/classes-button/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/classes-button/after.jpg)
   
</details>
    
**8.** The _Sign Up_ button scrolls the page to the sign up form
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/home/sign-up-button/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/sign-up-button/after.jpg)
    
</details>
    
**9.** The _Sign Up_ form submits to the Code Institute form dump page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/home/sign-up-form/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/home/sign-up-form/after.jpg)
   
</details>
    
**10.** Responsiveness
<details>
   <summary>320px</summary>

   ![320px](documentation/testing/home/responsiveness/320px.jpg)
   
</details>

<details>
   <summary>768px</summary>

   ![768px](documentation/testing/home/responsiveness/768px.jpg)
   
</details>

<details>
   <summary>1024px</summary>

   ![1024px](documentation/testing/home/responsiveness/1024px.jpg)
   
</details>

### Book a Climb

**1.** The navbar _Home_ link navigates to the home page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/book/home-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/home-nav/after.jpg)
   
</details>

**2.** The navbar _Book a Climb_ link navigates to the booking page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/book/book-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/book-nav/after.jpg)
   
</details>
    
**3.** The navbar _Membership_ link navigates to the membership page
<details>
   <summary>Before Action</summary>
   
   ![Before](documentation/testing/book/membership-nav/before.jpg)

</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/membership-nav/after.jpg)
   
</details>
    
**4.** The navbar _Classes_ link navigates to the classes page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/book/classes-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/classes-nav/after.jpg)
   
</details>
    
**5.** The navbar _About Us_ link navigates to the about page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/book/about-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/about-nav/after.jpg)
   
</details>
    
**6.** The _Become a Member_ button navigates to the membership page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/book/membership-button/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/membership-button/after.jpg)
   
</details>
    
**7.** The _Book Now_ form submits to the Code Institute form dump page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/book/book-form/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/book-form/after.jpg)
   
</details>
    
**8.** The _Sign Up_ form submits to the Code Institute form dump page
<details>
   <summary>Before Action</summary>
   
   ![Before](documentation/testing/book/sign-up-form/before.jpg)

</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/book/sign-up-form/after.jpg)
   
</details>

**9.** Responsiveness
<details>
   <summary>320px</summary>

   ![320px](documentation/testing/book/responsiveness/320px.jpg)
   
</details>

<details>
   <summary>768px</summary>

   ![768px](documentation/testing/book/responsiveness/768px.jpg)
   
</details>

<details>
   <summary>1024px</summary>

   ![1024px](documentation/testing/book/responsiveness/1024px.jpg)
   
</details>

### Membership

**1.** The navbar _Home_ link navigates to the home page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/membership/home-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/membership/home-nav/after.jpg)
   
</details>
 
**2.** The navbar _Book a Climb_ link navigates to the booking page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/membership/book-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/membership/book-nav/after.jpg)
   
</details>

**3.** The navbar _Membership_ link navigates to the membership page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/membership/membership-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/membership/membership-nav/after.jpg)
   
</details>
    
**4.** The navbar _Classes_ link navigates to the classes page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/membership/classes-nav/before.jpg)

</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/membership/classes-nav/after.jpg)
   
</details>

**5.** The navbar _About Us_ link navigates to the about page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/membership/about-nav/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/membership/about-nav/after.jpg)
   
</details>

**6.** The _Become a Member_ form submits to the Code Institute form dump page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/membership/membership-form/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>

   ![After](documentation/testing/membership/membership-form/after.jpg)
   
</details>
    
**7.** The _Sign Up_ form submits to the Code Institute form dump page
<details>
   <summary>Before Action</summary>

   ![Before](documentation/testing/membership/sign-up-form/before.jpg)
   
</details>

<details>
   <summary>After Action</summary>
   
   ![After](documentation/testing/membership/sign-up-form/after.jpg)
   
</details>

**8.** Responsiveness
<details>
   <summary>320px</summary>

   ![320px](documentation/testing/membership/responsiveness/320px.jpg)
   
</details>
    
<details>
   <summary>768px</summary>

   ![768px](documentation/testing/membership/responsiveness/768px.jpg)
   
</details>
    
<details>
   <summary>1024px</summary>

   ![1024px](documentation/testing/membership/responsiveness/1024px.jpg)
   
</details>

### Classes

- The navbar _Home_ link navigates to the home page
  - Before action:
    ![Before](documentation/testing/classes/home-nav/before.jpg)
  - After action:
    ![After](documentation/testing/classes/home-nav/after.jpg)
- The navbar _Book a Climb_ link navigates to the booking page
  - Before action:
    ![Before](documentation/testing/classes/book-nav/before.jpg)
  - After action:
    ![After](documentation/testing/classes/book-nav/after.jpg)
- The navbar _Membership_ link navigates to the membership page
  - Before action:
    ![Before](documentation/testing/classes/membership-nav/before.jpg)
  - After action:
    ![After](documentation/testing/classes/membership-nav/after.jpg)
- The navbar _Classes_ link navigates to the classes page
  - Before action:
    ![Before](documentation/testing/classes/classes-nav/before.jpg)
  - After action:
    ![After](documentation/testing/classes/classes-nav/after.jpg)
- The navbar _About Us_ link navigates to the about page
  - Before action:
    ![Before](documentation/testing/classes/about-nav/before.jpg)
  - After action:
    ![After](documentation/testing/classes/about-nav/after.jpg)
- The _Book a Class_ button scrolls down to the _Classes_ header
  - Before action:
    ![Before](documentation/testing/classes/book-class-button/before.jpg)
  - After action:
    ![After](documentation/testing/classes/book-class-button/after.jpg)
- The _1-2-1 Coaching_ button scrolls down to the _1-2-1 Coaching_ header
  - Before action:
    ![Before](documentation/testing/classes/coaching-button/before.jpg)
  - After action:
    ![After](documentation/testing/classes/coaching-button/after.jpg)
- The first _Find out More_ button scrolls to the top of the page
  - Before action:
    ![Before](documentation/testing/classes/find-out-more-button-1/before.jpg)
  - After action:
    ![After](documentation/testing/classes/find-out-more-button-1/after.jpg)
- The second _Find out More_ button scrolls to the top of the page
  - Before action:
    ![Before](documentation/testing/classes/find-out-more-button-2/before.jpg)
  - After action:
    ![After](documentation/testing/classes/find-out-more-button-2/after.jpg)
- The _Sign Up_ form submits to the Code Institute form dump page
  - Before action:
    ![Before](documentation/testing/classes/sign-up-form/before.jpg)
  - After action:
    ![After](documentation/testing/classes/sign-up-form/after.jpg)
- Responsiveness
  - 320px:
    ![320px](documentation/testing/classes/responsiveness/320px.jpg)
  - 768px:
    ![768px](documentation/testing/classes/responsiveness/768px.jpg)
  - 1024px:
    ![1024px](documentation/testing/classes/responsiveness/1024px.jpg)

### About Us

- The navbar _Home_ link navigates to the home page
  - Before action:
    ![Before](documentation/testing/about/home-nav/before.jpg)
  - After action:
    ![After](documentation/testing/about/home-nav/after.jpg)
- The navbar _Book a Climb_ link navigates to the booking page
  - Before action:
    ![Before](documentation/testing/about/book-nav/before.jpg)
  - After action:
    ![After](documentation/testing/about/book-nav/after.jpg)
- The navbar _Membership_ link navigates to the membership page
  - Before action:
    ![Before](documentation/testing/about/membership-nav/before.jpg)
  - After action:
    ![After](documentation/testing/about/membership-nav/after.jpg)
- The navbar _Classes_ link navigates to the classes page
  - Before action:
    ![Before](documentation/testing/about/classes-nav/before.jpg)
  - After action:
    ![After](documentation/testing/about/classes-nav/after.jpg)
- The navbar _About Us_ link navigates to the about page
  - Before action:
    ![Before](documentation/testing/about/about-nav/before.jpg)
  - After action:
    ![After](documentation/testing/about/about-nav/after.jpg)
- The _Contact Us_ form submits to the Code Institute form dump page
  - Before action:
    ![Before](documentation/testing/about/contact-form/before.jpg)
  - After action:
    ![After](documentation/testing/about/contact-form/after.jpg)
- The _icons8.com_ link opens a new tab to [icons8.com](https://icons8.com)
  - Before action:
    ![Before](documentation/testing/about/icon-link/before.jpg)
  - After action:
    ![After](documentation/testing/about/icon-link/after.jpg)
- The _Sign Up_ form submits to the Code Institute form dump page
  - Before action:
    ![Before](documentation/testing/about/sign-up-form/before.jpg)
  - After action:
    ![After](documentation/testing/about/sign-up-form/after.jpg)
- Responsiveness
  - 320px:
    ![320px](documentation/testing/about/responsiveness/320px.jpg)
  - 768px:
    ![768px](documentation/testing/about/responsiveness/768px.jpg)
  - 1024px:
    ![1024px](documentation/testing/about/responsiveness/1024px.jpg)

## Automated Testing

### Lighthouse Scores

- [Home](documentation/lighthouse/index.pdf)
- [Book](documentation/lighthouse/book.pdf)
- [Membership](documentation/lighthouse/membership.pdf)
- [Classes](documentation/lighthouse/classes.pdf)
- [About](documentation/lighthouse/about.pdf)

### Code Validation

The [W3C HTML validator](https://validator.w3.org/) was used to validate the HTML.
The [W3C CSS validator](https://jigsaw.w3.org/css-validator/) was used to validate the CSS.

- [styles.css](documentation/validation/styles.css.pdf)
- [index.html](documentation/validation/index.html.pdf)
- [book.html](documentation/validation/book.html.pdf)
- [classes.html](documentation/validation/classes.html.pdf)
- [membership.html](documentation/validation/membership.html.pdf)
- [about.html](documentation/validation/about.html.pdf)
