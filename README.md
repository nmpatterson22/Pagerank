## *Pagerank*
# This is an iteration of Pagerank utilized in Deeper Inside Pagerank 

## Task 1
montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --verbose
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=8.4183e+00 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=1 pagerank=8.4183e+00 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=8.4183e+00 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=3 pagerank=8.4183e+00 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=8.4183e+00 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=8.4183e+00 url=www.lawfareblog.com/masthead
INFO:root:rank=6 pagerank=8.4183e+00 url=www.lawfareblog.com/topics
INFO:root:rank=7 pagerank=8.4183e+00 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=8.4183e+00 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=8.4183e+00 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site

# Utilizing a verbose flag this is ranking URL's 

## Part 2
#This function utilizes the same power method to read in URL's as string as a parameter
(base) montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --search_query='corona'
INFO:root:rank=0 pagerank=4.5861e-03 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=1 pagerank=4.0460e-03 url=www.lawfareblog.com/house-oversight-committee-holds-day-two-hearing-government-coronavirus-response
INFO:root:rank=2 pagerank=2.6116e-03 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=3 pagerank=2.5390e-03 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=4 pagerank=2.3557e-03 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
INFO:root:rank=5 pagerank=2.2895e-03 url=www.lawfareblog.com/why-congress-conducting-business-usual-face-coronavirus
INFO:root:rank=6 pagerank=2.2727e-03 url=www.lawfareblog.com/livestream-house-oversight-committee-holds-hearing-government-coronavirus-response
INFO:root:rank=7 pagerank=2.2520e-03 url=www.lawfareblog.com/congressional-homeland-security-committees-seek-ways-support-state-federal-responses-coronavirus
INFO:root:rank=8 pagerank=2.1878e-03 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
INFO:root:rank=9 pagerank=2.0339e-03 url=www.lawfareblog.com/cyberlaw-podcast-how-israel-fighting-coronavirus

# Search Query Cyber 
INFO:root:rank=0 pagerank=6.1218e-02 url=www.lawfareblog.com/cyberlaw-podcast-mistrusting-google
INFO:root:rank=1 pagerank=5.8917e-02 url=www.lawfareblog.com/cyberlaw-podcast-sandworm-and-grus-global-intifada
INFO:root:rank=2 pagerank=5.8745e-02 url=www.lawfareblog.com/cyberlaw-podcast-plumbing-depths-artificial-stupidity
INFO:root:rank=3 pagerank=1.7709e-02 url=www.lawfareblog.com/cyber-command-operational-update-clarifying-june-2019-iran-operation
INFO:root:rank=4 pagerank=1.3321e-02 url=www.lawfareblog.com/indias-role-global-cyber-policy-formulation
INFO:root:rank=5 pagerank=1.3254e-02 url=www.lawfareblog.com/cyberlaw-podcast-bytedance-bitten-cfius
INFO:root:rank=6 pagerank=1.0685e-02 url=www.lawfareblog.com/self-help-cyberspace-path-forward
INFO:root:rank=7 pagerank=1.0464e-02 url=www.lawfareblog.com/cyberlaw-podcast-rebel-scum-alliance
INFO:root:rank=8 pagerank=1.0223e-02 url=www.lawfareblog.com/getting-drop-cyberspace
INFO:root:rank=9 pagerank=9.9394e-03 url=www.lawfareblog.com/achieving-and-maintaining-cyberspace-superiority-cyber-command-and-interagency-legal-conference

## List Largest Pagerank.
#montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz                     
INFO:root:rank=0 pagerank=8.4183e+00 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=1 pagerank=8.4183e+00 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=8.4183e+00 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=3 pagerank=8.4183e+00 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=8.4183e+00 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=8.4183e+00 url=www.lawfareblog.com/masthead
INFO:root:rank=6 pagerank=8.4183e+00 url=www.lawfareblog.com/topics
INFO:root:rank=7 pagerank=8.4183e+00 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=8.4183e+00 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=8.4183e+00 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site

