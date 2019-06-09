# Google Analytics Academy notes

Link: https://analytics.google.com/analytics/academy/

## About

Lots of information (videos, articles) about Google Analytics. Includes exercises based on the [Google Merchandise Store demo account](https://support.google.com/analytics/answer/6367342?hl=en&%3Bref_topic=1727148). Also has assessment test for each section.

[Demo account](https://support.google.com/analytics/answer/6367342?hl=en&%3Bref_topic=1727148)

## Certificates

- [Completion certificate (Basic)!](https://analytics.google.com/analytics/academy/certificate/EOVCm3WVRVaKakBZejAONQ) 
- [Completion certificate (Advanced)!!](https://analytics.google.com/analytics/academy/certificate/xlmJdhnpTtuaIr2jvmd5tg)

## Google Analytics for Beginners

- Basics
  - [How to verify view filters](https://support.google.com/analytics/answer/6046990?hl=en) (Google)
  - [About regular expressions](https://support.google.com/analytics/answer/1034324?hl=en) (Google)
  - [Basic Google Analytics for every site](https://www.bounteous.com/insights/2015/12/10/basic-google-analytics-filters-every-site/?ns=l)
  - [Regular expressions for GA](http://www.lunametrics.com/regex-book/Regular-Expressions-Google-Analytics.pdf)
  - Sharing dashboards
  - TRY THIS: public dashboards on [solutions gallery](https://analytics.google.com/analytics/gallery/?hl=en_US#posts/search/%3F_.type%3DDASHBOARD%26_.start%3D0/)
  - [Overview of audience reports](https://support.google.com/analytics/answer/1012034?hl=en)
  - [Exit rate vs bounce rate](https://support.google.com/analytics/answer/2525491?hl=en)
- Campaign and conversion tracking
  - Adwords is now Google Ads
  - [Best practices for creating Custom Campaigns](https://support.google.com/analytics/answer/1037445?hl=en)
  - [4 Steps To Better Campaign Data In Google Analytics](https://www.bounteous.com/insights/2011/09/08/4-steps-better-campaign-data-google-analytics/?ns=l)
  - CPC: cost-per-click
  - campaign tagging
  - TRY: URL builder tool
    - [Campaign URL Builder](https://ga-dev-tools.appspot.com/campaign-url-builder/)
  - [UTM Tracking Template](https://docs.google.com/spreadsheets/d/1tf3_SczMMTTf-ZJ9Bkb70xps_DPGLBTd4wkHPyadKSA/edit?hl=en_US&;usp=sharing&hl=en_US#gid=1)
  - Goals
    - goal funnel
    - goal ypes
      - destination, duration, pages, events
    - shows up in "Conversions"
    - [Match Types: Begins with, Equals to, & Regular Expression](https://support.google.com/analytics/answer/1116091?hl=en#matchTypes)
    - [Goal templates](https://analytics.google.com/analytics/gallery/?hl=en_US#posts/search/%3F_.type%3DGOAL%26_.start%3D0%26_.term%3Dgoals/)
    - [LunaMetrics Deleting Goals in Google Analytics](https://www.bounteous.com/insights/2013/02/05/deleting-goals-google-analytics/?ns=l)
  - Google Ads
- IDEAS
  - See the top performing pages for new users
    - Behavior > Site Content > All Pages: Add secondary dimension "User type"
  - To see ineffective landing pages:
    - Behavior > Site Content > Landing pages: Sort by bounce rate
    - Plus: Add secondary dimension of "campaign" or "source medium"
  - To see conversions by location:
    - Geo > Location: Select goal from pull-down and sort by conversion rate
- Resources
  - [Monitor account health and performance](https://support.google.com/analytics/topic/1727147?hl=en&%3Bref_topic=3544907)
  - [Diagnostics and troubleshooting](https://support.google.com/analytics/topic/6277287?hl=en&%3Bref_topic=1727148)

## Advanced Google Analytics

### Terms

- new user, returning user

### Data collection

- hits
  - pageview, event, transaction
  - [Domains and directories](https://support.google.com/analytics/answer/6205202?hl=en)
  - [Data limits](https://support.google.com/analytics/answer/1070983?hl=en)
  - [Data privacy and security](https://support.google.com/analytics/topic/2919631?hl=en)
  - [Check your tag setup](https://support.google.com/analytics/answer/1008083?hl=en)
  - [Definition of a web session](https://support.google.com/analytics/answer/2731565?hl=en)
  - [Linking Google Analytics to Search Console](https://support.google.com/analytics/answer/1308617?hl=en_US)
  - Try: Content groupings - lets you aggregate metrics based on the organization of site
  - [About view filters](https://support.google.com/analytics/answer/1033162?hl=en)
  - [About goals](https://support.google.com/analytics/answer/1012040?hl=en)
    - [Goal examples and use cases](https://support.google.com/analytics/topic/6150929)
  - [About channel groupings](https://support.google.com/analytics/answer/6010097?hl=en)
  - [About content groupings](https://support.google.com/analytics/answer/2853423?hl=en)
    - NOTE: Content grouping is not retroactive
  - [Dimensions and metrics](https://support.google.com/analytics/answer/1033861?hl=en)
  - [Dimensions and metrics explorer](https://developers.google.com/analytics/devguides/reporting/core/dimsmets)
  - TODO: [Create a measurement plan](https://support.google.com/analytics/answer/7165633?hl=en)
    - macro conversion and micro conversion
    - [Example measurement plan](https://analytics.google.com/analytics/academy/course/7/unit/1/lesson/5)
      - [More details](https://support.google.com/analytics/answer/6224341?hl=en)

### Setting up data collection

- TODO: Site linking or cross-domain tracking
  - Use Google Tag Manager to update code
- [Example account structures](https://support.google.com/analytics/answer/1102152?hl=en_US)
- [Multiple trackers](https://developers.google.com/analytics/devguides/collection/analyticsjs/creating-trackers?hl=en_US#working_with_multiple_trackers)
- [Roll up reporting](https://support.google.com/analytics/answer/6033415?hl=en)
  - to aggregate data from multiple properties
- [Cross-domain tracking](https://support.google.com/analytics/answer/1033876?hl=en)
  - see sessions on two domains as same session
- Advanced filters
  - [regular expressions](https://support.google.com/analytics/topic/1034375?hl=en)
- [Custom dimensions](https://analytics.google.com/analytics/academy/course/7/unit/2/lesson/3)
  - [custom dimensions and metrics](https://support.google.com/analytics/answer/2709828?hl=en)
- [Custom metrics](https://support.google.com/analytics/answer/7165644?hl=en)
  - Use Google Tag Manager to manage tracking code
  - [Set up custom metrics](https://support.google.com/analytics/answer/2709829?hl=en)
  - [Custom dimensions and metrics devguide](https://developers.google.com/analytics/devguides/collection/analyticsjs/custom-dims-mets?hl=en_US)
- TODO: [Set up event tracking](https://support.google.com/analytics/answer/7165642?hl=en)
  - examples
    - click play button, pause video
    - outbound link clicks
    - [event tracking template](https://docs.google.com/spreadsheets/d/1UIGf7KeuDZRI8Em5CP3lcZMXRqonSaSTis5aMU9M3Ac/edit?hl=en_US#gid=1247783967)
    - [set up event tracking](https://support.google.com/analytics/answer/1136960?hl=en)
    - [capture outbound links](https://support.google.com/analytics/answer/1136920?hl=en)
- TODO: [Set up internal site search](https://support.google.com/analytics/answer/7165643?hl=en)
  - [site search metrics](https://support.google.com/analytics/answer/1032321?hl=en)
  - [Five questions for site search data](https://support.google.com/analytics/answer/1032402?hl=en)

### Advanced analysis tools

- [Segments](https://support.google.com/analytics/answer/7165574?hl=en)
  - [About segments](https://support.google.com/analytics/answer/3123951?hl=en)
  - [Best practices](https://support.google.com/analytics/answer/6155560?hl=en)
  - [16 secrets](https://searchenginewatch.com/sew/how-to/2268458/16-secret-google-analytics-advanced-segments-worth-their-weight-in-gold)
- [Channel report analysis](https://support.google.com/analytics/answer/7165722)
  - [Multi-channel funnel reports](https://support.google.com/analytics/answer/7165174?hl=en)
  - [Attribution modeling](https://support.google.com/analytics/answer/1662518?hl=en)
- Analyze data by audience
- [Using custom reports](https://support.google.com/analytics/answer/1033013?hl=en)

### Advanced marketing tools

- [Remarketing](https://support.google.com/analytics/answer/7166025?hl=en)
- [Dynamic remarketing](https://support.google.com/analytics/answer/7166576?hl=en)
