# TECH EVENTS KENYA

I Intend to accomplish in Next/React, below is a pseudo design.  

# problem: 
- time(start of activity, end activity are not well coordinated, **NB**: this is mostly failure to plan or failed plans for trivial tasks like snack time and misc. like photo sessions), 
- people(management e.g queing priority if any, profiles i.e know who's in attendance and what they do and start a convo if your goals are aligned), 
- communication(attendee to organizers; organizer to organizer; organizer to speakers; organizer to attendees)
## baseline is that a real world event is non-deterministic and infinite which can not always be accounted for empirically.
# limitations
- events depend majorly in the human part, its coordination and everything is dependent on the community and the organizers
- this is not a social networking site, or at least doesn't seek to be, some comm. like banter and feedback would make sense to live on Twitter.

# Scope def: the features that the end product will ressemble, Attributes to measure progress/perfomance:
-  M Must have: 
-  S Should have: iCal, vCard, map, pub/sub
-  C Could have: mini-budget, Q&A, live/playback, mealplan, general chat(plus private one for organizers), suggest events
-  W Won't have:

# casestudy and background,
- Python KE event has two sites 1.https://www.pyconke.org/ 2.https://www.pycon.or.ke/, uses [sessionize] https://sessionize.com for the breakouts. No subchapters or anything e.g django, DS/ML, micropython, etc. 
- droidcon 1.https://www.droidcon.com/events/ 2.https://droidcon.co.ke/
- 
# Conclusion  a tech would be that an Event is created/promoted by either the language/tech itself or an organization using the underlying tech eg Android Kotlin, AI/ML python
take the following format:
1. one time e.g developer roadshow, themed hackathon
2. known/scheduled eg weekly, monthly, annually  
- events ride a lot on twitter to share trivial event info like photos and stuff

# Tix' and RSVP
 I'm yet to experience being thrown out for not having a ticket/RSVP'd but a ticket is, in a tech event, to serve this purposes:
  i. serving snacks/meals
  ii. giving out merch, mostly tee's **NB**: *merch/swaag is not always free, some are paid*

# DataStructure(s) pseudocode
- EVENT{
  TYPES{
   HACKATHONS[],
   FESTS[], 
   CONF[],
  } 
  <!-- -->
  COMMUNITIES, 
  VENUE{location, }
  ATTENDEES{profile, }
  SPONSORS[]
  ORGANIZERS[]
  AGGREGATOR_PLATFORMS {eventbrite, meetup, gdgdev}
  THEME/TOPIC
}
- TIME{
DURATION
BREAKOUTS/MINI-EVENTS 
OTHER PLANNED ACTIVITY kahoot icebreakers
SPEAKERS/FACILITATORS
TIX rarely used, eventbrite,
PROVIDERS
VALIDATORS/VOLUNTEERS
USES
}

# architecture/design
architecture SOA EOA
design DDD
I AM NOT IN THE BUSINESS OF COMING UP WITH MY OWN ARCHITECTURAL PATTERN HA! BUT GENERALLY THIS IS MY IDEA OF THE DATAFLOW.

***to be continued, have to rush to class ***

**NB** Considering to use a domain specific pattern for the time and datetime data structures
'''
info.>action every piece of info on the platform should lead to an action(achieved through user input event eg click, touch)
'''
action is mapped to a return value(an `event`(a computational event) is a function)


Built by [Wayne Gakuo](https://waynegakuo.netlify.app/) for [GDG DevFest Kenya](https://twitter.com/devfestkenya).
Fork and mod by Tim.  
