# css-course

## Week1
###videos(1-4)
1. /* Any Element With Class Title */
  .title {
  }
  
  /* a navigation bar using id */
  #nav {
  }
  
  /* all div elements in your file */
  div {
  }
  
  /* any heading h2 in your file */
  h2 {
  }

2. <!-- extenral css file -->
  <link rel="stylesheet" href="css/file.css" />
  
  <!-- internal css -->
  <style>
  p {
    color: red;
  }
  </style>
  
  <!-- inline css-->
  <p style="color: blue;">This Is Our Paragraph</p>

3. <!-- Write Path -->
   <link rel="stylesheet" href="assets\css\master.css\" />

4. <!-- Write Path -->
   <link rel="stylesheet" href="source\css\main.css" />

5. /* Valid */
  ._user-name {
  }
  
  /* valid */
  .-user-name {
  }
  
  /* not valid / starts with a number */
  .1user-name {
  }
  
  /* Not valid / contains an @ symbol */
  .@user-name {
  }
  
  /* invalid */
  .user@name {
  }
  
  /* valid */
  ._user10name {
  }
  
  /* valid */
  .u {
  }

6. /* good */
  .USERNAME {
  }
  
  /* bad */
  .UserName {
  }
  
  /* good */
  .user-name {
  }
  
  /* bad */
  .userName {
  }
  
  /* bad */
  .usernameprofile {
  }
