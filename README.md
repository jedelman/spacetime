# SpaceTime: A spatiotemporal social network
Why isn’t anyone doing this yet?
## The problem: GIS is complex and inaccessible
I keep seeing the need for collaboratively journaling things in spatial relation and temporal sequence. Specialized GIS solutions exist for specialized problems, and generalized GIS systems exist which require adaptation to your specific situation.
## The solution: general purpose GIS for laymen
I don’t understand why we don’t have an app/website for recording event data - what happened, where and when - then sharing, compiling, searching, and displaying it. 
- Operational
  - Principals
      - Dev community
        - FOSS - MIT license
      - Ops/admin/deployment
        - Freemium hosting
        - Self-host options
        - Federated server model
      - Investor community
        - Nonprofit for dev
        - For-profit hosting
      - User community
        - Localized user groups
        - Conferences
  - Technical Overview
      - ontology
        - Where: lat-long - ISO 6709
        - when: datetime - ISO 8601
        - Who: #tags, @tags, Public / group-restricted / private
        - What: content or link to content - markdown? Text, Image, Video?
        - Why: links
     - p2p exchange protocol
   - reference client implementation - i.e. this repository
      - Feed view
      - Group chat/direct messages
      - Map view with time slider
