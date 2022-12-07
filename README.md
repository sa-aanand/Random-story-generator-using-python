# Random-story-generator-using-python
# I created a random story generator bot using python in my beginner level. It's a mini project
import random

when_on = ["Few years ago",
               "Yesterday",
                   "Today"]

date = ["2 November 2004",
            "11 February 2005",
                 "10 NOvember 2003"]

where = ["Wankhede, Mumbai",
             "Lords, Australia",
                "Eden Gardens, Australia",
                   "Abu Dhabi, Dubai"]

who = ["Mahendra Singh Dhoni",
          "Sachin Tendulkar",
             "Virat Kohli",
                "Pardeep Narwal"]

proffesion = ["cricket",
                "kabaddi",
                   "hockey",
                      "badminton"]

what = ["scored 91 in world cup final",
          "scored 200 in T20",
             "scored 189 in IPL","scored 10 points"]

opposition = ["Pakistan",
                "England",
                   "Australia",
                     "Sri Lanka",
                       "South Africa"]

honour = ["Man of the match",
            "Man of the Series",
               "Player of the match"]

result = ["made India proud",
            "made fans feel proud",
               "made the Nation feel proud"]

captain = ["ODI",
             "Test matches",
                "T20",
                   "IPL"]

community = ["a small village",
               "the city"]

native = ["Punjab",
           "Jharkhand",
             "Andhra Pradesh",
                "Odisha"]

parents = ["Pan Singh and Devaki Devi",
              "Prem and Sarojini"]

studies = ["Delhi Public School",
             "DAV Jawahar Vidya Mandir",
                "Vishal Bharti Public School"]

rank = ["an average",
          "an excellent",
            "a poor"]

career_on = ["25 December 1977",
                "19 November 1989"]

debut = ["17 November 1990",
            "11 February 1992",
               "14 February 1995"]

records = ["eight 200s,sixty two 100s and hundred and ninety 50s",
                "seven 200s,fifty 100s and eighty five 50s"]

awards = ["Padma Bhushan",
            "Padma Shri",
               "Khel Ratna",
                  "Arjuna Award",
                    "Bharat Rward",
                      "Dronacharya Award"]

quality =["playing technique",
            "captaincy"]

print(random.choice(when_on)+" on "+random.choice(date)+" at "+random.choice(where)+", "+random.choice(who)+", a "+random.choice(proffesion)+
       " player "+random.choice(what)+" against "+random.choice(opposition)+" and stood as "+random.choice(honour)+" and "+
          random.choice(result)+"Till today he is the best captain in "+random.choice(captain)+". He belongs to "+ random.choice(community)+" of "+
            random.choice(native)+", born to "+ random.choice(parents)+". He done his schooling in "+random.choice(studies)+" and was "+random.choice(rank)+
             " student in school. He started his career on "+random.choice(career_on)+", made his debut on "+random.choice(debut)+". Till today he won many awards in his field. Some of them are "+
               random.choice(awards)+", "+random.choice(awards)+" etc... He is an inspiration for many young players of today. Not only in India, many people from all over the world love him for his "+random.choice(quality)+".")
