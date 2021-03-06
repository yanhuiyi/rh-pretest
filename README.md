# Open Ended Questions

- What are some best practices for ensuring proper accessibility support?
  In the technical level, I would like to follow technical standards such as,
  1. Provide semantic document tags and structure that helps keyboard navigation or screen reader
  2. Make sure link text meaningful
  3. Provide headers, footers or caption for table structure
  4. Set alternative text for image or link that enable screen reader to access
  5. Make sure content is clearly written with clear font face etc
  6. Test your website with a11y or WARIA tools before publishing

- How do you test to ensure your development work matches the design you are provided?
  1. First compare your accomplished work with design to eliminate obvious difference
  2. With the help of automation tools to ensure your changes won't introduce layout broken
  3. Sync-up with designers with your finished work to do design review if necessary
  
- What are some best practices for ensuring cross-browser compatibility?
  1. First, you should know the requirement of the work you will deliver, what platform, browser, and version the work should support
  2. Choose a library that your companies own or that compliance with your company policy will reduce the incompatibility issues
  3. Include browser prefix such as autoprefixer
  4. Use conditional commenting method to load specific external stylesheet for target platform
  5. Make good use of task runners such as Gulp, Grunt .etc to automate browser compatibility fixing
  6. Verification tools such as BrowserStack helps cross browser testing

- Have you used any design systems, if so which ones?
  
  [Alta](https://www.oracle.com/webfolder/ux/middleware/alta/index.html) is the one I used when worked for Oracle. We used another new design theme to rewrite UI of the project later on. I know some practice of [Material Deign](https://material.io/develop/web/).
  
- What are some pros and cons to working with a design system?
  ### Pros ###
  1. Consistency
  2. Quick to start work for non-designers
  3. New design can be built on top it
  4. Reusable
  ### Cons ###
  1. It limits new ideas to take sometimes
  2. Changes can become difficult along time
  
- What are some features you’d like to see added to the CSS/HTML specs?
  1. All text can be wrapped in a dedicated folder called, for example docs
  2. Images, icons put into a Assets folder
  3. A specification with space, box size clearly marked
  4. A completed design in multiple devices screen size
  
- In your career to-date what are you most proud of?
  - When I worked for RealNetworks, I worked with designers closely, and proposed to create a more dynamic look and feel deesign for real.com; Worked with designers by providing prototypes. Finally the proposal was taken. The new website gained more page view. 
  - Another one is when I worked in TheKnot, where there were several talent designers, I participated in design review flow and gave feedback to designers and tweaked the page in a quick way. I proposed to develop a HTML Email generator tool to free the developers from repetitive work, which was taken by managers and saved a great deal of time for the team.

# Practical Exercises
Web pages are tested on following browsers,
- Google Chrome Version 78.0.3904.108 (Official Build) (64-bit)
- Firefox Browser 71.0 (64-bit)

## Verify locally
1. Clone repo in your box
2. Access Exercise 1 - Bootstrap by <your path>/Exercise1/src/index.html
3. Access Exercise 2 - Vanilla CSS by <your path>/Exercise2/src/index.html
4. Access Exercise 3 - layout by <your path>/Exercise3/exercise-3.html
  
## Verify online
The pretest code is deployed into Netlify. Typing in following URL in location of your browsers.
1. https://eager-poitras-bb5243.netlify.com/exercise1/src/index.html
2. https://eager-poitras-bb5243.netlify.com/exercise2/src/index.html
3. https://eager-poitras-bb5243.netlify.com/exercise3/exercise-3.html