# Part 3
#Utilizing search ratio filter 
INFO:root:rank=0 pagerank=4.2773e+00 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=1 pagerank=2.7717e+00 url=www.lawfareblog.com/livestream-nov-21-impeachment-hearings-0
INFO:root:rank=2 pagerank=2.7533e+00 url=www.lawfareblog.com/opening-statement-david-holmes
INFO:root:rank=3 pagerank=1.8720e+00 url=www.lawfareblog.com/senate-examines-threats-homeland
INFO:root:rank=4 pagerank=1.7417e+00 url=www.lawfareblog.com/what-make-first-day-impeachment-hearings
INFO:root:rank=5 pagerank=1.7411e+00 url=www.lawfareblog.com/livestream-house-armed-services-committee-hearing-f-35-program
INFO:root:rank=6 pagerank=1.7347e+00 url=www.lawfareblog.com/whats-house-resolution-impeachment
INFO:root:rank=7 pagerank=1.6384e+00 url=www.lawfareblog.com/congress-us-policy-toward-syria-and-turkey-overview-recent-hearings
INFO:root:rank=8 pagerank=1.5597e+00 url=www.lawfareblog.com/summary-david-holmess-deposition-testimony
INFO:root:rank=9 pagerank=9.1265e-01 url=www.lawfareblog.com/events

# Utilizing verbose + filter ratio 
 montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --verbose --filter_ratio=0.2

DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=4.2773e+00 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=1 pagerank=2.7717e+00 url=www.lawfareblog.com/livestream-nov-21-impeachment-hearings-0
INFO:root:rank=2 pagerank=2.7533e+00 url=www.lawfareblog.com/opening-statement-david-holmes
INFO:root:rank=3 pagerank=1.8720e+00 url=www.lawfareblog.com/senate-examines-threats-homeland
INFO:root:rank=4 pagerank=1.7417e+00 url=www.lawfareblog.com/what-make-first-day-impeachment-hearings
INFO:root:rank=5 pagerank=1.7411e+00 url=www.lawfareblog.com/livestream-house-armed-services-committee-hearing-f-35-program
INFO:root:rank=6 pagerank=1.7347e+00 url=www.lawfareblog.com/whats-house-resolution-impeachment
INFO:root:rank=7 pagerank=1.6384e+00 url=www.lawfareblog.com/congress-us-policy-toward-syria-and-turkey-overview-recent-hearings
INFO:root:rank=8 pagerank=1.5597e+00 url=www.lawfareblog.com/summary-david-holmess-deposition-testimony
INFO:root:rank=9 pagerank=9.1265e-01 url=www.lawfareblog.com/events

----
##Part 4 
#Utilizing Task 4 montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --verbose --alpha=0.9999    
#Alpha is acting as a convergence filter
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=1.0190e+01 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=1 pagerank=1.0190e+01 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=1.0190e+01 url=www.lawfareblog.com/masthead
INFO:root:rank=3 pagerank=1.0190e+01 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=1.0190e+01 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=1.0190e+01 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=6 pagerank=1.0190e+01 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site
INFO:root:rank=7 pagerank=1.0190e+01 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=1.0190e+01 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=1.0190e+01 url=www.lawfareblog.com/topics

----
montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --verbose --filter_ratio=0.2 --alpha=0.9999
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=4.7568e+01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=1 pagerank=4.7568e+01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=2 pagerank=7.2060e+00 url=www.lawfareblog.com/cost-using-zero-days
INFO:root:rank=3 pagerank=2.1524e+00 url=www.lawfareblog.com/lawfare-podcast-former-congressman-brian-baird-and-daniel-schuman-how-congress-can-continue-function
INFO:root:rank=4 pagerank=1.4226e+00 url=www.lawfareblog.com/events
INFO:root:rank=5 pagerank=1.0793e+00 url=www.lawfareblog.com/water-wars-increased-us-focus-indo-pacific
INFO:root:rank=6 pagerank=1.0793e+00 url=www.lawfareblog.com/water-wars-drill-maybe-drill
INFO:root:rank=7 pagerank=1.0792e+00 url=www.lawfareblog.com/water-wars-disjointed-operations-south-china-sea
INFO:root:rank=8 pagerank=1.0792e+00 url=www.lawfareblog.com/water-wars-song-oil-and-fire
INFO:root:rank=9 pagerank=1.0792e+00 url=www.lawfareblog.com/water-wars-sinking-feeling-philippine-china-relations

