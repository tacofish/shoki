Israel Keyes POC for tracking, profiling, apprehension..using data analytics, scoring, and some AI to make smart decisions
- 2001-2012
Location Profile:
- Remote
- Far enough to not hear gunshots.
-- Gun was a last resort, as indicated with unrecovered, but known, victims.
- Did not operate close to home until last crime.
- Often traveled to one airport via plane, then rented a car and drove hundreds to a thousand miles to crime
- For WA, one lake used is Crescent Lake.
- One area used for disposal is near a valley in WA. 
- Encountered someone on road between Port Orchard and Neah Bay.
-- locate and speak to possible encounter individual.
--- find others tracking this. gather results as of today.
- Kidnapped then moved victims.
-- In one case, the couple moved to abandoned barn and killed. Never found as construction over barn.
- Indicated that ONE other body found, but deemed accidental death. Unknown vicinity or timeline.


Finding the radius, what I need:
- Rental car mileage records for each vehicle rented.
-- Provides the radius for operation.
- Where the rental car was rented from (airport, or a satellite location)
- Dates of arrival and departure.
-- Same airports? Or different?
- Locations of major national parks, nature preserves, etc...
- Missing persons in the area.
-- Couple with where they were last seen, and where they were going, if known.
-- Eliminate based on location profile and known knowns about the missing person.
- Profile the locations themselves. What are the traits of each locale?
-- Population
-- Tourism information
-- Proximity to cities.
-- Bank robberies (solved or not pointing towards keyes) and proximity to missing persons and potential operation radiuses. 
--- Join this data back to location profiling, and we may be able to categorically score something as high on the list. 
--- Bank robberies means he's been there. Expect same MO as other crimes, as this would be the best way to stay anonymous, and he was meticulous.
- Known spots:
-- One cache in remote location in NYS. Need coordinates.
--- This will be evaluated against missing persons and travel dates.
-- All travel dates and destination airports is known.
-- Rental car info is probably buried somewhere. Need to add to FOIA request.
- Look for the car type they were driving.
- Any security footage? If so, can this be ran through image recognition software to try to determine if this was indeed the vehicle. Can we sift for the license plates?
-- Used cash, but this was mostly from bank robberies.
- Using contents of the known caches, can items be bought from a single location? If so, do we have purchases matching that? Very likely not tracked or stored at this point, the data would be rotated out and lost.
- Finding caches may be a good way to figure out what was going on and methods for each area, if they remained consistent.
- Lake Crescent
-- New technology is being developed for deep sea exploration every day, can some of this be purposed for searching the bottom of the lake for remains?
--- Will anyone incur that kind of cost to figure this out? How important is it to solve this? Would it give a better glimpse into the secret side of the perp?


TECHNICAL 
- Need to find a way to pull all maps data for a radius, then cross-ref against census and tourism bureau data (where available). 
- Is a paid transit to augment mileage from the rental a potential avenue that needs to be explored? If so, what information is likely available via regulatory requirements? Any? Find out. If so, normalize and NLP for categorization and scoring.
- Tunable category scoring weights for analytics post-occurrence and once something is identified as related. (
  [
    {location: [
      {enabled: 'true'}, 
      {population: 'remote', weight: '.8'}
      ]
    }, 
    {victimology: [
      {enabled: 'false'}
      ]
    }
      
Something like that. Helps to generalize out. How to add new category? Figure out.
- Plug into murderdata.org for data on missing persons in a comprehensive way. This does not focus on the names, but characteristics, which is all I'm interested in. This is the most complete resource available today.
- Sub an ingest endpoint to event feeds about news and blotters. It's there, I just forgot the name
- Evaluate NLP engines, and the SaaS products available today to get this done quickly.
-- Understand configuration of those systems.
- Look for prior art that can be leveraged to evaluate location against criteria given. Think travel software libraries, etc... (travel agents do this every day, I think?)
- Determine the scoring system, and look for ways to have the system auto-correct when new information comes up. Auto-adjust scoring based on new information/crimes/victims/evolution of methods.
- DO NOT GET INVOLVED IN CASE DETAILS
- Find a way to codify the traits of a scene examined to the accepted psychological, sociological, or behavioral characteristics of the offender.
- Understand that this can be used for anyone and should be kicked off as soon as a serial offender is detected, which should give the system enough data to understand the basic profile and weights to be used. ML is going to be critical there.

-----
Location profile
- Evaluate feed coming in from the u.s. initially (I can't interpret foreign languages from their news feeds) (translation libraries may be evaluated later, but that may be of limited use if context doesn't preserve well across languages). If key words are all we need, that may be better than nothing.
-- Look at crimes, missing persons reports, news stories about incidents, and potentially gang related activity.
--- Safety index scoring
-- Look at case clearance rates
- Get this shoved into a nice K8S drop in package.
--- Prove that technology and automation can ease the burden on even professions that aren't typically associated with it. 
--- Prove that by doing things in this manner, we can provide cost and time savings while HOPEFULLY improving travel safety and satisfaction with travel arrangements.

-----
Reporting
- Evaluate data obtained against movements of suspect in custody. 
- Eliminate potential victims based on movements, characteristics learned during interview, and rescore.
- Determine how this data can be evaluated, reported, used to categorize and build a profile.
-- What is important in the report?
--- What do they need to ellicit in the interviews to be able to understand what is and isn't fact, and what actually maps back to needs/wants?
- Can voice processing be used to evaluate vocal cues in speech patterns to determine likely truths vs. uncertainty. Detect:
-- Pause
-- Calm
-- Surprise
-- Backpeddling
-- Defensiveness
-- Change in demeanor
-- Use to detect: 
--- Tone
--- Vocabulary used -- could be important if they shift speech patterns
--- Changes in inflection
--- Changes in volume
--- Changes in diction
--- Look for anything that doesn't fit the benchmark mold laid out through initial discussions.
---- Want a control without them realizing it. Talk about their likes and just BS for a few while the system is analyzing.
---- Briefly touch a subject that would ellicit a stress response. Money and cost (budget) is a great way to do this
---- Once the speech pattern is changed, the response has been ellicited. 
-- Report on likely areas of truth/fact and likely areas of uncertainty.
- Voice processing can be used to document data for further analysis:
-- Speech.
-- Verbage used.
-- Shifts in speaking patterns, and what spurned that.
-- Determine likely emotional state from these tells.
--- Psychologist would likely be a great resource to talk to about this. Or potentially former intelligence officers that know how to determine thought, from truths, from lies. Perhaps poker players, as well. How do they identify tells? Can this be analyzed from footage and/or speech patterns?
