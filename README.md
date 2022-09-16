# Pagerank Project
   
   Task 1, part 1:
   ```
   $ python3 pagerank.py --data=data/small.csv.gz --verbose
   DEBUG:root:computing indices
   DEBUG:root:computing values
   DEBUG:root:i=0 residual=0.3775096535682678
   DEBUG:root:i=1 residual=0.3134882152080536
   DEBUG:root:i=2 residual=0.2756592035293579
   DEBUG:root:i=3 residual=0.21698090434074402
   DEBUG:root:i=4 residual=0.18984204530715942
   DEBUG:root:i=5 residual=0.15531454980373383
   DEBUG:root:i=6 residual=0.13266263902187347
   DEBUG:root:i=7 residual=0.11062280833721161
   DEBUG:root:i=8 residual=0.0935136154294014
   DEBUG:root:i=9 residual=0.07847193628549576
   DEBUG:root:i=10 residual=0.06611069291830063
   DEBUG:root:i=11 residual=0.05558090656995773
   DEBUG:root:i=12 residual=0.04677915573120117
   DEBUG:root:i=13 residual=0.039349012076854706
   DEBUG:root:i=14 residual=0.03310869261622429
   DEBUG:root:i=15 residual=0.027853948995471
   DEBUG:root:i=16 residual=0.023434894159436226
   DEBUG:root:i=17 residual=0.019716130569577217
   DEBUG:root:i=18 residual=0.016587838530540466
   DEBUG:root:i=19 residual=0.013955758884549141
   DEBUG:root:i=20 residual=0.011741633526980877
   DEBUG:root:i=21 residual=0.009878222830593586
   DEBUG:root:i=22 residual=0.008310933597385883
   DEBUG:root:i=23 residual=0.006992380600422621
   DEBUG:root:i=24 residual=0.00588278379291296
   DEBUG:root:i=25 residual=0.00494928564876318
   DEBUG:root:i=26 residual=0.004164101090282202
   DEBUG:root:i=27 residual=0.003503275103867054
   DEBUG:root:i=28 residual=0.002947412896901369
   DEBUG:root:i=29 residual=0.0024798011872917414
   DEBUG:root:i=30 residual=0.002086422871798277
   DEBUG:root:i=31 residual=0.0017551911296322942
   DEBUG:root:i=32 residual=0.0014767624670639634
   DEBUG:root:i=33 residual=0.0012423915322870016
   DEBUG:root:i=34 residual=0.0010452595306560397
   DEBUG:root:i=35 residual=0.0008794325985945761
   DEBUG:root:i=36 residual=0.0007398635498248041
   DEBUG:root:i=37 residual=0.0006225021206773818
   DEBUG:root:i=38 residual=0.0005237152217887342
   DEBUG:root:i=39 residual=0.00044049162534065545
   DEBUG:root:i=40 residual=0.0003707956930156797
   DEBUG:root:i=41 residual=0.0003118595341220498
   DEBUG:root:i=42 residual=0.00026235461700707674
   DEBUG:root:i=43 residual=0.0002207769575761631
   DEBUG:root:i=44 residual=0.00018579662719275802
   DEBUG:root:i=45 residual=0.0001563065015943721
   DEBUG:root:i=46 residual=0.0001315098925260827
   DEBUG:root:i=47 residual=0.00011065506259910762
   DEBUG:root:i=48 residual=9.283208783017471e-05
   DEBUG:root:i=49 residual=7.835238648112863e-05
   DEBUG:root:i=50 residual=6.579793989658356e-05
   DEBUG:root:i=51 residual=5.543866427615285e-05
   DEBUG:root:i=52 residual=4.6715060307178646e-05
   DEBUG:root:i=53 residual=3.909929364454001e-05
   DEBUG:root:i=54 residual=3.294386260677129e-05
   DEBUG:root:i=55 residual=2.7852673156303354e-05
   DEBUG:root:i=56 residual=2.3248065190273337e-05
   DEBUG:root:i=57 residual=1.966203490155749e-05
   DEBUG:root:i=58 residual=1.6471843991894275e-05
   DEBUG:root:i=59 residual=1.4014856787980534e-05
   DEBUG:root:i=60 residual=1.1800590982602444e-05
   DEBUG:root:i=61 residual=9.742259862832725e-06
   DEBUG:root:i=62 residual=8.302875357912853e-06
   DEBUG:root:i=63 residual=7.063716111588292e-06
   DEBUG:root:i=64 residual=5.845966825290816e-06
   DEBUG:root:i=65 residual=4.962869752489496e-06
   DEBUG:root:i=66 residual=4.206880475976504e-06
   DEBUG:root:i=67 residual=3.499711510812631e-06
   DEBUG:root:i=68 residual=2.992129338963423e-06
   DEBUG:root:i=69 residual=2.5033950805664062e-06
   DEBUG:root:i=70 residual=2.214214191553765e-06
   DEBUG:root:i=71 residual=1.955177822310361e-06
   DEBUG:root:i=72 residual=1.3902072169003077e-06
   DEBUG:root:i=73 residual=1.244581540049694e-06
   DEBUG:root:i=74 residual=9.97376446321141e-07
   INFO:root:rank=0 pagerank=2.1634e+00 url=4
   INFO:root:rank=1 pagerank=1.6664e+00 url=6
   INFO:root:rank=2 pagerank=1.2402e+00 url=5
   INFO:root:rank=3 pagerank=4.5712e-01 url=2
   INFO:root:rank=4 pagerank=3.5620e-01 url=3
   INFO:root:rank=5 pagerank=3.2078e-01 url=1
   ```

   Task 1, part 2:
   ```
   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='corona'
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
   
   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='trump'
   INFO:root:rank=0 pagerank=6.6243e-02 url=www.lawfareblog.com/donald-trump-and-politically-weaponized-executive-branch
   INFO:root:rank=1 pagerank=6.0194e-02 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
   INFO:root:rank=2 pagerank=3.4969e-02 url=www.lawfareblog.com/trump-administrations-worrying-new-policy-israeli-settlements
   INFO:root:rank=3 pagerank=3.2193e-02 url=www.lawfareblog.com/document-trump-revokes-obama-executive-order-counterterrorism-strike-casualty-reporting
   INFO:root:rank=4 pagerank=3.0971e-02 url=www.lawfareblog.com/dc-circuit-overrules-district-courts-due-process-ruling-qasim-v-trump
   INFO:root:rank=5 pagerank=2.8460e-02 url=www.lawfareblog.com/how-trumps-approach-middle-east-ignores-past-future-and-human-condition
   INFO:root:rank=6 pagerank=2.5252e-02 url=www.lawfareblog.com/why-trump-cant-buy-greenland
   INFO:root:rank=7 pagerank=2.2457e-02 url=www.lawfareblog.com/oral-argument-summary-qassim-v-trump
   INFO:root:rank=8 pagerank=2.1462e-02 url=www.lawfareblog.com/dc-circuit-court-denies-trump-rehearing-mazars-case
   INFO:root:rank=9 pagerank=2.1103e-02 url=www.lawfareblog.com/second-circuit-rules-mazars-must-hand-over-trump-tax-returns-new-york-prosecutors

   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='iran'
   INFO:root:rank=0 pagerank=6.6131e-02 url=www.lawfareblog.com/praise-presidents-iran-tweets
   INFO:root:rank=1 pagerank=2.9199e-02 url=www.lawfareblog.com/how-us-iran-tensions-could-disrupt-iraqs-fragile-peace
   INFO:root:rank=2 pagerank=1.7709e-02 url=www.lawfareblog.com/cyber-command-operational-update-clarifying-june-2019-iran-operation
   INFO:root:rank=3 pagerank=1.4604e-02 url=www.lawfareblog.com/aborted-iran-strike-fine-line-between-necessity-and-revenge
   INFO:root:rank=4 pagerank=8.4512e-03 url=www.lawfareblog.com/iranian-hostage-crisis-and-its-effect-american-politics
   INFO:root:rank=5 pagerank=8.3989e-03 url=www.lawfareblog.com/parsing-state-departments-letter-use-force-against-iran
   INFO:root:rank=6 pagerank=8.2581e-03 url=www.lawfareblog.com/announcing-united-states-and-use-force-against-iran-new-lawfare-e-book
   INFO:root:rank=7 pagerank=8.0561e-03 url=www.lawfareblog.com/trump-moves-cut-irans-oil-revenues-whats-his-endgame
   INFO:root:rank=8 pagerank=7.1939e-03 url=www.lawfareblog.com/us-names-iranian-revolutionary-guard-terrorist-organization-and-sanctions-international-criminal
   INFO:root:rank=9 pagerank=5.9405e-03 url=www.lawfareblog.com/iran-shoots-down-us-drone-domestic-and-international-legal-implications
   ```

   Task 1, part 3:
   ```
   $ python3 pagerank.py --data=data/lawfareblog.csv.gz
   INFO:root:rank=0 pagerank=8.4156e+00 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
   INFO:root:rank=1 pagerank=8.4156e+00 url=www.lawfareblog.com/lawfare-job-board
   INFO:root:rank=2 pagerank=8.4156e+00 url=www.lawfareblog.com/documents-related-mueller-investigation
   INFO:root:rank=3 pagerank=8.4156e+00 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
   INFO:root:rank=4 pagerank=8.4156e+00 url=www.lawfareblog.com/subscribe-lawfare
   INFO:root:rank=5 pagerank=8.4156e+00 url=www.lawfareblog.com/masthead
   INFO:root:rank=6 pagerank=8.4156e+00 url=www.lawfareblog.com/topics
   INFO:root:rank=7 pagerank=8.4156e+00 url=www.lawfareblog.com/our-comments-policy
   INFO:root:rank=8 pagerank=8.4156e+00 url=www.lawfareblog.com/upcoming-events
   INFO:root:rank=9 pagerank=8.4156e+00 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site

   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2
   INFO:root:rank=0 pagerank=4.6091e+00 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
   INFO:root:rank=1 pagerank=2.9867e+00 url=www.lawfareblog.com/livestream-nov-21-impeachment-hearings-0
   INFO:root:rank=2 pagerank=2.9669e+00 url=www.lawfareblog.com/opening-statement-david-holmes
   INFO:root:rank=3 pagerank=2.0173e+00 url=www.lawfareblog.com/senate-examines-threats-homeland
   INFO:root:rank=4 pagerank=1.8769e+00 url=www.lawfareblog.com/what-make-first-day-impeachment-hearings
   INFO:root:rank=5 pagerank=1.8762e+00 url=www.lawfareblog.com/livestream-house-armed-services-committee-hearing-f-35-program
   INFO:root:rank=6 pagerank=1.8693e+00 url=www.lawfareblog.com/whats-house-resolution-impeachment
   INFO:root:rank=7 pagerank=1.7655e+00 url=www.lawfareblog.com/congress-us-policy-toward-syria-and-turkey-overview-recent-hearings
   INFO:root:rank=8 pagerank=1.6807e+00 url=www.lawfareblog.com/summary-david-holmess-deposition-testimony
   INFO:root:rank=9 pagerank=9.8346e-01 url=www.lawfareblog.com/events
   ```

   Task 1, part 4:
   ```{shell}
   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose 
   DEBUG:root:i=35 residual=6.144799158391834e-08
   INFO:root:rank=0 pagerank=8.4156e+00 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
   INFO:root:rank=1 pagerank=8.4156e+00 url=www.lawfareblog.com/lawfare-job-board
   INFO:root:rank=2 pagerank=8.4156e+00 url=www.lawfareblog.com/documents-related-mueller-investigation
   INFO:root:rank=3 pagerank=8.4156e+00 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
   INFO:root:rank=4 pagerank=8.4156e+00 url=www.lawfareblog.com/subscribe-lawfare
   INFO:root:rank=5 pagerank=8.4156e+00 url=www.lawfareblog.com/masthead
   INFO:root:rank=6 pagerank=8.4156e+00 url=www.lawfareblog.com/topics
   INFO:root:rank=7 pagerank=8.4156e+00 url=www.lawfareblog.com/our-comments-policy
   INFO:root:rank=8 pagerank=8.4156e+00 url=www.lawfareblog.com/upcoming-events
   INFO:root:rank=9 pagerank=8.4156e+00 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site

   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --alpha=0.99999
   DEBUG:root:i=999 residual=0.0003139339096378535
   INFO:root:rank=0 pagerank=1.0624e+01 url=www.lawfareblog.com/upcoming-events
   INFO:root:rank=1 pagerank=1.0624e+01 url=www.lawfareblog.com/lawfare-job-board
   INFO:root:rank=2 pagerank=1.0624e+01 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
   INFO:root:rank=3 pagerank=1.0624e+01 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
   INFO:root:rank=4 pagerank=1.0624e+01 url=www.lawfareblog.com/subscribe-lawfare
   INFO:root:rank=5 pagerank=1.0624e+01 url=www.lawfareblog.com/topics
   INFO:root:rank=6 pagerank=1.0624e+01 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site
   INFO:root:rank=7 pagerank=1.0624e+01 url=www.lawfareblog.com/our-comments-policy
   INFO:root:rank=8 pagerank=1.0624e+01 url=www.lawfareblog.com/documents-related-mueller-investigation
   INFO:root:rank=9 pagerank=1.0624e+01 url=www.lawfareblog.com/masthead

   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2
   DEBUG:root:i=78 residual=9.235662901119213e-07
   INFO:root:rank=0 pagerank=4.6091e+00 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
   INFO:root:rank=1 pagerank=2.9867e+00 url=www.lawfareblog.com/livestream-nov-21-impeachment-hearings-0
   INFO:root:rank=2 pagerank=2.9669e+00 url=www.lawfareblog.com/opening-statement-david-holmes
   INFO:root:rank=3 pagerank=2.0173e+00 url=www.lawfareblog.com/senate-examines-threats-homeland
   INFO:root:rank=4 pagerank=1.8769e+00 url=www.lawfareblog.com/what-make-first-day-impeachment-hearings
   INFO:root:rank=5 pagerank=1.8762e+00 url=www.lawfareblog.com/livestream-house-armed-services-committee-hearing-f-35-program
   INFO:root:rank=6 pagerank=1.8693e+00 url=www.lawfareblog.com/whats-house-resolution-impeachment
   INFO:root:rank=7 pagerank=1.7655e+00 url=www.lawfareblog.com/congress-us-policy-toward-syria-and-turkey-overview-recent-hearings
   INFO:root:rank=8 pagerank=1.6807e+00 url=www.lawfareblog.com/summary-david-holmess-deposition-testimony
   INFO:root:rank=9 pagerank=9.8346e-01 url=www.lawfareblog.com/events
   
   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2 --alpha=0.99999
   DEBUG:root:i=999 residual=2.813212813634891e-05
   INFO:root:rank=0 pagerank=5.2385e+01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
   INFO:root:rank=1 pagerank=5.2385e+01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
   INFO:root:rank=2 pagerank=7.9438e+00 url=www.lawfareblog.com/cost-using-zero-days
   INFO:root:rank=3 pagerank=2.3700e+00 url=www.lawfareblog.com/lawfare-podcast-former-congressman-brian-baird-and-daniel-schuman-how-congress-can-continue-function
   INFO:root:rank=4 pagerank=1.5529e+00 url=www.lawfareblog.com/events
   INFO:root:rank=5 pagerank=1.1867e+00 url=www.lawfareblog.com/water-wars-increased-us-focus-indo-pacific
   INFO:root:rank=6 pagerank=1.1867e+00 url=www.lawfareblog.com/water-wars-drill-maybe-drill
   INFO:root:rank=7 pagerank=1.1867e+00 url=www.lawfareblog.com/water-wars-disjointed-operations-south-china-sea
   INFO:root:rank=8 pagerank=1.1867e+00 url=www.lawfareblog.com/water-wars-us-china-divide-shangri-la
   INFO:root:rank=9 pagerank=1.1867e+00 url=www.lawfareblog.com/water-wars-sinking-feeling-philippine-china-relations
   ```

   Task 2, part 1:
   ```
   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
   ```

   Task 2, part 2:
   ```
   $ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona' --search_query='-corona'
   ```

