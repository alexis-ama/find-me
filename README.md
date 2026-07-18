# Enter the Password
Enter the password to unlock a USDA Tech recruiting website
[Link to site](https://enter-the-password.netlify.app/)

## Description
“Enter the Password” is a tool that is meant to be used by USDA (U.S. Department of Agriculture) representatives at career fairs and conferences to creatively recruit for entry-level positions. It is designed as a website puzzle that tests the skills of the users who attempt to solve it. When they open the website, the user is welcomed with a password field. They will have to read carefully and think outside the box to figure out the hidden password. Once they enter the password, they are directed to a contact form where they can enter their contact information and preferred tech field and potentially be reached out to with USDA early-career resources in the future. 

## Getting Started
### Dependencies
* Access to a web browser (Ex. Firefox, Google Chrome, Safari, etc.)

### Installation
To get a local copy of the project, please do the following:

1. Open Terminal. After each of the following commands, press the ‘Enter’ key.
2. Create or choose the directory that you want the project in. Then, type 
```
cd directory-name
``` 
3. Type
```
   git clone https://github.com/alexis-ama/find-me.git
```

### Updating the Password
* The password defaults as “USDATECH”.
* It is assigned to the variable, x50617373776F7264, as a series of hex values that are concatenated to a String with the Javascript String.fromCharCode function.
* The hex values are ```(0x55, 0x53, 0x44, 0x41, 0x54, 0x45, 0x43, 0x48)``` which can be converted to ASCII letters → 
0x55 - U,
0x53 - S,
0x44 - D,
0x41 - A,
0x54 - T,
0x45 - E,
0x43 - C,
0x48 - H
* The conversion can be done using an [online tool](https://www.rapidtables.com/convert/number/hex-to-ascii.html) or referring to a Hex and ASCII table.
* To change the password, the x50617373776F7264 variable can be replaced with different hex or non-hex characters. These characters could be concatenated to a String version or just kept as their original forms concatenated.

## Redeploying
1. Open Terminal.
2. Type cd enter-the-password. 
3. Type 
```
git commit -m “message"
git push
```
4. Follow the steps on the [GitHub Pull Request tutorial](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#creating-the-pull-request) to get permission to add your changes to the project.

## Running the Website
### Testing the Password
1. To test the program, open your computer’s file directory and locate the index.html file in the project folder.
2. Now, you are able to test passwords by typing them directly in the password field.

### Testing Form Submissions:
1. Enter the password in the first page. 
2. Enter a dummy name and email. (Optional: Also select at least one interest area).
3. Open the project on Netlify.
4. Go to the ‘Forms’ section on the left-hand side.
5. Click on ‘contact’ under ‘Active forms’ to view all form submissions.
6. Click on the dropdown menu of each submission to view contact information and selected area(s) of interest.

## Limitations
The contact form currently runs under the Netlify base (free) plan which has a limit on the number of project deployments per month (about 20 per month). This means that the host for the form submissions may need to be changed if there is a high volume of project deployments. However, there is no limit on the number of form submissions, so any number of users can enter their contact information in the form.

## Tech Stack
* HTML
* CSS
* Javascript

## Sources
* [USDA Mission](https://www.usda.gov/about-usda/general-information/our-agency) 
* [USDA Current open early-career opportunities](https://www.usda.gov/farming-and-ranching/agricultural-education-and-outreach/youth-agriculture/internships-and-career-opportunities)
* [USDA Logo](https://www.usda.gov/)
* [Password-protected website tutorial](https://www.tutorialspoint.com/article/how-to-password-protect-a-page-using-only-html-css-and-javascript)

## Author
I’m Alexis Ama, a student at the University of Maryland, and I completed this project as part of a microinternship for USDA. I worked under the supervision of Fredy Diaz, the USDA Deputy Chief Data & AI Officer.
