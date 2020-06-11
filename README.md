
Go through app and show how it meets requirements => 10-15 minutes

    (things we know how to do so far)

    # MVC program / file structure (easiest to just use Corneal app)
    # Must use Active Record with Sinatra
    # Must use multiple models, including a user model
    # Must have at least one has_many on a model and at least one belongs_to on a model
    # other misc things: github repo, commits, readme, license, blog post, vid walkthrough, 30-min code session. 

    (things we don't know how to do yet)
    # Must have user accounts => Sign up + log in/out functionality
    # Validate uniqueness of user login info (email/pw)
    # a logged-in user has full CRUD capacity for their *own* stuff
    # Users cannot edit or delete content that belongs to another user
    # Validations so that bad data cannot get into your DB - 
    # Show the user an error message that communicates why their attempt failed

Explain the flow of your program, answer questions related to your program => 10-15 minutes
    ## Most important: 
        # purpose of a migration (modify db structure), purpose of schema.rb (summary of current db/table structure)
        # request/response flow =>
            Processing a GET request =>
                ## E.G " __ request is made in the browser, and routed to __ route in __ controller, which then ___"
            Processing a POST request => 
                # how does the form display, and how is the form processed
                # what is params, and where do its keys come from?. What is its scope?

        # accessing objects through their associations (we sort of know how to do this)
        # rendering vs redirecting, and where we have access to controller instance variables
        # where we have access to the session hash, and how we can use it to log a user in/out
        # basics of encryption => what does bcrypt provide, what does 
        has_secure_password (from AR) provide. How is the password stored in your table?

    ## Important:
        # Using association methods to create objects (e.g. build/create)
        # A thoughtful commit history
        # A well-written readme
        # Code is generally well-designed and easy to follow
Live coding => 10-15 minutes
