## :computer: Task Description:

A company is looking for a web developer capable of creating a simple full-stack website related to Human Resource Management.

### 🧮 Website Theme:

<!-- Here, we have provided you a list of `7 different types of categories to build your brand-based website`. You are required to select `a single category` from the following list to build your website. Your website cannot have more than `one category type`. For instance, if you choose `Technology and Electronics`, your website will have products related to `Technology and Electronics` only; :x: `you cannot add other products`:x: related to Fashion and Apparel, Food and Beverage, etc. -->

### :writing_hand: Main Requirements

1. Make sure your design and website idea is unique. First, finalize your idea (what type of website you want to build). Then google the site design or visit `themeforest` to get your website idea. [You can visit this blog to collect free resources for your website](https://bootcamp.uxdesign.cc/free-images-and-resources-collection-for-website-c77f2fc46ce5). However, your website :x: `can not be related to your previous assignments or any demo project displayed in the course or in our conceptual sessions` :x:.

2. Home page will have a navbar, banner, footer and at least 6 Employee Card having the following information: `employee image`,`employee name`.

   > **Note:** When a user sign up / login with google the employee info[name,image] will be saved on database.

3. The navbar will have website name with logo, Home, All Employee List, Dashbaord, Apply For Leave, Employee Leave List, Blog, and Login.

4. Add two extra sections in the home page , make sure it is related to your project.

5. Create an `Apply For Leave` page where there will be a form for the user to apply for a leave. The form will have:

   - Leave Reason
   - Leave Type
   - Leave Start Date
   - Leave End Date
   - Total Leave Days (Auto Calculate)
   - Apply Leave Button
     > **Note:** You should store the user id and email with these informations.Use this id to get data for a single user [for requiremnet number 6].

6. On clicking a Employee Card will redirect the user to the page having leave details based on the Employee. On that page, there will be some leave card.
   Each card will have:

   - Leave Reason
   - Leave Type
   - Leave Start Date
   - Leave End Date
   - Total Leave Days (Auto Calculate)
   - Leave Status (Pending / Approved / Rejected)

   > **Note:** By Default Leave Status will be pending. A user can update it from Employee Leave List Page .

7. On Clicking All Employee List Page, There will be table of all employee's having:

- Employee Name
- Employee Image
- Three button [pending/approve/reject].
  On clicking any button the status will be updated .

8. The Employee details route will be a private/protected route. Please make sure that if the user is not logged in, the private route redirects to the login page.

9. Clicking the `Apply Leave` button will store your leave information in to the database. Inform the user with a success message using a toast/alert. `Do not use the browser alert.`

10. Create a `Dashboard` page where a user will see all his/her added leaves with a `Update button`. If the user wants, he/she can delete a leave. The design is up to you. This will be a private/protected route.

11. Clicking on the `Update button` will redirect the user to a form page where the form will have:

- Leave Reason
- Leave Type
- Leave Start Date
- Leave End Date
- Total Leave Days (Auto Calculate)
- Update button
  On clicking Update button A user Can update his/her leave informations.

This will be a private/protected route.

12. You Must implement Email and password based Authentication. This means, you will have to implement the Registration and the login page. Users should be able to toggle between Login and Registration view .

> :warning: `Note:` Do not enforce `forget or reset password feature` and the `email verification method`, as it will inconvenience the examiner. If you want, you can add email verification/forget the password after receiving the assignment result.

On the Registration page, display errors when:

     The password

     - is less than 6 characters
     - don't have a capital letter
     - don't have a special character

On the Login page, display errors when:

    - password doesn't match
    - email doesn't match
    You can take the error message from firebase. You can show the error below the input fields or via alert/toast. If you use alert/toast, do not implement the browser alert.

13. Also, implement at least `one extra login` which could be (facebook, github, google, etc).

14. Once logged in, the user name, profile picture and the logout button should appear on the navbar. If the user clicks on the logout button, make sure to log him/her out.

15. Add a 404 page (not found page)

### :gift: Bonus Requirements:

1. **Commits & readme:**

   - Minimum 10 meaningful git commits on the client-side repository.
   - Minimum 5 meaningful commits on the server-side repository.
   - Create a readme for client-side and write about your project (at least 5 bullet points). ** Remember to add your client-side live link to your website here.**

2. After reloading the page of a private route, the user should not be redirected to the login page.

3. Make the website responsive. Make sure the site looks different on desktop and mobile responsive. Tablet responsive is optional

4. Implementing a dark/light theme toggle for the home page. It's optional to implement the theme toggle for the entire website.

### :scroll: Additional information:

1. You cannot load the data from a .json file. The data must be stored in the database and you must all the data from the database.
2. You can use a local or host image anywhere or use pictures from the internet. And it's ok if you have the image url, but the image link doesn't work.
3. You can use vanilla CSS or any CSS library.
4. Try to host your site on Firebase (Netlify hosting will need some extra configurations)
5. Host your server-side application on Vercel. If needed, you can host somewhere else as well.
6. Make Sure you deploy server-side and client-side on the first day. If you have any issues with hosting or GitHub push, please join the "Github and deploy" related support session.

### :pushpin: What to submit

1. Your github client-side repository
2. Your github server-side repository
3. Your live website link

### Deadline

এই এসাইনমেন্ট মুলত তিন দিনের এসাইনমেন্ট। অর্থাৎ আগামী 20 October, রাত ১১.৫৯ এর মধ্যে তোমার এসাইনমেন্ট জমা দিলে তোমার সর্বোচ্চ মার্কস ৬০ মার্কস (৫০ এসাইনমেন্ট এর মার্কস + ১০ মার্কস বোনাস) । আর তুমি যদি এসাইনমেন্ট October 21 তারিখ সন্ধ্যা ৫.৫৯ এর মধ্যে সাবমিট করে তাহলে সর্বোচ্চ মার্কস ৫০। এর পরে সাবমিট করলে তোমার সর্বোচ্চ মার্কস ৩০।

### :trophy: No Pain, No Gain:

- The most beautiful moments in life comes after going through hardships and challenges.
