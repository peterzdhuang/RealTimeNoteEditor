# RealTimeMD


# Core Features
    Web based real time mark down editor
    No account, no signups
    Create links for people to share
    Real-Time Collaboration
    Live cursor positions
    Character-by-character sync
    Conflict resolution


# Working on 

    I want to fix cursors, it doesn't actually track the cursor
    position, instead it gives the x,y of the cursor based a bounds

    But the thing is, the bounds could be different for different 
    screen sizes.

    So maybe I can get the bounds and manually adjusts it that 
    way?

    Also I want to refactor the functions, because right now its 
    so cluttered 


    Features to add:

        attributes for words
            - this is built into quill, so not that hard
        show highlight by the other person
            - this is also built into quill, but 
            will need to build new funcs in the backend 
            to accomadate this
        save the document to indexDB

        


