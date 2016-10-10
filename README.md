# ZE CTD Session: Effective UI Testing with ScenariooJS and Protractor

Material and Outcomes of the Client Tech Day Session 2016 in Zurich (Schlieren).

We make this currently as a private repo but might think about migrating it later to an open repo.

Date of Session: 18.11.2016 13:30-15:00

Authors: Dominic Langenegger (@dola), Michael Werner (@mi-we) and Rolf Bruderer (@bruderol)

Major Goal & Content: Using Scenarioo JS, Protractor and Jasmine 2 to efficiently test and document web applications form a user interface perspective and how to structure and design those tests.

## Session Abstract (as currently announced in the CTD program)

The Open Source RUA Scenarioo provides a new ScenariooJS library, that integrates perfectly with 
Jasmine 2 and Protractor to efficiently test and simultaneously document your Web-Applications 
from a user interface perspective. The session will focus on test design, since this is the most 
important part of successful and effective UI/E2E-Testing. We will present examples from the 
Swisscom Cloud Portal poject and how Rolf structured their tests there to get a well-organized 
test suite and system documentation from a user's point of view. We will also present some useful 
protractor tips and tricks and best practices for writing stable and maintainable UI/E2E-Tests 
more efficiently. The session will be practically oriented with real examples from real projects 
and will also demonstrate some of the newest Scenarioo features. Get to know more in advance 
under http://scenarioo.org

## Schedule

 - Introduction. Who are we? Agenda (1', dola)
 - Problem Statement (5', dola)
   - (Stakeholders, Questions, What we have: Unit Tests, Integration Tests, UI Tests => Use UI Tests to satistfy needs)
   - Schraubzwinge: Test der alles zusammenhält, Klettern Methapher
   - What is UI Testing? What is the other end?
 - Solution: Scenarioo (5', dola)
   - Who knows Scenarioo?
   - Who uses UI Tests?
   - Short Introduction, _share slides with other Scenarioo Presentation_
 - Example Swisscom Cloud UI Tests (5', Rolf)
    - Small Demo: Click through a scenario in application
 - How to structure/design your UI tests? (15', Rolf)
    - Main Learnings
	- Design of UseCases/Scenarios
	- Mocking DB
	- Use Case Isolation
	- Keep it simple!
	- Independent Tests
	- Parallel Tests
 - How to write those tests? (10', Michael)
   - Show code examples
   - Protractor / Jasmine
   - PageObjects etc.
   - Vanilla Protractor/Jasmine vs. Scenarioo Fluent DSL
   - Asynchronous Tasks
   - Protractor helps with interception of HTTP Requests, Mocking etc.
   - But my Build Server has no GUI => Headless Browser (e.g. PhantomJS)
   - When should steps be created? (Strategies, interception, in page object)
   - Automatic screenshots on expectation missed, error, at end of test (sucessfull/error)
 - Scenarioo in other environments (Java, C#) (2', dola)
 - Outlook Scenarioo  (2', dola)
    - Upcoming Features (Search, Diff Viewer)
	- 2.0 (JSON Format)

If enough time:
 - Exercise: What are UseCases, Scenarios of your application?
