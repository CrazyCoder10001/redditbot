import praw 

user_agent = ("ChicasMagicRainbowBot")

r = praw.Reddit(user_agent = user_agent)

subreddit = r.get_subreddit("fivenightsatfreddys")

for submission in subreddit.get_new(limit: 3):

    print "Wow, what a moron!"
    print "You suck"
    print "Haha +
    
   
