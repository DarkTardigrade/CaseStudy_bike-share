# CaseStudy_bike-share
 
Analysis of Cyclistic's highest-value, casual to member conversion opportunities in 5.9M bike-share trips. A Google Data Analytics capstone project, completed with SQL and Tableau
 
## Slide show version
- Web link: —
- Download: —
## Cyclistic Case Study
Data from: Coursera | Google Data Analytics Capstone
Project completed by: Thomas D Cochran
 
## Business task
Learn how annual members and casual riders use Cyclistic bikes differently, from the perspective of designing a new marketing strategy to convert casual riders into annual members.
 
## Top 3 recommendations
 
1. **Target the commuter segment** — discounted trial/first-month membership for casual riders with short, weekday rush-hour, point-to-point trips. This segment already rides like a member: an 89.74% hour-of-day pattern match with confirmed member commuters, representing 9.16% of all casual trips.
2. **Weekend/leisure tier** — casual and member weekend ride timing overlap 94.08%. A leisure-framed offer (weekend-unlimited, seasonal discount) targets this large volume pool with a message suited to why they're actually riding, rather than a commute pitch they don't need.
3. **Hotspot-targeted marketing** — member and casual riders' top-10 busiest stations show *zero* overlap. Members cluster around downtown business intersections (Canal & Madison, Clinton & Washington); casual riders cluster around lakefront landmarks (Navy Pier, Millennium Park, Shedd Aquarium). In-person offers (QR codes, geofenced push notifications) placed at casual riders' own top stations reach 45% of casual ridership — a more efficient conversion target than marketing at member's own hotspots.
## Evidence
 
**Trip duration**
Members ride shorter on average than casual riders (~12.7 min vs. ~22.6 min).
 
![Average trip duration: member vs. casual](LookAtThisGraph/AvgTripDur2.png)

![Trip duration distribution by rider type](LookAtThisGraph/TripDurByRideType.png)
 
**Weekday commute pattern**
Isolating short (≤15 min), point-to-point trips on Tue/Wed/Thu rush hours, casual riders' hour-of-day timing shows an 89.74% shape match with confirmed member commuters.

![Weekday Commute-Hour Timing: Member vs. Casual (Tue–Thu, ≤15 min, point-to-point trips).](LookAtThisGraph/WeekDay.png)
 
**Weekend timing**
Casual and member riders overlap 94.08% in when they ride on weekends.

 ![Weekend Ride Timing: Member vs. Casual](LookAtThisGraph/WeekEnd.png)
 
**Station geography**
Casual trip share tracks 2–3 percentage points behind member trip share across every station-popularity tier tested (top 5 through top 500) — but the top-10 stations for each group show zero overlap.
 
[graph — two side-by-side horizontal bar charts (or one grouped chart). Left: Member's top 10 stations by trip count, labeled with station names. Right: Casual's top 10 stations by trip count, labeled with station names. Title: "Top 10 Stations by Rider Type — Member vs. Casual." Consider a small map graphic alongside showing the downtown cluster vs. lakefront cluster if you want to go further.]




