# Reading

## An introduction to NodeJS and Express

    Explain middleware, answer as though I were a non-technical recruiter.
      Anything that happens to the information put into the url and method before the request is sent, such as taking information such as params and using them to pull data, and such.

    Express the most popular __ __ ____.
      Node js framework.

    Express is “unopinionated.” What does that mean?
      You can structure your apps any way that you'd like and it won't stop you from doing so. With any middleware you'd like.

    What is a module and why is modularity useful to us as developers?
    Small additions(or large) that can do things for your code that run middleware for the code you are trying to run, it can help run your code by doing things for you when you call them.

## What is NPM?

    I am running 8.19.6 on my computer. If I were to install jslint onto my computer I would first get into the proper project I would want to install it on. I would then run npm jslint and it would install and be listed under packages in the package.json.

## What is TDD?

    Explain why tests are important. Please explain as though I were your non technical elder.
    Tests are important to coding to see how your code works before you've reached your finished project, and even during bug fixing at the end of development. There are many ways to test for errors, wether it be actual tests or simple console logs.
    What are three expected benefits of testing
    The Most important benefits of testing are 
      - It can catch errors before you find them when trying to present your code, or before someone has to experience the pain they cause when they are using your product.
      - If you do test driven development, it can paint a clearer picture of what the end goal should be, and any edge cases that you should implement or build around so that you don't have to restructure later
      -Tests throughout your code  may help you understand where along your code the error is happening at, and help you locate what area of code you need to fix.
    Tests may be written wrong, and you break your code trying to pass a test; you may also write to many tests and not understand which console log you are trying to look for in your console. Some issues when working on tests in teams is that you may have different ideas on what tests need to be implemented and fail to read the results or not understand why a test fails because its written convoluted. 

## CI/CD

    Continouos intergration is when you test the complete code to pass a series of tests to make sure that new branches of code don't break other parts of the code in ways that you might not account for, they are set up so that it does some extra thinking for you, and prevents future issues trying to trace where and why some other feature has broken. It encourages more commits, as less human testing has to be done before pushing and merging, and allows more code to be in github for the entire team to use. 
