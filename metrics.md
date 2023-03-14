_Based on discussion in issues [#293](https://github.com/meilisearch/devrel/issues/293) and [#332](https://github.com/meilisearch/devrel/issues/332)._

![yrvcdbq2vg48z492aber](https://user-images.githubusercontent.com/2602288/147088244-6d6490fb-2e01-4854-8411-f0a0dbda1eaf.png)

This image is taken from the [Measuring Developer Relations](https://dev.to/dx/measuring-developer-relations-ie8) article written by [Shawn @swyx Wang](https://www.swyx.io/). This article encompasses our vision of KPIs.

As described in [#326](https://github.com/meilisearch/devrel/issues/326), there are many metrics that we can measure, and it's hard to choose one North Star metric for DevRel. North Star metrics are for companies, not for teams.

Ultimately, DevRel's goal is to get more **active users**, and we should measure this metric's growth.
But this is not a KPI that DevRel can use as it stands because we're not the only team doing work that influences this metric. It would not be fair to rely on this sole indicator to evaluate our performance.

As explained in the article and in our [manifesto](https://github.com/meilisearch/devrel/blob/main/devrel.md#the-3cs) (even if it needs some rework), we're embracing the 3C's approach. (In the article, "Product" is our equivalent of "Code").
And I think that we need the equivalent of a North Star metric for each of these pillars of our initiatives.
This means one master KPI for _Community_, for _Content_, and for _Code/Product_, and other metrics that can be useful to track.

## North star metric
| ID | KPI desc | Data | Chart|
|---|---|---|---|
| 0 | Monthly active databases (considered as our users: MAU) | From telemetry data | [Amplitude](https://analytics.amplitude.com/meili/chart/gm7nupg) _(private link)_  |

## Community
The main KPI is **community health**. This can be measured through community members' activity, the size of the community, the number of discussions... It's hard to define the precise metric to track. Fortunately, the [Orbit model](https://github.com/orbit-love/orbit-model#orbit-kpis) provides the right tools: **the size of each Orbit**. 
Here we focus on Slack. We could argue that the community is also on GitHub, Stack Overflow... if needed, we will re-assess these metrics again.

**Community dashboard [on Amplitude](https://analytics.amplitude.com/meili/dashboard/o7lqc4s) _(private link)_**

| ID | KPI desc | Data | Chart|
|---|---|---|---|
| 0 | Size of each Orbit | From orbit report. Following [how Orbit defines its orbit repartition](https://github.com/meilisearch/devrel/issues/327#issuecomment-1001999467), it's also interesting to look at the average love score for each orbit | [Amplitude](https://analytics.amplitude.com/meili/chart/hluf8zy) _(private link)_  |
| 1 | Presence for each orbit and for the whole community | computed, [as described in #327](https://github.com/meilisearch/devrel/issues/327#issuecomment-1005794055)  | [Amplitude](https://analytics.amplitude.com/meili/chart/6a29my1) _(private link)_ |
| 2 | Number of Discord community members | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=01b3f1ddc81a4516a81d49cabb8dac75) - source: [Discord](https://discord.com/developers/servers/1006923006964154428/analytics/) (_private links_) | [chart](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=1806228464&format=interactive) _(private link)_ |
| 3 | Number of Discord community members active in the last 30 days | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=01b3f1ddc81a4516a81d49cabb8dac75) - source: [Orbit](https://app.orbit.love/meili/reports/source?activity_type=slack%3Amessage%3Asent%2Cslack%3Achannel%3Ajoined%2Cslack%3Athread%3Areplied&affiliation=member&source=slack) (_private links_) | [chart](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=1229153591&format=interactive) _(private link)_ |
| 4 | Number of messages and discussions |  Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=01b3f1ddc81a4516a81d49cabb8dac75) - source: [Discord](https://discord.com/developers/servers/1006923006964154428/analytics/) (_private links_)  | [chart](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=1506294981&format=interactive) _(private link)_ |
| 5 | Number of Champions | [WIP ](https://github.com/meilisearch/devrel/milestone/6)|   |


## Content
The main KPIs are **analytics on the Ressource Center**. The main current difficulty is that the Ressource Center doesn't exist yet, and [we haven't done much work about it](https://github.com/meilisearch/devrel/milestone/5).
In the meantime, we can rely on other metrics. 

**Content dashboard [on Amplitude](https://analytics.amplitude.com/meili/dashboard/lybicqe) _(private link)_**
| ID | KPI desc | Data | Chart |
|---|---|---|---|
| 0 | Analytics on the resource center | [WIP](https://github.com/meilisearch/devrel/milestone/5) |   |
| 1 | Number of UGC (blog posts, tutorials, ...)| Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=aaaa57f80b3a4ac58b381b7151f32436) - source [Notion list](https://www.notion.so/meilisearch/e95536f3b1b8425ab0859f5505ba9864?v=4dd5fc5ccba341f8be2895ba1e5a94f6) _(private links)_ | TODO |
| 2 | Number of events and attendance | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=aaaa57f80b3a4ac58b381b7151f32436) - source [UGC Notion list](https://www.notion.so/meilisearch/e95536f3b1b8425ab0859f5505ba9864?v=4dd5fc5ccba341f8be2895ba1e5a94f6) and [Events Notion list](https://www.notion.so/meilisearch/Events-1fd89bd590394d44af7c7db327e5c623) _(private links)_ | TODO |
| 3 | Number of workshops and attendance | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=aaaa57f80b3a4ac58b381b7151f32436) _(private link)_ | TODO |
| 4 | Number of newsletter subscribers, opens and clicks | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=98a2c2227c604b349b62c839ee1fd872) - source: [Mailchimp](https://us2.admin.mailchimp.com/reports/) _(private links)_|  [chart subscribers](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=1649342680&format=interactive) - [chart engagement](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=2007321837&format=interactive) _(private links)_  |
| 5 | Number of Twitter followers, mentions, and engagement | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=82af0f9db1cf4695a50d30eb9f528436) - source: [Twitter](https://analytics.twitter.com/user/meilisearch/home)  _(private links)_| [chart followers](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=1943728927&format=interactive) - [chart engagement](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=513472966&format=interactive) _(private links)_   |
| 6 | Number of Linkedin followers, mentions, and engagement | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=7dc44375adb7458fa045944923fd58a4) - source: [Linkedin](https://www.linkedin.com/company/13016868/admin/analytics/visitors/)  _(private links)_| [chart followers](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=1460435516&format=interactive) _(private link)_   |
| 7 | Number of blog posts created and audience | Blog posts currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=f68dc3a1481740628550e2771b443862) - source: [Meilisearch blog](https://blog.meilisearch.com) / audience source: [Fathom](https://app.usefathom.com/?filters%5B0%5D%5Boperator%5D=is&filters%5B0%5D%5Bproperty%5D=Domain&filters%5B0%5D%5Bvalue%5D=https%3A%2F%2Fblog.meilisearch.com&page=1&range=last_month&site=QNBPJXIV&sort=visitors%3Adesc)| [chart blog posts creation](https://docs.google.com/spreadsheets/d/e/2PACX-1vS_8gJhoI3jCcLaw_xhOrkaNBp98VZ-z_vWUph6ytSbip_4hkDncPGsjtnRwLIUjYzIy8sEUsaSV3-b/pubchart?oid=649259286&format=interactive) _(private link)_ |
| 8 | Number of demos created| Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=aaaa57f80b3a4ac58b381b7151f32436) _(private link)_ | TODO |
| 9 | Number of use cases | Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=aaaa57f80b3a4ac58b381b7151f32436) _(private link)_ | TODO |
| 10 | Domain authority| Currently on [Notion](https://www.notion.so/meilisearch/fe5f4cff1224490ebc489fe50a503c58?v=6bd6ebfb23684e52bb84a2c9baa9c0b5)  - source: [Moz](https://moz.com/domain-analysis?site=meilisearch.com) _(private links)_ | TODO |


## Code/Product
The main KPI is the **number of Meilisearch instance launches** _(edit: previously I preferred downloads, but launches seem more relevant)_. Distribution is critical, and this measures if it's done right.

**Code/product dashboard [on Amplitude](https://analytics.amplitude.com/meili/dashboard/s343sbg) _(private link)_**

| ID | KPI desc | Data | Chart |
|---|---|---|---|
| 0 | Number of Meilisearch instance launches | from telemetry data | [Amplitude](https://analytics.amplitude.com/meili/chart/4n55ed9) _(private link)_  |
| 1 | Number of contributors| from [Orbit](https://app.orbit.love/meili/members?affiliation=member&activity_type=pull_requests%3Amerged&relative=last_30_days&rt=1)  _(private link)_| asked in [#327](https://github.com/meilisearch/devrel/issues/327#issuecomment-1105458945)  |
| 2 | Number of contributions | from Orbit | [Amplitude](https://analytics.amplitude.com/meili/chart/zg5terf) _(private link)_  |
| 3 | Number of GitHub Stars | from Github | [Amplitude](https://analytics.amplitude.com/meili/chart/obexvb7) _(private link)_ |
| 4 | Number of integration users | from telemetry data | [Amplitude](https://analytics.amplitude.com/meili/chart/0sose4i) _(private link)_  |
| 5 | NPS/[Sean Ellis question](https://review.firstround.com/how-superhuman-built-an-engine-to-find-product-market-fit#anchoring-around-a-metric-a-leading-indicator-for-productmarket-fit) | not done yet at Meilisearch |   |
