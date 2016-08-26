import praw

user_agent = ("FredditArtworkBot")

r = praw.Reddit(user_agent = user_agent)

subreddit = r.get_subreddit("fivenightsatfreddys")

for submission in subreddit.get_flair("artwork"):

    print "That is some amazing artwork!"
    print "Wow! Cool drawing skills!"
    print "Nice job on that!!"
    print "I like it!"
    print "This is really good. Like **really** good.
    print "Haha I love it!"
    print "You are so talented!"
    print "Uhh... it's ok. Maybe use a bit more colour?
    print "I prefer pencil drawings."
    print "Eww it's so gross yet so great"
    print "Work on your shading darling."
    print "Meh. I've seen better."
    
