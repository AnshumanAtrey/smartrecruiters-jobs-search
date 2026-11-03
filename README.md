# SmartRecruiters Jobs Scraper & API - Remote, Last 24 Hours

SmartRecruiters jobs scraper and API: search the career sites of 2,900+ companies on SmartRecruiters (careers.smartrecruiters.com and jobs.smartrecruiters.com) at once, live, and get each job's title, company, location, remote, hybrid or onsite, job type, department, exact posting time and link, newest first. Turn on full details for the description, the pay with its period, the reference number and the city, region and country.

Use it as a SmartRecruiters jobs API, a careers.smartrecruiters.com scraper or a daily job feed from the Apify Console, the Apify API, Python, JavaScript, n8n, Make or an AI agent, and export JSON, CSV or Excel. It is the `site:careers.smartrecruiters.com` Google dork done at the source, with the fields a search result cannot give you. Available as an [Apify Actor](https://apify.com/anshumanatrey/smartrecruiters-jobs-search). $0.0025 per job, $0.0035 with full details, no start fee, no login, no API key.

## What does it do?

- **Searches 2,917 career sites of 2,907 companies at once**: 222,729 open jobs in 198 countries on 2026-11-03, at companies such as Bosch, ServiceNow, LinkedIn, Domino's, Accor, H&M, Deloitte, Canva, Ubisoft and Delivery Hero.
- **One keyword is enough.** Type a job title and press Start. Leave the form empty for the newest jobs of every kind.
- **Newest first, read live.** Every job comes from SmartRecruiters at the moment of your run, dated to the millisecond, not from a stored copy.
- **Fresh jobs in volume.** 8,406 jobs were posted on these career sites in the 24 hours before a count on 2026-11-03, and 36,138 in 7 days.
- **Filters that take what people type.** Germany, EMEA, Remote, part time, last 24 hours, or a pasted Google dork such as `site:careers.smartrecruiters.com/BoschGroup intext:software`.
- **Pay and full descriptions when you want them.** Full details add the job ad, the pay with its period when the company publishes it, the reference number and the place.
- **Checks job links.** Paste links and each comes back open, closed or not found.

## How is it different from other SmartRecruiters scrapers?

- **You do not need to know the companies.** SmartRecruiters publishes no list of its customers, and 67 of the 124 Store actors with SmartRecruiters in their name or title will not start without a company ID, link or board (2026-11-02). This actor carries a list of 2,917 career sites built from SmartRecruiters' own company search, web archives and public job data, so one keyword covers them all and finds companies you had never heard of.
- **Years-old postings stay out.** SmartRecruiters keeps a job open until its company closes it, and many never do: on 2026-11-03, 9,626 career sites had posted nothing for two years yet still listed 179,872 jobs as open, 129,611 of them on sites whose newest job was from 2017. A search leaves those sites out; name such a company and it is read, with each job's real date.
- **Test postings stay out.** Sandbox, test and demo accounts post tests, templates and copies of real jobs. On 2026-11-03, 46 such accounts held 3,714 postings, and 748 more on 33 real career sites were titled as tests, such as Pilot Flying J's `(J_SYNC_TEST)Deli Baker`. A search leaves them out, so you never pay for one.
- **Companies that SmartRecruiters' own job search leaves out.** The cross-company search on jobs.smartrecruiters.com answers with only the newest 100 jobs of a query, and 1,387 career sites with open jobs were missing from its company list on 2026-11-02, 617 of them among the 2,917 this actor searches. AbbVie (1,855 jobs on 2026-11-03) and the City of New York (1,397) are two of them, and this actor reads both.
- **The real posting date, to the millisecond.** Each job's date is the instant its own page gives Google as datePosted (11 of 11 pages checked), so the last 24 hours means 24 hours.
- **A place is where the job is.** Some companies file an office under a continent: Turner & Townsend lists Amsterdam under "Europe". This actor reads that as Amsterdam, Netherlands, so a search for Germany does not return it.
- **Company IDs in any capitals.** BoschGroup and boschgroup read the same career site, and a name such as Bosch Group finds each of its career sites on the list.
- **A failed read costs nothing.** You pay per delivered row.

## When should I use it?

- **Job seekers and job boards:** the newest jobs at large employers in Europe, the US and beyond, filtered by place, remote work and job type, on a daily schedule.
- **Recruiters and sourcing teams:** see who is hiring for a role across 2,900+ companies on SmartRecruiters, and where.
- **Sales and market research:** a company's open jobs show where it is growing, by department and by country.
- **Data teams and AI agents:** one clean, stable feed of SmartRecruiters jobs through the API or MCP.

## How much does it cost to scrape SmartRecruiters jobs?

Pay per event. Platform usage is included, and there is no start fee or monthly fee.

| Event | Price | When it is charged |
|---|---|---|
| Job | $0.0025 | One saved job, and one checked link that is closed or not found |
| Job with details | $0.0035 | One saved job with full details on |

On paid Apify plans these are 10% less on Scale ($0.00225 and $0.00315) and 20% less on Business and above ($0.002 and $0.0028).

| Job (Free and Starter price) | Cost |
|---|---|
| 100 newest jobs | $0.25 |
| 100 jobs with full details | $0.35 |
| 1,000 jobs | $2.50 |
| Every job posted in one day (8,406 on 2026-11-03) | $21.02 |

Apify's free $5 monthly credit covers 2,000 jobs, or about 1,400 with full details. Number of jobs (`maxJobs`) sets the most a run can cost, and a run stops at its spending limit with a message saying so.

## How does the price compare with other SmartRecruiters scrapers?

Every actor on the Apify Store whose listing says it reads SmartRecruiters jobs and that had 20 or more users in the last 30 days, or 3 or more with SmartRecruiters in its title, ordered by those users. Found on 2026-11-02 by reading the 1,207 job listings that name SmartRecruiters among the 2,705 actors returned by 36 Store searches; users and free-plan prices from each actor's record the same day.

| Actor | Users, 30 days | Per job | Start fee | Covers |
|---|---|---|---|---|
| fantastic-jobs/career-site-job-listing-api | 1,632 | $0.012 | $0.01 | 58 ATS from its own database; `smartrecruiters` is one filter |
| fantastic-jobs/career-site-job-listing-feed | 282 | $0.0025 | $0.10 | The same database as a feed |
| hirebase/job-search | 137 | $0.005 | $0.001 | 80+ ATS from its own index; SmartRecruiters is one platform filter |
| jobo.world/ats-jobs-api | 134 | $0.004 | $0.00005 | 150+ platforms from its own index; SmartRecruiters is one source |
| bovi/greenhouse-lever-ashby-job-scraper | 100 | $0.0015 | $0.00005 | 6 ATS, the companies you name or 4 preset lists |
| memo23/career-site-ats-jobs-api | 81 | $0.004 | $0.03 | 116 ATS, the companies you name |
| jobspipe/jobspipe-job-search | 61 | $0.00196 | none | Its own index of job boards and 12 ATS; `smartrecruiters` is one source |
| openclawai/career-site-ats-jobs-scraper | 47 | $0.0005 | none | 60+ ATS by its listing (34 named), the careers page or company name you give it |
| santamaria-automations/career-site-jobs-scraper | 23 | $0.001 | $0.001 | 42 ATS and job sites, the career-site links you give it |
| lergassy/jobs-api | 20 | $0.006 | none | Indeed, LinkedIn and 5 ATS; the SmartRecruiters boards you name. $0.0001 from 2026-11-13 |
| blackfalcondata/greenhouse-scraper | 6 | $0.00095 | $0.005 | 6 ATS, the board links you give it |
| pulsedata/career-page-jobs-scraper | 5 | $0.002 | none | 12 ATS, the board or careers-page links you give it |
| jobo.world/smartrecruiters-jobs-scraper-api | 5 | $0.004 | none | SmartRecruiters only, by keyword from its own index |
| memo23/smartrecruiters-scraper | 3 | $0.0009 | $0.025 | SmartRecruiters only, the company IDs you give it |
| This actor | new | $0.0025 | none | SmartRecruiters only, 2,917 career sites read live, no IDs needed |

Per job is each actor's main event; some charge more for extra data. Where others are cheaper: bovi, openclawai, santamaria-automations, blackfalcondata, pulsedata and memo23's SmartRecruiters actor cost less per job when you already know the companies, and jobspipe costs less per job across its sources. Where others do more: the multi-ATS actors cover many platforms in one run. The other 120 actors with SmartRecruiters in their name or title had 2 users or fewer each.

Left out although their listings name SmartRecruiters: factpipe/ats-jobs-feed (98 users), glitchbound/ats-jobs-scraper (63), jtpalms/ats-jobs-index (60) and conserving_celerytop/live-career-page-jobs-api (55) say they do not read it, and kaix/linkedin-jobs-scraper (174) reads it only to enrich jobs found on LinkedIn.

## Which inputs does it take?

Nothing is required. Type a job title and press Start, or press Start with the form empty.

| Field | What it does |
|---|---|
| Job titles to find (`searchTerms`) | One per line. A job matches when its title has every word, with or without accents. SmartRecruiters' own search finds the words, so frontend and front end find different jobs: add both lines to get both. A pasted Google dork or SmartRecruiters link works too |
| Where the job is (`location`) | A city, state, country or region: London, United States, Germany, EMEA. Remote asks for remote jobs |
| Remote or onsite (`workType`) | remote, hybrid or onsite: remote and hybrid as the company flagged them, every other job onsite |
| Posted in the last (`postedWithin`) | 24 hours, 3 days, 7 days, 30 days, any time, or your own period such as 48 hours |
| Number of jobs (`maxJobs`) | How many, newest first: 100 by default, 0 for every match |
| Full details (`includeDetails`) | Adds the description as text and HTML, pay with its currency and period, the reference number, city, region, country and country code |
| Leave out words (`excludeTerms`) | Drops jobs whose title has these words, such as senior or intern |
| Job type (`employmentType`) | full-time, part-time, contract or intern, the four job types SmartRecruiters jobs carry (its Casual counts as part-time): temporary or seasonal finds nothing |
| Match descriptions (`searchDescriptions`) | Finds your words in the description too, not only the title |
| Only these companies (`companies`) | A name (Bosch Group), the company ID (BoschGroup) or a SmartRecruiters link. Empty searches every company on the list |
| Job links to check (`jobUrls`) | Paste job links, smrtr.io short links included, to check whether they are still open, instead of searching |

Example input:

```json
{
  "searchTerms": ["software engineer"],
  "location": ["Germany", "United States"],
  "postedWithin": "30 days",
  "maxJobs": 100
}
```

## What does the output look like?

One row per job, newest first. These rows are from a local run of the actor's engine on 2026-11-02, searching every company for software engineer and saving the 100 newest. TODO_DEPLOYED: the same table and JSON row from a run of the deployed build, with its run id.

| Job title (`title`) | Company name (`company`) | Job location (`location`) | Remote or onsite (`workType`) | Job type (`employmentType`) | Posted on (`postedAt`) |
|---|---|---|---|---|---|
| Senior Staff Software Engineer, JavaScript Runtime & Compilers | ServiceNow | San Diego, California, United States | remote | full-time | 2026-11-02 |
| Staff Software Engineer, Reliability | LinkedIn | Mountain View, CA, United States | hybrid | full-time | 2026-11-02 |
| Software Engineer - AI Platform (Hybrid) | AbbVie | North Chicago, IL, United States | hybrid | full-time | 2026-11-02 |
| Software Engineer Graduate | Bosch Group | Nuneaton, England, United Kingdom | onsite | full-time | 2026-11-02 |
| Software Engineer Android | Delivery Hero | Montevideo, Uruguay | hybrid | full-time | 2026-11-02 |

One row as JSON:

```json
{
  "title": "Senior Staff Software Engineer, JavaScript Runtime & Compilers",
  "company": "ServiceNow",
  "location": "San Diego, California, United States",
  "workType": "remote",
  "employmentType": "full-time",
  "department": "Engineering, Infrastructure and Operations",
  "salary": null,
  "postedAt": "2026-11-02T20:23:23.631Z",
  "jobUrl": "https://jobs.smartrecruiters.com/ServiceNow/744000159234126-senior-staff-software-engineer-javascript-runtime-compilers",
  "applyUrl": "https://jobs.smartrecruiters.com/ServiceNow/744000159234126-senior-staff-software-engineer-javascript-runtime-compilers?oga=true",
  "status": "open",
  "platform": "smartrecruiters",
  "companySlug": "ServiceNow",
  "jobId": "744000159234126",
  "checkedAt": "2026-11-02T20:48:11+00:00"
}
```

Full details add `description`, `descriptionHtml`, `reference`, `salaryMin`, `salaryMax`, `salaryCurrency`, `salaryPeriod`, `city`, `region`, `country` and `countryCode`, and fill `salary` when the company publishes pay, such as `USD 37 - 60.98 an hour` for a registered nurse at Northwestern Memorial Healthcare. A run also writes an `OUTPUT` record: how many career sites were read, how many jobs were saved, the matching jobs it counted while reading, and any notes on how your input was read.

## How fast is it?

TODO_DEPLOYED: the seconds and cost of the empty form and of the example input at the default memory on the deployed build, with their run ids.

Every search reads all 2,917 career sites, about 3,050 requests for an empty form or one keyword (local runs, 2026-11-03: 39 to 43 s), because SmartRecruiters dates each job to the millisecond and the newest jobs can sit on any of them. Each keyword is its own pass over every site, so five keywords took 14,844 requests and 187 s. Requests are paced to 80 a second, below the rate at which SmartRecruiters starts refusing one address. Naming companies in Only these companies reads only those: Bosch Group took 5 requests. Full details add one request per saved job.

## Common questions

### How does it find the companies?

SmartRecruiters publishes no customer list, so the list is built the way the `site:careers.smartrecruiters.com` dork works, at the source: SmartRecruiters' own company search, the Wayback Machine, Common Crawl, freehire's public job data and a public GitHub list gave 15,969 candidates, each checked live on 2026-11-02, and every site found was checked again on 2026-11-03. 12,589 career sites had open jobs: the 2,917 that posted within two years are searched, and 46 sandbox, test and demo accounts are left out. An estimate from how much the sources overlap puts the sites found at 83 to 90% of all SmartRecruiters career sites with open jobs, holding 93 to 96% of their jobs, possibly less, because the sources are not independent. To search a company that is not on the list, type its name or paste its link into Only these companies.

### Why does a search leave some companies out?

SmartRecruiters keeps a job open until the company closes it, and many never do. On 2026-11-03, 9,626 career sites had posted nothing since 2024-11-03 yet still listed 179,872 jobs as open. A search skips those sites, so the newest jobs it returns are live ones, and each refresh of the list checks them again. It also skips sandbox, test and demo accounts, whose postings are tests and copies. Name such a company in Only these companies and it is read, with each job's real date.

### Why is there no pay on most rows?

SmartRecruiters' job list carries no pay, so it comes only with full details on, from each job's own record: 15% of a sample of 2,000 jobs had pay on 2026-11-03, and 70 of the 100 newest nurse jobs in the United States in a run the same day. The period is the one the company states (year, month, week, day or hour). A maximum stated alone reads "up to", and a period nobody stated is never guessed.

### What does remote mean here?

What the company flagged on SmartRecruiters: 4.8% of jobs are remote and 13.7% hybrid (2026-11-03). Every other job is onsite, SmartRecruiters' own third choice.

### Does it need a login or an API key?

No. It reads SmartRecruiters' public Posting API, the one SmartRecruiters offers its customers for building their own career sites, and public jobs need no key there. You need only an Apify account.

### How do I run it from Python or an AI agent?

Through the Apify API, with your Apify token:

```python
from apify_client import ApifyClient

client = ApifyClient("<YOUR_APIFY_TOKEN>")
run = client.actor("anshumanatrey/smartrecruiters-jobs-search").call(run_input={"searchTerms": ["software engineer"]})
for row in client.dataset(run["defaultDatasetId"]).iterate_items():
    print(row["title"], row["company"], row["location"], row["workType"], row["jobUrl"])
```

AI agents can call it through the Apify MCP server at https://mcp.apify.com, and n8n and Make have Apify nodes.

### Am I charged for closed jobs?

A search returns open jobs only. A pasted link that turns out closed or not found is one Job row, because it was checked and answered.

### Is it legal to use?

It reads public job postings. You are responsible for how you use the data, including each site's terms and the privacy laws that apply to you.

## Limitations

- One place per job: SmartRecruiters stores one location for each posting, and its API gives no closing date.
- Pay comes only with full details, and about 6 jobs in 7 show none.
- Every search reads every career site on the list, so a filter that matches almost nothing, such as a rare place, reads every page of every site and takes several times longer than a normal search.
- Some large posters are staffing firms or job boards that post for other employers, such as Jobs for Humanity (2,823 jobs on 2026-11-03).
- The department field holds what the company typed: sometimes a person's name, or several teams joined by a vertical bar.
- Titles and descriptions come in the company's own language.
- The same job at the same place at one company is delivered once.
- A company that locked its job API, such as CHECK24, cannot be read and comes back as not found.
- The list of career sites was last checked on 2026-11-03. A company that joined later, or a quiet one that starts posting again, is searched when you name it, until the next refresh of the list.

## Who maintains it?

Built and maintained by **Anshuman Atrey** ([@AnshumanAtrey](https://github.com/AnshumanAtrey)), who publishes a portfolio of data and OSINT actors on Apify Store. For a feature request or a bug, message [LinkedIn](https://linkedin.com/in/anshumanatrey) (fastest), open an issue on the GitHub repo, or write through [atrey.dev](https://atrey.dev).

## Sibling actors

| Actor | Use case |
|---|---|
| [ashby-jobs-search](https://apify.com/anshumanatrey/ashby-jobs-search) | Every job on every Ashby board, searched live |
| [workday-job-search](https://apify.com/anshumanatrey/workday-job-search) | Every job at 1,688 Workday employers, searched live |
| [cornerstone-jobs-search](https://apify.com/anshumanatrey/cornerstone-jobs-search) | Every job on every Cornerstone career site |
| [deel-jobs-search](https://apify.com/anshumanatrey/deel-jobs-search) | Every job on every Deel ATS career page, with pay |
| [greenhouse-jobs-search](https://apify.com/anshumanatrey/greenhouse-jobs-search) | Jobs on Greenhouse job boards, searched live |
| [lever-jobs-search](https://apify.com/anshumanatrey/lever-jobs-search) | Jobs on Lever job sites, searched live |
| [workable-job-search](https://apify.com/anshumanatrey/workable-job-search) | Jobs on Workable job boards, searched live |
| [linkedin-harvester](https://apify.com/anshumanatrey/linkedin-harvester) | Email to LinkedIn profile, for the people behind a company |

## Documentation

- Apify Store: https://apify.com/anshumanatrey/smartrecruiters-jobs-search
- GitHub repo: https://github.com/AnshumanAtrey/smartrecruiters-jobs-search (MIT license, see [LICENSE](LICENSE))
- The engine behind it: https://github.com/AnshumanAtrey/ats-jobs-engine

## Last updated

2026-11-03 (version 1.0)