1. Ensure that all your changes to the `pagerank.py` and `README.md` files are committed to your repo and pushed to github.

1. Get at least 5 stars on your repo.
   (You made trade stars with other students in the class.)

   > **NOTE:**
   > 
   > Recruiters use github profiles to determine who to hire,
   > and pagerank is used to rank user profiles and projects.
   > Links in this graph correspond to who has starred/followed who's repo.
   > By getting more stars on your repo, you'll be increasing your github pagerank, which increases the likelihood that recruiters will hire you.
   > To see an example, [perform a search for `data mining`](https://github.com/search?q=data+mining).
   > Notice that the results are returned "approximately" ranked by the number of stars,
   > but because "some stars count more than others" the results are not exactly ranked by the number of stars.
   > (I asked you not to fork this repo because forks are ranked lower than non-forks.)
   >
   > In some sense, we are doing a "dual problem" to data mining by getting these stars.
   > Recruiters are using data mining to find out who the best people to recruit are,
   > and we are hacking their data mining algorithms by making those algorithms select you instead of someone else.
   >
   > If you're interested in exploring this idea further, here's a python tutorial for extracting GitHub's social graph: <https://www.oreilly.com/library/view/mining-the-social/9781449368180/ch07.html> ; if you're interested in learning more about how recruiters use github profiles, read this Hacker News post: <https://news.ycombinator.com/item?id=19413348>.

1. Submit the url of your repo to sakai.

   Each part is worth 2 points, for 12 points overall.