# TLDR

The Open Goverment Data Initiative advocates for laws that force government to proactively publish data in machine-readable formats.

It is non-partisan ; we support exposing _all_ data, whether that might support the policies of the left, the right, both, or neither.

It does not advocate for government-provided _tools_ to view or read data; it advocates only for the _publishing_ of data.

( The OGDI believes in [The Unix Philosophy](https://en.wikipedia.org/wiki/Unix_philosophy): small tools, loosely coupled.  Make the [government provide the data and the free market will do the rest](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar)! )

Finally, OGDI is based in New Hampshire and advocates first and foremost for state-level laws, but we support activists in other states and look forward to sharing model legislation and discussing best practices.

# The problem

At the federal level we have FOIA (the Freedom of Information Act).

At the state level in New Hampshire we have RSA 91-a (a "right to know" law).

Both of these require:
1. that a citizen know what information they want
1. that a citizen send in a request to the government
1. that the citizen wait for the government (often there's a 'deadline', but (a) there are no penalties when the government breaks the deadline, (b) the deadline can be satisfied by the government merely replying by the specified date "this may take up to three years").

Further, the data
1. does not come back in a machine-readable format
1. is published, at most, once, and not repeatedly (e.g. annually, quarterly, weekly...)

Contrast this to the private sector where every 1-person ecommerce business, or 4-hour-per-week software side project has a [dashboard](https://en.wikipedia.org/wiki/Dashboard_(computing)).

A typical 1-person project has a dashboard that displays in real-time (update cycle of < 1 second) and shows things like
- number of site visitors
- percent of site visitors that spend more than 1 second on site
- percent of site visitors that put an item in a shopping cart
- percent of site visitors that click the checkout button
- number of orders received
- total value of orders received
- inventory levels
- packages shipped per day
- etc.

This has been state-of-the-art in the private sector for almost 30 years.

Now compare this to even a small responsive state like New Hampshire, where almost no data is proactively published, and what is published is

- not machine readable
- often out of data

For examples of both problems, look at the NH Department of Education data for (Weare's high school)[https://my.doe.nh.gov/profiles/profile.aspx?d=275&year=2017], which hasn't been updated in over seven years, and which is presented in crappy HTML format.

# What sort of data do we want to see?

All of it!

Pick the issue that you care about:

## Children

- How many families did DCYF investigate last year?
- How many children were taken into state custody?
- How many of those children were placed in foster homes within one week?
- ...within two weeks?
- ...within a month?
- How many of the children placed in foster homes were seen by therapists within a week?
- ...a month?
- ...ever?
- How many of those children placed in foster homes had the appropriate paperwork from DCYF to attend local schools?
- ...and how many didn't, because DCYF couldn't get its act together in time, and children instead stayed home?
- How many children in DCYF custody were shipped to out-of-state facilities?
- How many children in DCYF custody were sexually abused?
- How many children in DCYF custody died?

and further: how do the figures for 2023 compare to 2022, 2021, 2020, etc?  Is NH DCYF getting better at getting children needed care?  ...or worse?

and further: how does NH DCYF's numbers compare to, say, Vermont's ?  or Maine's?  Are NH children who have survived trauma seeing therapists in half the time that Vermont children do?  Or twice the time?  Are we paying twice as much per child processed?  

## Police and Crime

- How many drunk driving arrests were there state-wide this year?  Last year? 10 years ago?
- What percent of those arrests led to conviction?
- What percent of those convicted went to jail?
- What percent of those arrested ended up not charged at all?
- Are we sending more or fewer drunk drivers to jail now vs then?
- Are conviction rates heading up or down?
- ...out of how many drivers, and driver-miles (we want to be able to scale statistics appropriately, not have them be swamped by secular trends / exogenous events)?
- How many robberies were reportyed in Hillsborough county last year?
- ...how does that compare, per capita, to the same county five years ago?  To Strafford county this year?
- How do robberies correlate with population density?  With demographics like age of the perpetrator?

## Colleges

For any given college in the state:

- How many people applied to the college?  What were their average SAT scores?
- How many people were accepted?  What were their average SAT scores?  What were the scores broken down by race (suggestive of institutions abusing their non-profit status to illegally discriminate against citizens)?
- What percent of students successfully completed each degree program?
- What percent of students successfully graduated?
- What was the average debt load of drop-outs?
- What was the average debt load of graduates?
- How long does it take a graduate of, say, a chemical engineering program to pay back their average student loan at by spending 25% of the average salary of a graduate of such a program?
- How long does it take a graduate of, say, a gender studies program to pay back their average student loan at by spending 25% of the average salary of a graduate of such a program?

## Taxes and lobbying expenses

For any given town in the state:

- how much was collected in tax dollars from citizens
- how much of this was spent on lobbyist organizations (e.g. towns sending taxpayer dollars to [The New Hampshire Municipal Association](https://www.nhmunicipal.org/2025-2026-legislative-policies-and-principles) which actively lobbies on many topics against the interests of citizens, or the [New Hampshire School Boards Association](https://nhsba.org/legislative-services/) or [other lobbyists](https://sos.nh.gov/media/1ghdjl2z/lobbyist-report-11-01-24.pdf) ?

## Judges

- how many judges does NH have?
- how many cases did each of them judge last year?  The year before?
- how many cases were overturned by the NH Supreme Court?
- what judge had the highest rate of cases being overturned?  Who had the lowest?
- what areas did specific judges have more or less cases overturned?  Is there some judge who has 2% of their zoning law cases overturned, but 50% of their criminal law cases overturned?

## etc.

This list is just a start.

While the above list strives to be non-partisan, it's inevitable that
certain prejudices have crept in ... but others can expand the list
with whatever issues they care about.  Number of wetland development
projects approved.  Number of garbage dumps created / closed.
Conviction rates for crimes against women.  Spending on homeless
veterans.  Whatever it is that citizens care about, governments and
non-profits operating under government regulation almost certainly
already collect the data, and just aren't sharing it effectively.

# The Solution: Open Data

Before we can craft legislation that forces government to share data, we have to consider exactly what it is we're looking for (Remember the old adage: "be careful what you wish for"). 

## Small tools, loosely coupled

Different citizens and groups will have different interests.

- one might care that per pupil spending is going up, and might pull from various data sources to assemble data to show expenditures per pupil, statewide, over time.
- another group might argue that high density urban areas are getting shortchanged in policing, and might pull for a different set of sources, and generate graphs to show policing results as compared with population density.
- etc.

Each citizen group should be encourged to build tools that do the analysis and reporting that they care about.

Again, the OGDI believes in [The Unix Philosophy](https://en.wikipedia.org/wiki/Unix_philosophy): small tools, loosely coupled.  Make the [government provide the data and the free market will do the rest](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar)! )

To support this low-effort modular approach to data import and digestion, we need to think about ...

## Data formats

Data formats vary from human readable (a JPG of a graph, or a PDF file of a budget) to the machine readable.

Machine readable data formats vary from the opaque (a binary file, or a spreadsheet with zero column headings) to the more transparent (a CVS file with column headers, or an XML file with a [DTD (Document Type Definition)[https://en.wikipedia.org/wiki/Document_type_definition).

Data varies from the easily comprehensible overviews( the list of [NH town tax rates](https://www.revenue.nh.gov/sites/g/files/ehbemt736/files/documents/2023-tax-rate-comparison.xlsx)), to the complete (the full [1,284 pages of the New Hampshire 2023 budget](https://www.das.nh.gov/budget/Budget2024-2025/GovernorsBudgetBill.pdf#06-56) ).

There is a tension between the desire to get every scrap of data that's available, on the one hand, and drowning users in minutia that may make it effectively impossible to make use of the data (can you look at the almost 1,300 page budget and - even using search in the PDF, find how much money goes to road building and maintenance?).

Additionally, there is the issue of ..

## Data format consistency over time

I recently did a small project importing NHLA spreadsheet data going
back ~10 years into a Rails app, and because I could export it as CSV,
it was trivial to import ... but even then, column headers changed
from year to year, and I ended up doing a lot of special casing to,
e.g., pull out canonical names which appear in 3 or 4 different
formats over various years.

That's from great, clean, simple data only going back a few years.

You can imagine the challenges in trying to parse out the DCYF
component of the state budget over 20 years, especially as divisions
get renamed, programs come and go, etc.

So we'd like data that is easy to compare across time (especially given that one bureacratic trick is to change measurements college, or change the definition of terms over time, to intentionally thwart measurability).  This pushes us in the direction of wanting to carefully specify, in legislation, exactly what must be provided.

...however, this is all in tension with the ideal of ...

## Re-use of existing data whenever possible

The state collects absolute mountains of data.  Every town has a budget generated in a spreadsheet. Every school system, likewise.  DCYF generates reams of internal reports.  Every police department shares data with the FBI.

The key is to, when possible, discover existing data sources that the government already creates internally, and then mandate sharing.

So ... would we rather a priori, when crafting legislation, specify
the 12 fixed things we want, each year, in a time sequence ... or
would we rather get massive data dumps?

I think the answer is "both".

# Legislative Approach: legislation -> data -> evangelism -> legislation -> ...

I have submitted bills over my first two-year term.  None got beyond
the committee stage.  I am optimistic that we can do better in the
future.

I intend to submit one or more bills this term, but I see whatever bills we craft as the start of a long salami slicing
tactic - we get one bill through this year, ideally, perhaps one that forces
the state police to share data.  Then we reach out to grad students in
political science, government, economics, etc. and point them to this
data source.  We also reach out to friendly media and organizations (Reason magazine, NHLA, etc etc)   We also loop in Dems and point out how the data supports
some of their goals.

We document those successes and take another bite next year - getting
DCYF to share information, maybe, or Department of Ed.

Then we keep circling back adding more and more data requirements, to
get additional fields.

Simultaneously perhaps we write a few data visualization tools
ourselves, and open source them.  (Perhaps "write tools" overstates
it; maybe we just write some blank spreadsheets that can import from
the data sources, or write a 5 line bash file that invokes curl
several times to download files, etc.)  The point of this exercise is
to create both a community ("evangelization") and also an ecosystem of
tools.

### Goals over time

The near term goal is to get some data, any data, in New Hampshire
available.

The medium term goal is to get a lot more data available in New
Hampshire, and to start using it for effective liberty activism.
Additionally, the Open Goverment Data Initiative can serve as a
catalog of data analysis tools / streams.  One can imagine a complete
ecosystem where government data sources exist on the web, and certain
analysis tools operate on them as streams / filters / webapps.
Perhaps one activist writes a tool that takes in the full state budget and produces a much simpler, easy to digest 

The long term goal is to spread the idea to other states, complete with
model legislation.


# Allied groups

I believe that the following groups are likely to be sympathetic to
our goals, and we may have success talking to them, evangelizing them,
and asking them for introductions to like-minded legislators.

The presence of a group on this list is not indicative of their endorsement!

- [Americans For Prosperity](https://americansforprosperity.org)
  - [AFP NH][https://nh.americansforprosperity.org/)
- [New Hampshire Liberty Alliance](https://www.nhliberty.org)


# Open Issues

1. learning what data sources already exist inside New Hampshire
government (I'm sure that there are thousands of reports already going
to the feds, to insurance companies, etc).  I know that police report
to the FBI using some sort of common data reporting system, for
example.

2. thinking about the tension between (a) easy legislation to write
that dumps tons of data, e.g. "post the TPS reports that you
already send the FBI", and (b) harder legislation that pulls out
exactly the data fields we want and makes it very easy for casual
users to start downloading stuff and doing things.

3. thinking about tools that we might write that could bridge the gap
from more complete data sources to more comprehensible data for the
masses.  I'm torn on this - I don't want the initiative to hang on
tools that we as activists write ... but I also don't think that we
can legislate civil servants into doing a good job.

4. codifying all of this into legislation ASAP (the deadline for
submitting bill ideas to OLS is 2024 Nov 22).

# How you can help

I'd love to hear your thoughts on any/all of this!

Next steps:

- join our Signal group.  https://signal.group/#CjQKIK73olErwV7kLGcTLL3Fvy5dW1TYfokyWXoXwChZXj6QEhA4TIgLCzKlCEO4NcXydx4O
- view the [github repo](https://github.com/travis4nh/open-gov-data-init) that holds this document
- clone the repo, make changes, add documents, etc. and create a PR.  I'll merge as appropriate.
- submit a [ticket](https://github.com/Travis4nh/open-gov-data-init/issues) to the repo with ideas



