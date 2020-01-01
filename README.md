# dokumentation

A crucial step for a **successful** project is documentation.
But don't forget to update it from time to time so it stays relevant and useful.
There are many ways for documenting a piece of code. In this case we will be working on both soft and technical docunentation for your newly created fetch-wrapper npm module.

## Keep your documentation updated.
Every change in code must be followed by a relevant change in documentation. Otherwise documentation soon becomes outdated, which is equal to the absence of documentation. A README on the Git repo hopefully is more in sync with the project because when you make changes to the code you're "forced" to update the README too (otherwise users will complain).
A README is a crucial but basic way of documenting your project. Every project should at least have a README!

## Suggestions for a good README
There are many formats that you might choose for your README. The best approach is to have a **general, informative format.** That way people can easily understand what your project is about and start working on it.

1. #### What problem your project solves? ####

      The first thing to add to your document is a clear definition of what is the name of the project and **what problem it        solves.** It is better to have one or two sentences. People are going to be visiting your page from many sources and, hence, have different perspectives. That’s why you have to be very precise and avoid vague descriptions. 

2. #### Quick start and installation steps ####

    Most people do not like to wait. So do your users. Let them launch and try your project as fast as you can. Prepare a simple short list of steps needed to setup the project and put it on top of documentation front page. Usually it may be a list of commands required to setup an environment and start the application.

    > People will simply copy and paste your code. Keep this in mind and make sure to double check this yourself by executing it. Avoid placing some invisible characters to code examples. It is even better to use code and blockquote tags to embed code blocks.
    
    
    Example of embed code:
    ```
    npm install foobar
    ```

3. #### Usage ####

    After you've told users how to install your project locally, you can include brief instructions on how to use it. Use examples, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples.
    
    ```
    import foobar

    foobar.pluralize('word') # returns 'words'
    foobar.pluralize('goose') # returns 'geese'
    foobar.singularize('phenomena') # returns 'phenomenon'
    ```

4. #### Support ####
    
    Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.
    
5. #### Licence ####

    For open source projects, tell how it is [licenced](https://choosealicense.com/)


