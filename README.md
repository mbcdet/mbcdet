# Mohammad Bius

I work on systems that turn messy real-world data into structured output you can
actually check. Lately that's meant knowledge graphs, computer vision on open
geospatial data, and a lot of thinking about how a program should behave when the
evidence isn't good enough to answer.

That last part is the thread running through most of my projects. It's easy to
publish a number. It's harder to say where it came from, how confident you are,
and when you should have said nothing at all. I tend to spend my time there.

## What I work with

Python is my main language — packaging, command-line tools, FastAPI, and testing
with pytest. I've done graph modelling in Neo4j and Cypher, image work with OpenCV,
and geospatial work with GeoPandas, Shapely and PyProj. On the frontend side I use
TypeScript, React and Next.js. I rely on JSON Schema, content hashing and GitHub
Actions to keep results reproducible.

## Things I've built

**[Financial Knowledge Graph](https://github.com/mbcdet/financial-kg)**
A prototype for a problem I kept running into: what should a system conclude when
macro signals point in opposite directions? Instead of handing it to a model, this
one encodes a small curated ontology of macro drivers and assets, pulls live market
data into weighted logical states, and resolves the conflict with defeasible
reasoning in Cypher. Each result comes with a proof tree showing which force won
and why.

**[SiteFinder](https://github.com/mbcdet/SiteFinder)**
A command-line tool that finds local businesses with no website, a social-media-only
presence, or an outdated one, then ranks them as web-development prospects.
Discovery runs on OpenStreetMap, so it costs nothing. The site audit runs
independent checkers — SSL, mobile, performance, SEO, accessibility — over a single
fetch. The paid Google enrichment is a separate command that shows an estimated cost
and waits for confirmation before sending any request, so the tool cannot quietly
run up a bill. Tests run against fixtures, with no network required.

**[Business Showcase Platform](https://github.com/mbcdet/Business-showcase)**
A Turborepo monorepo for client business websites, with a shared component library
and per-business theming through CSS custom properties. Each site is defined by
configuration and data rather than a separate codebase, so adding one is mostly a
matter of describing it.

## Technical assessments

[Vienna Digital Twin Candidate Finder](https://github.com/mbcdet/vienna-digital-twin-candidate-finder) — A geospatial application for ranking Vienna buildings as Digital Twin candidates using Python, FastAPI, GeoPandas, React and MapLibre.

[Vienna Rooftop Intelligence](https://github.com/mbcdet/propx-rooftop-intelligence) — A reproducible pipeline for extracting structured rooftop information from Vienna open data using Python, OpenCV and geospatial tooling.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/mohammad-bius-810452184/)
