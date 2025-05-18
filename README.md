CSE 110 LAB 7
Teammate:
Zhenyu Jiang

Katy Stadler (A17301232)

## Expose

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed would be the answer since we want everyone follow the same guideline as we test the code. As a result, set up the test to the Github action can automatically check our work as we update the branch so it won't cause a greater issue later.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   No if only for simple task like return output, JUnit test will be better

## Explore
3. What is the difference between navigation and snapshot mode?
- Navigation mode loads the page from scratch while snapshot audits the page in its current state. Navigation mode is better for looking at overall performance of the page while snapshot mode is better for finding accessibility issues.
4. Name 3 things we could do to improve the CSE110 shop site based on the Lighthouse results.
- Properly size images -- images are being loaded and data is wasted because they're oversized
- Serving images in formats like Webp and AVIF could provide better compression than PNG or JPEG
- Missing `<meta name="viewport">` tag which optimizes for mobile screens. It's also important because it prevents a delay for user input 
