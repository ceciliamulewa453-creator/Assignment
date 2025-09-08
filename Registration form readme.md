# Registration Form 

## Project Description

This project contains a fully semantic and accessible **traditional HTML registration form** that uses basic HTML elements. 

The form collects user details including personal information, contact information, address, and preferences.

## Purpose of the Form

The form gathers:

- **Personal Information:** Title, full name, date of birth, and gender.
- **Contact Information:** Email address and phone numbers.
- **Address:** Street address, city, state, postal code, and country.
- **Preferences:** Newsletter subscription and preferred contact method.

## File Structure

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Registration Form</title>
</head>
<body>

  <h1>Registration Form</h1>

  <form action="#" method="post">

    <!-- Personal Information Section -->
    <div role="group" aria-labelledby="personal-info-label">
      <h2 id="personal-info-label">Personal Information</h2>

      <p>
        <label for="title">Title</label><br />
        <select id="title" name="title">
          <option value="">Select your title</option>
          <option value="mr">Mr</option>
          <option value="mrs">Mrs</option>
          <option value="miss">Miss</option>
          <option value="dr">Dr</option>
          <option value="prof">Prof</option>
        </select>
      </p>

      <p>
        <label for="firstName">First Name</label><br />
        <input type="text" id="firstName" name="firstName" />
      </p>

      <p>
        <label for="middleName">Middle Name</label><br />
        <input type="text" id="middleName" name="middleName" />
      </p>

      <p>
        <label for="lastName">Last Name</label><br />
        <input type="text" id="lastName" name="lastName" />
      </p>

      <p>
        <label for="dob">Date of Birth</label><br />
        <input type="text" id="dob" name="dob" placeholder="MM/DD/YYYY" />
      </p>

      <p>
        <label>Gender</label><br />
        <input type="radio" id="genderMale" name="gender" value="male" />
        <label for="genderMale">Male</label>

        <input type="radio" id="genderFemale" name="gender" value="female" />
        <label for="genderFemale">Female</label>

        <input type="radio" id="genderOther" name="gender" value="other" />
        <label for="genderOther">Other</label>
      </p>
    </div>

    <!-- Contact Information Section -->
    <div role="group" aria-labelledby="contact-info-label">
      <h2 id="contact-info-label">Contact Information</h2>

      <p>
        <label for="email">Email Address</label><br />
        <input type="text" id="email" name="email" />
      </p>

      <p>
        <label for="phone">Phone Number</label><br />
        <input type="text" id="phone" name="phone" />
      </p>

      <p>
        <label for="altPhone">Alternate Phone Number</label><br />
        <input type="text" id="altPhone" name="altPhone" />
      </p>
    </div>

    <!-- Address Section -->
    <div role="group" aria-labelledby="address-label">
      <h2 id="address-label">Address</h2>

      <p>
        <label for="address1">Address Line 1</label><br />
        <input type="text" id="address1" name="address1" />
      </p>

      <p>
        <label for="address2">Address Line 2</label><br />
        <input type="text" id="address2" name="address2" />
      </p>

      <p>
        <label for="city">City</label><br />
        <input type="text" id="city" name="city" />
      </p>

      <p>
        <label for="state">State / Province / Region</label><br />
        <input type="text" id="state" name="state" />
      </p>

      <p>
        <label for="postalCode">Postal / Zip Code</label><br />
        <input type="text" id="postalCode" name="postalCode" />
      </p>

      <p>
        <label for="country">Country</label><br />
        <select id="country" name="country">
          <option value="">Select your country</option>
          <option value="india">India</option>
          <option value="usa">United States</option>
          <option value="uk">United Kingdom</option>
          <option value="australia">Australia</option>
          <option value="canada">Canada</option>
          <option value="other">Other</option>
        </select>
      </p>
    </div>

    <!-- Preferences Section -->
    <div role="group" aria-labelledby="preferences-label">
      <h2 id="preferences-label">Preferences</h2>

      <p>
        <label for="newsletter">Subscribe to newsletter?</label>
        <input type="checkbox" id="newsletter" name="newsletter" value="yes" />
      </p>

      <p>
        <label for="contactMethod">Preferred Contact Method</label><br />
        <select id="contactMethod" name="contactMethod">
          <option value="">Select an option</option>
          <option value="email">Email</option>
          <option value="phone">Phone</option>
          <option value="sms">SMS</option>
        </select>
      </p>
    </div>

    <p>
      <input type="submit" value="Submit" />
    </p>

  </form>

</body>
</html>
</a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
