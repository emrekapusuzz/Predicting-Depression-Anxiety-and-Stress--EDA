
# Predicting Depression, Anxiety and Stress- EDA

![alt text](https://www-assets.perkbox.com/media/7058/i960/22a5cdad3b473bc9ff2a.jpg)




## About

The data is from: https://openpsychometrics.org/tests/TMAS/

Depression, Anxiety and Stress; three horse-man of pschological disorders of our era. They effect how we live, how we work and other aspects of our daily lives. Many studies proved the negative effects of these three; however we are still not sure about how we got these disorders, what drives us to get the DAS. There are more studies and analysis needed to discuss and make assumptions about that.

One of the studies conducted to determine the reasons / drivers of DAS is the Taylor study, and the data is available at Kagge and openpsychometrics web page.

Let's have a look at the data information:

This data was collected with an on-line version of the Depression Anxiety Stress
Scales (DASS), see http://www2.psy.unsw.edu.au/dass/

The survey was open to anyone and people were motivated to take it to get 
personalized results. At the end of the test they also were given the option to 
complete a short research survey. 
This datatset comes from those who agreed to complete the research survey and answered 
yes to the question "Have you given accurate answers and may they be used for research?" 
at the end.

This data was collected 2017 - 2019.

Each item was presented one at a time in a random order for each new participant 
along with a 4 point rating scale asking the user to indicate how often that had 
been true of them in the past week.

This response is stored in variable A (e.g. Q1A). 
Also recorded was the time taken in milliseconds to answer that question (E)
and that question's position in the survey (I).

These other durations were also recorded (measured on the server's side):

* introelapse        The time spent on the introduction/landing page (in seconds)
* testelapse        The time spent on all the DASS questions (should be equivalent to the time elapsed on all the indiviudal questions combined)
* surveyelapse    The time spent answering the rest of the demographic and survey questions

On the next page was a generic demographics survey with many different questions.

The Ten Item Personality Inventory was administered 
(see Gosling, S. D., Rentfrow, P. J., & Swann, W. B., Jr. (2003). 
A Very Brief Measure of the Big Five Personality Domains. Journal of Research in Personality, 37, 504-528.):

* TIPI1    Extraverted, enthusiastic.
* TIPI2    Critical, quarrelsome.
* TIPI3    Dependable, self-disciplined.
* TIPI4    Anxious, easily upset.
* TIPI5    Open to new experiences, complex.
* TIPI6    Reserved, quiet.
* TIPI7    Sympathetic, warm.
* TIPI8    Disorganized, careless.
* TIPI9    Calm, emotionally stable.
* TIPI10    Conventional, uncreative.

The TIPI items were rated "I see myself as:" _____ such that

* 1 = Disagree strongly
* 2 = Disagree moderately
* 3 = Disagree a little
* 4 = Neither agree nor disagree
* 5 = Agree a little
* 6 = Agree moderately
* 7 = Agree strongly

TIPI scale scoring (‘‘R’’ denotes reverse-scored items): Extraversion: 1, 6R; Agreeableness: 2R, 7;
Conscientiousness; 3, 8R; Emotional Stability: 4R, 9; Openness to Experiences: 5, 10R

The following items were presented as a check-list and subjects were instructed "In the grid below, check all the words whose definitions you are sure you know":

* VCL1    boat
* VCL2    incoherent
* VCL3    pallid
* VCL4    robot
* VCL5    audible
* VCL6    cuivocal
* VCL7    paucity
* VCL8    epistemology
* VCL9    florted
* VCL10    decide
* VCL11    pastiche
* VCL12    verdid
* VCL13    abysmal
* VCL14    lucid
* VCL15    betray
* VCL16    funny

A value of 1 is checked, 0 means unchecked. The words at VCL6, VCL9, and VCL12
are not real words and can be used as a validity check.

A bunch more questions were then asked:


* education:    "How much education have you completed?", 1=Less than high school, 2=High school, 3=University degree, 4=Graduate degree
* urban:        "What type of area did you live when you were a child?", 1=Rural  (country side), 2=Suburban, 3=Urban (town, city)
* gender:      "What is your gender?", 1=Male, 2=Female, 3=Other
* engnat:       "Is English your native language?", 1=Yes, 2=No
* age:          "How many years old are you?"
* hand:         "What hand do you use to write with?", 1=Right, 2=Left, 3=Both
* religion:     "What is your religion?", 1=Agnostic, 2=Atheist, 3=Buddhist, 4=Christian (Catholic), 5=Christian (Mormon), 6=Christian (Protestant),  7=Christian (Other), 8=Hindu, 9=Jewish, 10=Muslim, 11=Sikh, 12=Other
* orientation:  "What is your sexual orientation?", 1=Heterosexual, 2=Bisexual, 3=Homosexual, 4=Asexual, 5=Other
* race:        "What is your race?", 10=Asian, 20=Arab, 30=Black, 40=Indigenous Australian, 50=Native American, 60=White, 70=Other
* voted:       "Have you voted in a national election in the past year?", 1=Yes, 2=No
* married:     "What is your marital status?", 1=Never married, 2=Currently married, 3=Previously married
* familysize:  "Including you, how many children did  your mother have?"        
* major:       "If you attended a university, what was your major (e.g. "psychology",  "English", "civil engineering")?"

The following values were derived from technical information:

* country:      ISO country code of where the user connected from
* screensize: 1=device with small screen (phone, etc), 2=device with big screen (laptop, desktop, etc)
* uniquenetworklocation: 1=only one survey from user's specific network in dataset, 2=multiple surveys submitted from the network of this user (2 does not necessarily imply duplicate records for an individual, as it could be different students at a single school or different memebers of the same household and even if 1 there still could be duplicate records from a single individual e.g. if they took it once  on their wifi and once on their phone)
* source: How the user found the test, 1=from the front page of the site hosting
the survey, 2=from google, 0=other or unknown


## Methods Used

* Data Cleaning
* Explotory Data Analysis
* Feature Engineering
* Data Visualization



  
## Author

- [@orkunaran](https://github.com/orkunaran)
- [@emrekapusuzz](https://github.com/emrekapusuzz)

  