------
##TASK 2 Personalization Vector 
#The Personalization Vector Methodmontypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --personalization_vector_query='iran'     
INFO:root:rank=0 pagerank=1.0370e+00 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=1 pagerank=1.0370e+00 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=2 pagerank=1.0370e+00 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=3 pagerank=1.0370e+00 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=4 pagerank=1.0370e+00 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=5 pagerank=1.0370e+00 url=www.lawfareblog.com/support-lawfare
INFO:root:rank=6 pagerank=1.0370e+00 url=www.lawfareblog.com/snowden-revelations
INFO:root:rank=7 pagerank=1.0370e+00 url=www.lawfareblog.com/masthead
INFO:root:rank=8 pagerank=1.0370e+00 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=9 pagerank=1.0370e+00 url=www.lawfareblog.com/documents-related-mueller-investigation
#Personalization Vector string was 'Iran"


# Part 2
# Searches terms using both personalization vector + search term, meaning that it only displays webpages with corona importance but not those that mention corona
montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --personalization_vector_query='corona' --search_query='corona'
INFO:root:rank=0 pagerank=3.4561e-02 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=1 pagerank=3.4561e-02 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=2 pagerank=3.1105e-02 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=3 pagerank=2.9424e-02 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
INFO:root:rank=4 pagerank=2.8572e-02 url=www.lawfareblog.com/china-responds-coronavirus-iron-grip-information-flow
INFO:root:rank=5 pagerank=2.8409e-02 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
INFO:root:rank=6 pagerank=2.8053e-02 url=www.lawfareblog.com/congressional-homeland-security-committees-seek-ways-support-state-federal-responses-coronavirus
INFO:root:rank=7 pagerank=2.7263e-02 url=www.lawfareblog.com/trump-right-britain-handling-coronavirus-well
INFO:root:rank=8 pagerank=2.7263e-02 url=www.lawfareblog.com/house-oversight-committee-questions-government-response-coronavirus
INFO:root:rank=9 pagerank=2.7174e-02 url=www.lawfareblog.com/lessons-america-how-south-korean-authorities-used-law-fight-coronavirus

 
## Experimentation with search term iran
montypatterson@Montys-MacBook-Pro-2 ~ % python /Users/montypatterson/Desktop/working_pagerank.py --data=/Users/montypatterson/Desktop/lawfareblog\ \(1\).csv.gz --personalization_vector_query='iran' --search_query='iran'   
INFO:root:rank=0 pagerank=5.7547e-02 url=www.lawfareblog.com/cyber-command-operational-update-clarifying-june-2019-iran-operation
INFO:root:rank=1 pagerank=5.5730e-02 url=www.lawfareblog.com/aborted-iran-strike-fine-line-between-necessity-and-revenge
INFO:root:rank=2 pagerank=5.4704e-02 url=www.lawfareblog.com/iranian-hostage-crisis-and-its-effect-american-politics
INFO:root:rank=3 pagerank=5.4704e-02 url=www.lawfareblog.com/announcing-united-states-and-use-force-against-iran-new-lawfare-e-book
INFO:root:rank=4 pagerank=5.4251e-02 url=www.lawfareblog.com/parsing-state-departments-letter-use-force-against-iran
INFO:root:rank=5 pagerank=4.1902e-02 url=www.lawfareblog.com/how-us-iran-tensions-could-disrupt-iraqs-fragile-peace
INFO:root:rank=6 pagerank=2.0823e-02 url=www.lawfareblog.com/legal-context-cybercoms-reported-operations-against-iran
INFO:root:rank=7 pagerank=1.7879e-02 url=www.lawfareblog.com/trump-moves-cut-irans-oil-revenues-whats-his-endgame
INFO:root:rank=8 pagerank=1.6109e-02 url=www.lawfareblog.com/us-names-iranian-revolutionary-guard-terrorist-organization-and-sanctions-international-criminal
INFO:root:rank=9 pagerank=1.4591e-02 url=www.lawfareblog.com/praise-presidents-iran-tweets


