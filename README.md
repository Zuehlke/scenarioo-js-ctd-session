# ZE CTD Session: Effective UI Testing with ScenariooJS and Protractor

Material of the Client Tech Day Session 2016 in Zurich (Schlieren).

We make this currently as a private repo but might think about migrating it later to an open repo.

Date of Session: 18.11.2016 13:30-15:00

Authors: Dominic Langenegger (@dola), Michael Werner (@mi-we) and Rolf Bruderer (@bruderol)

Major Goal & Content: 
* Using Scenarioo JS, Protractor and Jasmine 2 to efficiently test and document web applications
* Best Practicces from real projects how to do this right and effective
* How to structure and design those tests for Maintainability
* Coding Examples

## Session Abstract (as currently announced in the CTD program)

ScenariooJS, Protractor and Jasmine 2 are a perfect team to get your web applications tested and simultaneously documented from a user interface perspective. The session will focus on test design, since this is the most 
important part of successful and effective UI/E2E-Testing, and is as well useful for you if you are using any other UI Testing technologies (like pure Selenium).

We will discuss examples from the Swisscom Cloud Portal poject and how Rolf structured these tests to get a well-organized test suite and system documentation from a user's point of view. 

Furthermore we will also present some useful protractor tips and tricks and best practices for writing stable and maintainable UI/E2E-Tests more efficiently and how to prevent falling into pitfalls.

The session will be practically oriented with real examples from real projects and will also demonstrate some of the newest features of the Zühlke Open Source RUA Scenarioo. 

Get to know more in advance under http://scenarioo.org

## Plan / Topics / Timeline

 - Introduction (2', all)
     - Welcome
     - Goals
     - Who we Are
     - Focus Group Scenarioo
 - Motivation and Problem Statement (5', dola, rolf, michael)
   - (Stakeholders, Questions, What we have: Unit Tests, Integration Tests, UI Tests => Use UI Tests to satistfy needs)
   - Schraubzwinge: Test der alles zusammenhält, Klettern Methapher
   - What is UI/E2E Testing? What is the other end?
 - Solution: Scenarioo (5', dola)
   - Who knows Scenarioo?
   - Who uses UI Tests?
   - Short Introduction, _share slides with other Scenarioo Presentation_
 - Example Swisscom Cloud UI Tests (5', Rolf)
    - Small Demo: Click through a scenario in application
 - How to structure/design your UI tests? (15', Rolf)    
	- Select & Design of UseCases & Scenarios	
	- Use Case Isolation
	- Keep it simple!	
	- Independent Tests
	- Mocking DB / REST API
	- Parallel Tests
 - How to write those tests? (15-20', Michael & all)
   - Show code examples
   - Protractor / Jasmine
   - PageObjects etc.
   - Vanilla Protractor/Jasmine vs. Scenarioo Fluent DSL
   - Asynchronous Tasks
   - Protractor helps with interception of HTTP Requests, Mocking etc.
   - But my Build Server has no GUI => Headless Browser (e.g. PhantomJS)
   - When should steps be created? (Strategies, interception, in page object)
   - Automatic screenshots on expectation missed, error, at end of test (sucessfull/error)
   - Tips and tricks: Fixed screen size, turn off animations, ...
 - Scenarioo in other environments (Java, C#) (2', dola)
 - Outlook Scenarioo (2', dola)
    - Coming soon - Release 2.3
       - Full Text Search
       - Diff Viewer
	- Work in progress: JSON Format 3.0

If enough time:
 - Exercise: What are UseCases, Scenarios of your application?

## Open Points: Points to Add / Questions to Answer

* Using Firefox or Chrome for Testing? Advantages and Disadvantages
* Why not using Internet Explorer for Testing?
    * only if you can not avoid!
    * Mention some Arguments for not using it (even if your app has to support IE)


## Presentation Tooling

For important commands see scripts in `package.json`.

### Prez with RevealJS

See https://github.com/byteclubfr/prez

## References

### Pictures in Presentations

In general we prefer to use pictures under Creative Commons Zero Licence.

Sources: see according README files in images folders.

Some interesting sources for pictures:

* https://www.pexels.com
* https://pixabay.com
* http://blog.teachable.com/post/120193329843/the-13-ultimate-free-stock-photo-sites
